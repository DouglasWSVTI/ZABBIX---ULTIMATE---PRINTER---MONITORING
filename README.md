# 🖨️ Zabbix Ultimate Printer Monitoring

Template avançado para **monitoramento de impressoras Ricoh ** utilizando **Zabbix + SNMP**.

O projeto foi desenvolvido para ambientes corporativos que precisam acompanhar de forma centralizada o **volume de impressão, tipos de impressão, consumo de papel e estimativa de custos**, permitindo maior controle e visibilidade sobre a utilização das impressoras.

---

## 🚀 Funcionalidades

O projeto disponibiliza diversas métricas para acompanhamento detalhado das impressões.

### 📊 Contadores de impressão

Monitoramento dos principais contadores de páginas:

- Total de impressões por dia
- Total de impressões por semana
- Total de impressões por mês
- Total de impressões
- Total de impressões por hora

### 🖨️ Impressões por tipo

Monitoramento separado das impressões de acordo com o tipo:

#### 1 Cor

- Total de impressões 1 Cor por dia
- Total de impressões 1 Cor por hora
- Total de impressões Duplex 1 Cor por dia
- Total de impressões Duplex 1 Cor por hora

#### 2 Cores

- Total de impressões 2 Cores por dia
- Total de impressões 2 Cores por hora
- Total de impressões Duplex 2 Cores por dia
- Total de impressões Duplex 2 Cores por hora

#### 4 Cores

- Total de impressões 4 Cores por dia
- Total de impressões 4 Cores por hora
- Total de impressões Duplex 4 Cores por dia
- Total de impressões Duplex 4 Cores por hora

#### Preto e Branco

- Total de impressões P&B por dia
- Total de impressões P&B por hora
- Total de impressões Duplex P&B por dia
- Total de impressões Duplex P&B por hora

---

## 📈 Indicadores e estimativas

Além dos contadores, o projeto permite acompanhar indicadores relacionados ao consumo e aos custos de impressão:

- 📄 Consumo estimado de papel
- 📦 Estimativa de resmas utilizadas
- 💰 Estimativa de custo mensal
- 📊 Volume de impressão
- 🖨️ Comparação entre tipos de impressão
- 📈 Acompanhamento da utilização ao longo do tempo

---

## 🧩 Templates

O projeto contém templates específicos para diferentes necessidades de monitoramento.

### `Zabbix_Ultimate_Template_Contador_De_Paginas`

Template destinado ao monitoramento e acompanhamento dos contadores de páginas das impressoras.

Permite acompanhar:

- Impressões por dia
- Impressões por semana
- Impressões por mês
- Impressões por hora
- Resmas utilizadas
- Custo mensal estimado

### `Zabbix_Ultimate_Template_Impressora_Ricoh`

Template principal destinado ao monitoramento de impressoras **Ricoh** através do protocolo **SNMP**.

---

## 🎨 Métricas de impressão

| Métrica | Descrição |
|---|---|
| 🖤 Preto e Branco | Quantidade de páginas impressas em P&B |
| 🌈 Colorido | Quantidade de páginas impressas em cores |
| 📄 Simplex | Impressões realizadas em uma única face |
| 📑 Duplex | Impressões realizadas frente e verso |
| 📦 Resmas | Estimativa de papel utilizado |
| 💰 Custo | Estimativa de custo das impressões |
| 📊 Total | Total de páginas impressas |

---

## 🔧 Requisitos

Para utilizar o projeto, é necessário:

- **Zabbix 6.x ou superior**
- Impressora **Ricoh** com suporte a SNMP
- SNMP habilitado na impressora
- Conectividade de rede entre o **Zabbix Server/Proxy** e a impressora
- OIDs/MIBs compatíveis com o modelo da impressora

### 📡 Protocolo SNMP

O monitoramento utiliza **SNMP** para realizar a coleta das informações diretamente das impressoras.

Compatibilidade:

- SNMPv2c
- SNMPv3

> 💡 Recomenda-se utilizar SNMPv3 quando disponível, de acordo com as políticas de segurança do ambiente.

---

## 📁 Estrutura do projeto


.
├── docs/
│   └── Documentação e informações técnicas do projeto
│
├── images/
│   └── Imagens, gráficos e screenshots dos dashboards
│
├── mibs/
│   └── Arquivos MIB utilizados no monitoramento via SNMP
│
├── templates/
│   └── Templates do Zabbix para monitoramento das impressoras Ricoh
│
├── LICENSE
│   └── Licença de utilização do projeto
│
└── README.md
    └── Documentação principal do projeto
