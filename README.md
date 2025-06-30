# 📊 Dashboard de Vendas - Game Pass / Assinaturas

Este projeto foi desenvolvido como parte de um desafio de visualização de dados com Excel. O objetivo é transformar dados brutos de assinaturas de serviços em um dashboard claro, interativo e útil para análise de desempenho e tomada de decisões.

---

## 🧾 Sobre o Projeto

Criamos um dashboard de vendas com base em uma planilha de assinaturas de jogos (Game Pass, EA Play, Minecraft). O foco está na organização dos dados, extração de métricas e visualização eficiente no Excel.

---

## 📂 Dados Utilizados

O arquivo de entrada é uma planilha `.xlsx` chamada `base.xlsx`, com as seguintes informações:

- **Subscriber ID** – identificador único do cliente  
- **Name** – nome do assinante  
- **Start Date** – data de início do plano  
- **Subscription Type** – tipo de assinatura (Mensal, Anual, etc.)  
- **Subscription Price** – valor da assinatura principal  
- **Auto Renewal** – se a renovação automática está ativa  
- **EA Play Season Pass** + **Preço** – se assinou esse extra  
- **Minecraft Season Pass** + **Preço** – se assinou esse extra  
- **Coupon Value** – valor de desconto aplicado  
- **Total Value** – valor final pago após descontos

Esses dados estão organizados na aba `Bases` do Excel final.

---

## 📈 Estrutura do Dashboard

O arquivo final `dashboard_final.xlsx` contém:

- `Bases`: dados brutos organizados
- `Cálculos`: análises e tabelas dinâmicas com:
  - Receita total por mês
  - Distribuição por tipo de assinatura
  - Taxa de renovação automática
  - Aderência ao EA Play e Minecraft Pass
  - Ticket médio por tipo de plano
- `Dashboard`: instruções de gráficos sugeridos (coluna, pizza, barras)

---

## ▶️ Como Reproduzir o Dashboard

1. Faça o download do arquivo [`dashboard_final.xlsx`](./dashboard_final.xlsx)
2. Abra com o **Microsoft Excel 2016 ou superior**
3. Vá até a aba **Dashboard**
4. Siga as sugestões de gráficos e utilize as Tabelas da aba `Cálculos` para gerar visuais interativos (segmentações, filtros, gráficos)

---

## 💡 Gráficos Sugeridos

- 📅 Receita Total por Mês (gráfico de colunas)
- 📊 Distribuição de Tipos de Assinatura (pizza)
- 🔁 % com Renovação Automática (barra/pizza)
- 🎮 Aderência aos Passes (barra comparativa EA vs Minecraft)
- 💰 Ticket Médio por Plano (coluna)

---

## 🚀 Tecnologias Usadas

- Microsoft Excel
- Tabelas Dinâmicas
- Segmentações de Dados
- Gráficos Interativos

---

## 👤 Autor

Desenvolvido por Gabriela Tregnago Motta como parte de um desafio de análise de dados em Excel.

---
