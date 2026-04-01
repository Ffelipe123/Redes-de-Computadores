# Laboratório — Rede segmentada com VLANs e Trunk 🧩🔒

Descrição rápida  
Simulação de uma infraestrutura com segmentação por VLANs, trunks 802.1Q e roteamento inter‑VLAN (Router‑on‑a‑Stick), com foco em boas práticas de segurança na camada 2.

## Topologia
- Dois switches interconectados por EtherChannel (LACP) 🔗  
- Um roteador responsável pelo roteamento entre VLANs 🔁

## Objetivos 🎯
- Implementar segmentação de rede com múltiplas VLANs  
- Configurar enlaces trunk 802.1Q entre switches e roteador  
- Realizar roteamento inter‑VLAN (Router‑on‑a‑Stick)  
- Aplicar boas práticas de segurança em camada 2  
- Garantir isolamento de tráfego e controle de acesso 🔒

## Implementações realizadas ✅

### Segmentação de Rede
- VLANs de dados: 10, 20 e 30 🗂️  
- VLAN dedicada para gerenciamento 🛠️  
- Separação lógica entre diferentes grupos de hosts

### Trunking e Interconexão
- Trunks 802.1Q configurados entre os dispositivos 🚧  
- VLANs permitidas restritas nos enlaces  
- VLAN nativa alterada para uma VLAN não utilizada (isolamento)  
- Agregação de links com EtherChannel (LACP)

### Roteamento Inter‑VLAN
- Router‑on‑a‑Stick implementado  
- Subinterfaces com encapsulamento 802.1Q  
- Gateways configurados por VLAN ⚙️

### Serviços de Rede
- DHCP por VLAN para distribuição automática de endereços IP 📡

### Segurança de Camada 2
- VLAN nativa isolada (não usada)  
- Remoção da VLAN 1 dos trunks  
- DTP desativado nas interfaces  
- VLAN “black hole” para portas não utilizadas  
- Portas ociosas desativadas  
- VTP em modo transparente para evitar propagação indevida de VLANs 🔒

## Resultados principais 📌
- Comunicação entre VLANs funcionando via roteador  
- Tráfego segmentado e isolamento entre grupos  
- Redução da superfície de ataque na camada 2  
- Alinhamento com práticas recomendadas para ambientes corporativos ✅
