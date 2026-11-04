# 📊 Customer Churn Data Analysis & Retention Modeling

[PT] Projeto de Análise Exploratória de Dados (EDA) focado na identificação dos principais fatores de cancelamento de clientes (Churn) e na formulação de planos de ação estratégicos para retenção.
[EN] Exploratory Data Analysis (EDA) project focused on identifying key customer churn drivers and formulating strategic retention action plans.

---

## 🇧🇷 Português

### 📌 Visão Geral do Projeto
Este projeto analisa uma base de dados de clientes para diagnosticar o motivo de uma taxa inicial de cancelamento de **56,8%**. Utilizando Python, **Pandas** e **Plotly**, os dados foram limpos, transformados e visualizados para simular cenários de negócio e propor soluções operacionais imediatas.

### 💡 Principais Descobertas & Plano de Ação
1. **Contratos Mensais (Gargalo Primário):** 100% dos clientes no plano mensal cancelam o serviço. 
   - *Ação:* Migração incentivada de clientes para planos bimestrais ou anuais. A remoção isolada desta modalidade reduz o churn geral de **56,8% para 46,1%**.
2. **Atendimento ao Cliente (Call Center):** Clientes com 5 ou mais ligações ao suporte cancelam massivamente.
   - *Ação:* Alerta preventivo no CRM ao atingir a 3ª/4ª ligação para resolução prioritária de gargalos.
3. **Inadimplência (Dias de Atraso):** Atrasos superiores a 20 dias resultam em cancelamento inevitável.
   - *Ação:* Régua de cobrança preventiva e renegociação automática a partir do 15º dia de atraso.

> **Resultado Estimado:** A aplicação conjunta das ações operacionais reduz a taxa de cancelamento de **46,1% para 18,0%**, gerando uma queda de **28,1% no churn operacional**.

### 🛠️ Stack Técnica
- **Linguagem:** Python 3.10+
- **Manipulação de Dados:** `pandas`
- **Visualização de Dados:** `plotly.express`

---

## 🇺🇸 English

### 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a customer dataset to diagnose the root causes behind an initial **56.8% churn rate**. Leveraging Python, **Pandas**, and **Plotly**, the data was cleaned, transformed, and visualized to simulate business scenarios and propose immediate operational solutions.

### 💡 Key Insights & Action Plan
1. **Monthly Contracts (Primary Bottleneck):** 100% of customers on monthly contracts churn.
   - *Action:* Incentivize migration to bi-monthly or annual plans. Removing monthly plans drops overall churn from **56.8% to 46.1%**.
2. **Customer Support (Call Center):** Customers reaching 5 or more support calls show critical churn rates.
   - *Action:* Automated CRM alert on the 3rd/4th call for fast-track problem resolution.
3. **Payment Delays:** Delays exceeding 20 days lead to direct account cancellation.
   - *Action:* Automated debt negotiation triggers starting on day 15.

> **Estimated Impact:** Applying these operational strategies decreases the baseline churn rate from **46.1% down to 18.0%**, achieving a **28.1% reduction in overall churn**.

### 🛠️ Tech Stack
- **Language:** Python 3.10+
- **Data Manipulation:** `pandas`
- **Data Visualization:** `plotly.express`

---

## 📁 Como Executar / How to Run

1. **Clone o repositório / Clone the repo:**
   ```bash
   git clone [https://github.com/nwor1958/telecom-churn-data-analysis.git](https://github.com/nwor1958/telecom-churn-data-analysis.git)
   cd telecom-churn-data-analysis
