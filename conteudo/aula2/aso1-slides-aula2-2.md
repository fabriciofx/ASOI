---
marp: true
theme: gaia
backgroundColor: white
color: black
paginate: true
footer: Administração de Sistemas Operacionais I - Fabrício Barros Cabral <<fabricio.cabral@ead.ifpe.edu.br>>
---
<style>
img[alt~="center"] {
    display: block;
    margin: 0 auto;
}
</style>

<!-- _paginate: false -->
# **Administração de Sistemas Operacionais I (ASOI)**

## Aula 2 - Arquitetura de Rede do Windows Server 2022

---

## Introdução

- Arquitetura de Rede do Windows Server 2022 é bastante abrangente e flexível, projetada para oferecer suporte a uma ampla variedade de cenários e requisitos de rede além de permitir a configuração, gerenciamento e segurança de redes em ambientes corporativos

---

## Pilha de Protocolos

- Suporta uma pilha de protocolos de rede robusta, incluindo:
  - TCP/IP (Transmission Control Protocol / Internet Protocol)
  - DNS (Domain Name System)
  - DHCP (Dynamic Host Configuration Protocool)
  - SMB (Server Message Block)
  - LDAP (Lightweight Directory Access Protocol)

---

## Serviços de Rede Integrados

- DNS (Domain Name System): Tradução de nomes de domínio em endereços IP e vice-versa
- DHCP (Dynamic Host Configuration Protocol): Atribuição dinâmica de endereços IP, configurações de rede e outros parâmetros para dispositivos na rede
- NAT (Network Address Translation): Permite a tradução de endereços IP entre redes diferentes, útil para conexões à internet

---

## Serviços de Rede Integrados

- Active Directory: Oferece serviços de diretório para gerenciamento centralizado de usuários, grupos, computadores, políticas de segurança e recursos compartilhados na rede

---

## Funções de Rede

- Servidor de Arquivos: Compartilhamento de arquivos e pastas dentro da rede
- Servidor Web: Hospedagem de sites e aplicativos web
- Servidor de Impressão: Gerenciamento centralizado de impressoras e tarefas de impressão
- Serviços de Segurança de Rede: Oferece serviços de segurança de rede, incluindo firewalls integrados, políticas de grupo para controle de acesso
- Windows Defender para proteção contra ameaças

---

## Funções de Rede

- VPNs (Virtual Private Networks) para conexões seguras entre redes

---

## Gerenciamento Remoto

- Permite o gerenciamento remoto de servidores, permitindo que administradores acessem e controlem servidores de qualquer local com conexão à rede
- Ferramentas:
  - RDP (Remote Desktop Protocol)
  - PowerShell 

---

## Virtualização de Rede

- Por meio do Hyper-V, o Windows Server oferece recursos avançados de virtualização de rede, permitindo a criação e gerenciamento de redes virtuais isoladas para máquinas virtuais, oferecendo flexibilidade e segurança