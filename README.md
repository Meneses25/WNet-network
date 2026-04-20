# WNet-network
Projeto que simula uma infraestrutura de provedor de internet (ISP) em ambiente controlado



# 🌐 ISP Network Simulation – Tianguá-CE

## 📌 Descrição

Simulação de infraestrutura de provedor de internet (ISP) em ambiente controlado, representando uma cidade como Tianguá-CE. O projeto inclui segmentação de rede, controle de acesso, tradução de endereços (NAT), monitoramento e controle de banda.

---

## 🏗️ Topologia

* 2 Roteadores (Core e Borda)
* 1 Switch de distribuição
* 3 Clientes
* 1 Servidor de monitoramento (NOC)

---

## ⚙️ Tecnologias Utilizadas

* VLAN (segmentação por bairros)
* DHCP por VLAN
* NAT (PAT / Overload)
* Roteamento estático
* SNMP (monitoramento)
* Syslog (logs centralizados)
* QoS (controle de banda)

---

## 🔐 Segurança e Controle

* Separação de clientes por VLAN
* Controle de acesso com ACL
* Tradução de endereços (NAT)
* Monitoramento de eventos da rede

---

## 📊 Funcionalidades Implementadas

* Comunicação entre VLANs (Router-on-a-stick)
* Distribuição automática de IP (DHCP)
* Acesso à rede externa simulada
* Monitoramento via SNMP
* Registro de logs via Syslog
* Controle de banda por cliente

---

## 🧠 Desafios Resolvidos

* Ajuste de NAT após implementação de VLAN
* Falha de comunicação devido a segmentação de rede
* Integração entre serviços (DHCP, NAT, QoS)
* Troubleshooting de conectividade

---

## 🚀 Resultados

Rede totalmente funcional com características de um provedor real, incluindo segmentação, controle de tráfego e monitoramento.

---

## 👨‍💻 Autor

Projeto desenvolvido por Nalberty Meneses Sulino
 
