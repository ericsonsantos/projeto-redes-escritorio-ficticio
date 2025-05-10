# 🏢 Projeto de Redes - Escritório Fictício

Este projeto simula uma rede corporativa completa de um escritório fictício utilizando o **Cisco Packet Tracer**. A topologia foi desenvolvida com foco em segmentação de rede com VLANs, serviços essenciais (DHCP, HTTP, e-mail), roteamento e organização por departamentos.

---

## 📌 Objetivos do Projeto

- Planejar e simular uma rede corporativa segmentada
- Aplicar boas práticas de organização com VLANs
- Configurar serviços básicos como DHCP, HTTP e servidor de e-mail
- Testar conectividade entre dispositivos e comunicação entre departamentos

---

## 🖧 Topologia da Rede

![Topologia da rede](./Topologia%20da%20rede.png)

---

## 🧩 Estrutura da Rede

- **3 VLANs principais**:
  - VLAN 10 - Administração
  - VLAN 20 - Financeiro
  - VLAN 30 - Suporte
- **1 VLAN adicional**:
  - VLAN 50 - Servidores

---

## ⚙️ Serviços Configurados

### 🔐 VLANs
Configuração de VLANs com isolamento de tráfego por departamento.

![Tabela VLAN](./tabela%20vlan.png)

---

### 📧 Servidor de E-mail

Servidor de e-mail com domínio `empresa.com` habilitado para SMTP e POP3.

![Servidor de E-mail](./servirdor%20de%20e-mail.png)

---

### 🌐 Servidor DHCP

Distribuição automática de IPs para cada VLAN com pools separados.

![Servidor DHCP](./servirdor%20dhcp.png)

---

### 🌍 Servidor HTTP/HTTPS

Servidor web com páginas HTML e HTTPS ativado.

![Servidor HTTP](./servirdor%20http.png)

---

## 🧠 Conhecimentos Aplicados

- Segmentação de rede com VLANs
- Roteamento entre VLANs (Router-on-a-Stick)
- Configuração de serviços em ambiente simulado
- Testes de conectividade e validação de serviços
- Organização de rede para ambientes corporativos

---

## 💼 Tecnologias Utilizadas

- Cisco Packet Tracer
- Switch 2960 e Roteador 2911
- Servidor PT (para DHCP, HTTP, e-mail)
- PCs padrão com sistemas operacionais simulados

---

## 👨‍💻 Autor

**Ericson**  
Projeto feito como parte da construção de portfólio voltado para redes e infraestrutura.

---

