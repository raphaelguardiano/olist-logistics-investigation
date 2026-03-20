# 📦 E-commerce Logistics Analysis — Olist

## 📊 Dashboard

![Dashboard](dashboard/dashboard_final.png)

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

![Prazo vs atraso](images/prazo_vs_atraso.png)

Pedidos com prazos mais longos apresentam aumento significativo na taxa de atraso.

---

### 2. Tempo de despacho vs atraso

![Despacho vs atraso](images/despacho_vs_atraso.png)

O tempo de despacho dos vendedores impacta diretamente a probabilidade de atraso.

---

### 3. Frete vs atraso

![Frete vs atraso](images/frete_vs_atraso.png)

Pedidos com frete mais elevado apresentam maior risco de atraso, sugerindo maior complexidade logística.

---

## 💡 Principais Insights

* Pedidos com prazo acima de 20 dias apresentam aumento acentuado na taxa de atraso, indicando limitações no planejamento logístico para entregas de longa distância.

* O tempo de despacho dos vendedores tem impacto direto no atraso, sugerindo que parte do problema ocorre antes do envio.

* Fretes mais altos estão associados a maior risco de atraso, possivelmente devido à complexidade operacional dessas entregas.

* O atraso não é causado por um único fator, mas pela combinação de variáveis ao longo da cadeia logística.

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

* registros com tempo de despacho negativo
* pedidos sem datas completas

Esses casos foram tratados ou excluídos em análises específicas para garantir consistência dos resultados.

---

## 📌 Conclusão

Os atrasos logísticos no e-commerce analisado são resultado da combinação de fatores estruturais e operacionais.

Prazos mais longos, tempo de despacho elevado e maior complexidade logística aumentam significativamente o risco de atraso.

A melhoria da operação depende de ações coordenadas ao longo de toda a cadeia, desde o processamento do pedido até a entrega final.

---

## 🛠 Ferramentas

* Excel
* Análise exploratória de dados (EDA)
* Modelagem e estruturação de base analítica

---

## 📎 Estrutura do Projeto

```
data/
 ├── raw/
 ├── processed/

dashboard/
 ├── dashboard_final.png

excel_project/
 ├── olist_logistica_projeto.xlsx

images/
 ├── prazo_vs_atraso.png
 ├── despacho_vs_atraso.png
 ├── frete_vs_atraso.png
```

---

## 📬 Contato

Projeto desenvolvido como parte da transição para a área de Análise de Dados, com foco em resolução de problemas reais de negócio.
