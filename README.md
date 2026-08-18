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

<!-- Adicione aqui as capturas de tela de cada página, ex: -->
<!-- ![Visão Geral](images/pagina1-visao-geral.png) -->
<!-- ![Produtos e Categorias](images/pagina2-produtos.png) -->
<!-- ![Segmentação de Cliente](images/pagina3-clientes.png) -->
<!-- ![Sazonalidade](images/pagina4-sazonalidade.png) -->

## 📌 Observações sobre os dados

O dataset público utilizado não possui identificador único de cliente, dados de orçamento ou estrutura de custo fixo. Por isso, métricas como churn, LTV, concentração de receita por cliente e ponto de equilíbrio não foram incluídas nesta versão — ficam como próximos passos em uma base com esse nível de granularidade.

## 👤 Autor

João Meyer
