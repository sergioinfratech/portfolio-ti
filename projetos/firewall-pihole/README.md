# 🔥 Projeto: Firewall com pfSense + Pi-hole

## ✅ Objetivo
Implementar uma solução de segurança e filtragem de conteúdo para redes domésticas ou empresariais, utilizando pfSense como firewall e Pi-hole como bloqueador de anúncios e domínios indesejados.

## ⚙️ Tecnologias
- pfSense (Firewall)
- Pi-hole (DNS Filtering)
- VirtualBox ou Proxmox (para simulação)
- Rede local com acesso à internet

## 📋 Etapas

### 🔐 Configuração do pfSense
1. Instalar pfSense em máquina virtual ou hardware dedicado
2. Configurar interfaces WAN e LAN
3. Criar regras de firewall básicas
4. Ativar DHCP e DNS Resolver

### 🚫 Integração com Pi-hole
1. Instalar Pi-hole em máquina separada (Raspberry Pi ou VM)
2. Redirecionar DNS da rede para o IP do Pi-hole
3. Adicionar listas de bloqueio personalizadas
4. Testar bloqueio de anúncios e sites indesejados

## 💡 Dicas
- Use listas atualizadas como [Firebog](https://firebog.net/)
- Monitore logs do pfSense para identificar tráfego suspeito
- Combine com VPN para maior privacidade

## 📸 Resultados
*Em breve prints da interface do pfSense e painel do Pi-hole mostrando bloqueios ativos*
