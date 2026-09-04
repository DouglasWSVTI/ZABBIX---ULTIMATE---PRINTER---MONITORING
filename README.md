# 🖨️ Zabbix Ultimate Printer Monitoring

Template avançado para **monitoramento de impressoras Ricoh** utilizando **Zabbix + SNMP**, desenvolvido para fornecer visibilidade completa sobre utilização, produtividade e consumo das impressoras.

O projeto foi desenvolvido com foco em ambientes corporativos que precisam acompanhar o volume de impressão, identificar tendências de consumo e gerar indicadores para controle operacional e financeiro.

---

## 🚀 Funcionalidades

O template permite monitorar diversos indicadores das impressoras, incluindo:

### 📊 Contadores de impressão

- Total de páginas impressas
- Impressões por hora
- Impressões por dia
- Impressões por semana
- Impressões por mês

### 🖨️ Tipos de impressão

- Impressões em Preto e Branco
- Impressões Coloridas
- Impressões Simplex
- Impressões Duplex

### 📈 Indicadores e estimativas

- Consumo estimado de papel
- Estimativa de custo mensal
- Resmas utilizadas
- Custo mensal de impressão
- Acompanhamento do volume de impressão

---

## 🧩 Templates

O projeto contém templates específicos para diferentes tipos de monitoramento:

### `Zabbix_Ultimate_Template_Contador_De_Paginas`

Template destinado ao monitoramento dos contadores de páginas das impressoras.

Permite acompanhar:

- Páginas impressas por dia
- Páginas impressas por semana
- Páginas impressas por mês
- Resmas utilizadas
- Custo mensal

### `Zabbix_Ultimate_Template_Impressora_Ricoh`

Template principal para monitoramento de impressoras Ricoh através de SNMP.

---

## 🎨 Métricas de impressão

O monitoramento contempla:

| Métrica | Descrição |
|---|---|
| 🖤 Preto e Branco | Quantidade de páginas P&B |
| 🌈 Colorido | Quantidade de páginas coloridas |
| 📄 Simplex | Impressões em uma face |
| 📑 Duplex | Impressões frente e verso |
| 📦 Resmas | Estimativa de papel utilizado |
| 💰 Custo | Estimativa de custo mensal |
| 📊 Total | Total de páginas impressas |

---

## 🔧 Requisitos

Para utilizar o projeto, é necessário:

- **Zabbix 6.x ou superior**
- **Zabbix 7.x**
- Impressora Ricoh com suporte a **SNMP**
- SNMP habilitado na impressora
- Acesso de rede entre o Zabbix Server/Proxy e a impressora

> 💡 Recomenda-se utilizar SNMPv2c ou SNMPv3 de acordo com a política de segurança do ambiente.

---

## 📁 Estrutura do projeto

```text
.
├── images/
│   └── screenshots e imagens do projeto
│
├── templates/
│   └── templates Zabbix
│
├── README.md
└── LICENSE
