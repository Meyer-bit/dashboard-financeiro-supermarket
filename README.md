# 📊 Dashboard Financeiro — Supermarket Sales Analysis

Dashboard interativo desenvolvido no **Power BI**, com foco em análise financeira, desempenho de produtos e comportamento de clientes de uma rede de supermercados. Projeto construído como peça de portfólio, simulando a entrega de um dashboard de BI para um cliente de varejo.

## 🎯 Sobre o projeto

O objetivo foi transformar uma base bruta de transações de vendas em um dashboard de 4 páginas com indicadores financeiros, análise de produtos, segmentação de clientes e sazonalidade — do jeito que seria entregue a um cliente real.

## 🗂️ Fonte dos dados

Dataset público **"Supermarket Sales"** ([Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)): 1.000 transações de 3 filiais, cobrindo o período de janeiro a março de 2019, com dados de produto, preço, forma de pagamento, tipo de cliente e avaliação de satisfação.

## 🛠️ Tecnologias utilizadas

- **Power BI Desktop** — construção do relatório
- **Power Query (M)** — limpeza, correção de locale e criação de colunas calculadas (mês, dia da semana, hora)
- **DAX** — medidas customizadas (Ticket Médio, Fluxo de Caixa)

## 📄 Estrutura do Dashboard

### Página 1 — Visão Geral Financeira
- Cartões de KPI: Receita Total, Ticket Médio, Imposto Total, Despesa Total
- Crescimento mensal (MoM)
- Receita por filial
- Fluxo de caixa (últimos 60 dias)

### Página 2 — Produtos e Categorias
- Receita por categoria de produto
- Curva ABC (ranking de categorias por receita, com % de participação)
- Quantidade vendida por categoria

### Página 3 — Segmentação de Cliente
- Receita por tipo de cliente (Membro x Normal)
- Receita por gênero
- Receita por forma de pagamento
- Avaliação média cruzada (filial x tipo de cliente)

### Página 4 — Sazonalidade e Tempo
- Receita por dia da semana
- Receita por hora do dia
- Receita diária ao longo do período

## 📸 Screenshots

<img width="1530" height="741" alt="visao_geral" src="https://github.com/user-attachments/assets/7feb3a76-020b-437f-a1bf-2b470c04283e" />
<img width="1524" height="725" alt="produtos" src="https://github.com/user-attachments/assets/b01d7ac4-71bc-4a1b-bcb4-60a68f0b5706" />
<img width="1518" height="742" alt="clientes" src="https://github.com/user-attachments/assets/7b7c7ba1-44ee-40b0-a6f5-1d46fb2e3e33" />
<img width="1524" height="735" alt="sazonalidade" src="https://github.com/user-attachments/assets/04458ef7-16d4-4d1c-b655-f0af9343eb8f" />

## 📌 Observações sobre os dados

O dataset público utilizado não possui identificador único de cliente, dados de orçamento ou estrutura de custo fixo. Por isso, métricas como churn, LTV, concentração de receita por cliente e ponto de equilíbrio não foram incluídas nesta versão — ficam como próximos passos em uma base com esse nível de granularidade.

## 👤 Autor

João Meyer
