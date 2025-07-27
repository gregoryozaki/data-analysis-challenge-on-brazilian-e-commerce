# Desafio de Análise de Dados - E-commerce Brasileiro

Este projeto é uma análise exploratória de dados (EDA) baseada no Brazilian E-Commerce Public Dataset by Olist, com foco em entender o desempenho do e-commerce, logística, satisfação do cliente, aspectos financeiros e impacto de campanhas promocionais.

---

## 🧠 Objetivo

Executar um pipeline completo de **ETL + EDA**, escolhendo **uma pergunta por tópico** (vendas, logística, cliente, financeiro, marketing) conforme o desafio proposto.

---

## ⚙️ Pipeline

### 1. ETL (Extração, Transformação e Carregamento)

- Leitura e verificação de todos os datasets
- Remoção de duplicatas
- Conversão de colunas de data
- Agregação da geolocalização (cliente e vendedor)
- Fusão completa dos dados em um único DataFrame (`merged_df`)
- Salvamento do dataset final processado

---

## 📊 Análises Exploradas

### 🔹 1. Tendência de Crescimento (Vendas)

> Como evoluíram as vendas ao longo do tempo?

- Análise mensal por categoria de produto
- Gráfico de linha com volume de vendas por mês
- Destaque para categorias com maior crescimento

---

### 🔹 2. Prazos de Entrega (Logística)

> Como anda o tempo médio de entrega? Quais fatores influenciam os atrasos?

- Cálculo de tempo médio e atraso de entrega
- Comparação entre entregas pontuais vs atrasadas
- Gráficos:
  - Tempo médio por categoria
  - Tempo médio entre atrasados
  - % de atrasos por categoria
  - Volume de pedidos por categoria

---

### 🔹 3. Atrasos x Satisfação do Cliente

> Atrasos impactam a avaliação dos clientes?

- Correlação entre atraso e nota (`review_score`)
- Gráfico comparativo da distribuição das avaliações com/sem atraso
- Conclusão clara: atrasos afetam negativamente a satisfação

---

### 🔹 4. Lucratividade por Categoria

> Quais categorias são mais lucrativas?

- Estimativa de custo com margem fixa (40%)
- Lucro bruto e lucro líquido por categoria
- Gráficos com ranking de categorias mais rentáveis

---

### 🔹 5. Eficácia de Campanhas Promocionais

> As promoções geram mais vendas?

- Comparação entre meses promocionais (Black Friday, Natal) vs comuns
- Gráfico de barras com destaque visual de meses com promoções
- Aumento de até 70% nas vendas e novos clientes em meses promocionais

---

## 📁 Estrutura de Arquivos

```
data-analysis-challenge-on-brazilian-e-commerce/
├── README.md
├── analise-dados.ipynb
└── dataset/
````

---

## 📚 Tecnologias Utilizadas

- **Python 3**
- **Pandas, NumPy** – manipulação de dados
- **Seaborn, Matplotlib, Altair** – visualização
- **Google Colab** – ambiente de desenvolvimento

---
