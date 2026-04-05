# 🔐 Router-on-a-Stick Lab (Cisco Packet Tracer)

## 📌 Descrição

Este laboratório demonstra a implementação de uma arquitetura **Router-on-a-Stick**, utilizando segmentação de rede com **VLANs**, distribuição automática de IP com **DHCP**, acesso remoto seguro via **SSH** e aplicação de boas práticas básicas de **segurança em interfaces**.

## 🧠 Objetivos

* Implementar comunicação entre múltiplas VLANs
* Configurar roteamento inter-VLAN com Router-on-a-Stick
* Automatizar endereçamento IP com DHCP
* Garantir acesso remoto seguro utilizando SSH
* Aplicar medidas básicas de segurança em interfaces

## 🏗️ Topologia

* 1 Roteador
* 1 Switch
* 3 VLANs configuradas
* Hosts distribuídos entre as VLANs

## ⚙️ Tecnologias Utilizadas

* VLANs (802.1Q)
* Router-on-a-Stick
* DHCP Server
* SSH (Secure Shell)

## 🔒 Medidas de Segurança

* Desativação de portas não utilizadas
* Associação de portas não utilizadas a uma **VLAN "morta"**
* Acesso remoto restrito via SSH (sem uso de Telnet)

## 🚀 Funcionalidades

* Comunicação entre dispositivos de VLANs diferentes
* Endereçamento IP automático via DHCP
* Gerenciamento remoto seguro no roteador

## 📂 Como usar

1. Abra o arquivo `.pkt` no Cisco Packet Tracer
2. Verifique as configurações de VLANs e subinterfaces no roteador
3. Teste conectividade com `ping` entre VLANs
4. Acesse o roteador via SSH


## 📝 Observações

Este laboratório foca em conceitos fundamentais de segmentação e segurança básica de rede, sendo ideal para estudos iniciais de redes e preparação para certificações como **CCNA**.

