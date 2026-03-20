# 📦 E-commerce Logistics Analysis — Olist

## 📊 Dashboard

![Dashboard](imagens/dashboard.png)

---

## 📌 Contexto

Este projeto analisa a operação logística de um e-commerce brasileiro (Olist), com foco na identificação de fatores que influenciam atrasos nas entregas.

A análise foi conduzida utilizando Excel, com abordagem orientada a problema de negócio.

---

## 🎯 Problema de Negócio

Os atrasos nas entregas impactam diretamente a experiência do cliente e podem gerar perdas operacionais e reputacionais.

A questão central é:

> **Quais fatores aumentam o risco de atraso nas entregas?**

---

## 🎯 Objetivo

Investigar os principais drivers de atraso logístico e gerar insights acionáveis para melhoria da operação.

---

## 🗂 Dataset

Base utilizada: **Olist E-commerce Dataset (Kaggle)**

Período analisado: **Set/2016 a Ago/2018**

---

## 📈 Métricas Utilizadas

* % de pedidos atrasados
* Prazo médio de entrega (dias)
* Atraso médio (dias)
* Valor médio do pedido
* Valor médio do frete
* Total de pedidos

---

## 🔍 Análises Realizadas

### 1. Prazo de entrega vs atraso

![Prazo vs atraso](imagens/prazo_vs_atraso.png)

Pedidos com prazos mais longos apresentam aumento significativo na taxa de atraso.

---

### 2. Tempo de despacho vs atraso

![Despacho vs atraso](imagens/despacho_vs_atraso.png)

O tempo de despacho dos vendedores impacta diretamente a probabilidade de atraso.

---

### 3. Análise do frete

O valor do frete foi analisado como variável explicativa do atraso.

Pedidos com frete mais elevado apresentam maior risco de atraso, sugerindo maior complexidade logística (ex: distância, regiões mais remotas ou operações mais complexas).

---

## 💡 Principais Insights

* Pedidos com prazo acima de 20 dias apresentam aumento acentuado na taxa de atraso, indicando limitações no planejamento logístico.

* O tempo de despacho dos vendedores tem impacto direto no atraso, evidenciando que parte do problema ocorre antes do envio.

* Pedidos com maior valor de frete apresentam maior risco de atraso, sugerindo maior complexidade operacional.

* O atraso é resultado da combinação de fatores ao longo da cadeia logística, e não de uma única causa isolada.

---

## 🧠 Recomendações

### Curto prazo

* Definir SLA de despacho (ex: até 2 dias)
* Monitorar sellers com atraso recorrente
* Criar alertas para pedidos com prazo elevado

### Médio prazo

* Revisar prazos prometidos ao cliente
* Priorizar pedidos com maior risco logístico
* Ajustar processos operacionais de envio

### Longo prazo

* Otimizar rotas logísticas
* Estruturar estratégia logística por região
* Avaliar criação de centros de distribuição

---

## ⚠️ Qualidade dos Dados

Foram identificadas pequenas inconsistências na base, incluindo:

* tempo de despacho negativo
* pedidos com dados incompletos

Esses casos foram tratados ou desconsiderados em análises específicas para garantir consistência dos resultados.

---

## 📌 Conclusão

Os atrasos logísticos são resultado da combinação de fatores estruturais e operacionais.

Prazos mais longos, maior tempo de despacho e maior complexidade logística aumentam significativamente o risco de atraso.

Melhorias dependem de ações integradas ao longo de toda a cadeia de entrega.

---

## 🛠 Ferramentas

* Excel
* Análise exploratória de dados (EDA)
* Estruturação de base analítica

---

## 📂 Estrutura dos Dados

### Dados Brutos

Os dados brutos foram obtidos do dataset público Olist (Kaggle) e incluem os seguintes arquivos:

- olist_customers_dataset.csv  
- olist_geolocation_dataset.csv  
- olist_order_items_dataset.csv  
- olist_order_payments_dataset.csv  
- olist_order_reviews_dataset.csv  
- olist_orders_dataset.csv  
- olist_products_dataset.csv  
- olist_sellers_dataset.csv  
- product_category_name_translation.csv  

---

### Base Tratada

A base analítica foi construída a partir da integração e tratamento dos dados brutos, consolidada na planilha:

- `olist_logistica_projeto.xlsx`

Essa base foi utilizada para cálculo das métricas, análises e construção do dashboard.


---

## 📬 Contato

Este projeto faz parte da minha transição para a área de Análise de Dados, com foco em resolver problemas reais de negócio com dados.

Atualmente desenvolvo dashboards em Excel, análises de KPIs e organização de bases de dados para apoiar decisões.

Aberto a oportunidades de projetos freelance e colaborações.
