# 🔐 Projeto: Servidor Web Seguro

## ✅ Objetivo
Configurar um servidor Apache com certificado SSL gratuito usando Let's Encrypt, garantindo segurança na comunicação web.

## ⚙️ Tecnologias
- Ubuntu Server
- Apache2
- Certbot (Let's Encrypt)

## 📋 Etapas
1. Instalar Apache: `sudo apt install apache2`
2. Abrir portas 80 e 443 no firewall
3. Instalar Certbot: `sudo apt install certbot python3-certbot-apache`
4. Gerar certificado: `sudo certbot --apache`
5. Testar renovação automática: `certbot renew --dry-run`

## 💡 Dicas
- Use DNS válido para evitar erros na emissão do certificado
- Configure redirecionamento automático de HTTP para HTTPS

## 📸 Resultados
*Em breve prints da configuração e acesso seguro via navegador*
