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

## Aula 2 - Arquitetura do Sistema Operacional Windows Server 2022

---

## Introdução

- O Windows Server 2022 é a versão mais recente do sistema operacional para servidores da Microsoft
- Projetado para oferecer desempenho, segurança e funcionalidades avançadas para ambientes de servidor
- Sua arquitetura é baseada em camadas e módulos que permitem a execução de uma variedade de serviços e funções de servidor.

---

## Introdução

- Alguns elementos-chave da arquitetura do Windows Server 2022
  - Kernel
  - Subsistema de Segurança
  - Serviços de Diretório
  - Serviços de Rede
  - Virtualização
  - Gerenciamento e Ferramentas
  - Interface de Usuário

---

## Kernel

- É o núcleo do sistema operacional, responsável por gerenciar recursos de hardware, como memória, processos e drivers
- Fornece uma base para que outros componentes do sistema operacional funcionem

---

## Subsistema de Segurança

- O Windows Server 2022 possui um robusto subsistema de segurança que inclui o Windows Defender, que oferece proteção contra ameaças de segurança
- Possui políticas de segurança para controlar o acesso e os privilégios de usuário

---

## Serviços de Diretório

- O Active Directory é um componente crucial em ambientes corporativos, permitindo a organização e gerenciamento centralizado de recursos, como usuários, computadores e políticas de segurança
- O Windows Server 2022 aprimora esses serviços para oferecer maior escalabilidade e desempenho.

---

## Serviços de Rede

- O sistema operacional oferece uma variedade de serviços de rede, incluindo:
  - DNS (Domain Name System) para tradução de nomes de domínio em endereços IP
  - DHCP (Dynamic Host Configuration Protocol) para atribuição dinâmica de endereços IP
  - Outros serviços de comunicação e conectividade

---

## Virtualização

- Possui recursos avançados de virtualização, permitindo a criação e gerenciamento de máquinas virtuais usando o Hyper-V
- Essa funcionalidade é essencial para consolidar servidores físicos, oferecer alta disponibilidade e simplificar a administração de infraestrutura

---

## Gerenciamento e Ferramentas

- Inclui uma série de ferramentas de gerenciamento, que permitem aos administradores configurar, monitorar e gerenciar servidores de forma eficiente e centralizada
  - Server Manager
  - PowerShell
---

## Interface de Usuário

- Proporciona flexibilidade aos administradores para escolher a maneira como desejam interagir e gerenciar o sistema
- Possui duas interfaces de usuário:
  - Oferece uma interface de usuário gráfica (GUI) 
  - Suporta a administração por meio de linha de comando
