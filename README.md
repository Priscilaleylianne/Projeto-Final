# Projeto Final

# Análise de Recompra em Comércio Eletrônico: Dataset Instacart

## Introdução

Este projeto apresenta um estudo baseado em técnicas de aquisição, pré-processamento e análise exploratória de dados utilizando o conjunto de dados **Instacart Market Basket Analysis**. O objetivo é compreender padrões de recompra de produtos em um ambiente de e-commerce, com foco na preparação dos dados para futuras aplicações de Machine Learning.

As atividades foram desenvolvidas no contexto da disciplina **Aquisição e Pré-Processamento de Dados**.

---

## Objetivo do Projeto

Antecipar o comportamento de compra dos clientes na plataforma Instacart, visando responder à seguinte questão:

> **"Como prever os produtos que um cliente irá recomprar em seu próximo pedido, com base em seu histórico de compras?"**

---

##  Perguntas Analíticas

1. Quais produtos apresentam maior taxa de recompra entre os clientes?
2. Quais horários e dias da semana concentram a maior quantidade de reorders?
3. Existe um padrão no número de dias entre os pedidos de um mesmo cliente?
4. Quais departamentos ou corredores concentram os produtos mais frequentemente reordenados?
5. Como o comportamento de recompra varia entre diferentes perfis de cliente (ex.: frequência de pedidos, número de itens por carrinho, horário habitual de compra)?

---

## Coleta de Dados

Os dados foram obtidos do repositório público do Kaggle:

- [Instacart Market Basket Analysis Dataset](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)

**Arquivos utilizados:**
- `orders.csv`
- `order_products__prior.csv`
- `order_products__train.csv`
- `products.csv`
- `aisles.csv`
- `departments.csv`

**Limitações do Dataset:**
- Ausência de informações demográficas dos clientes.
- Falta de dados financeiros (preço ou valor dos pedidos).
- Dataset limitado a histórico de compras, sem contexto externo (ex.: campanhas, sazonalidade).

---

## Pré-Processamento dos Dados

Etapas principais realizadas:

- **Tratamento de valores ausentes**  
- **Conversão de tipos (inteiros, datas)**
- **Integração relacional entre arquivos** (`JOINs` entre produtos, pedidos, usuários)
- **Criação de atributos derivados** (quantidade de recompras, frequência média, intervalos entre pedidos)
- **Normalização (quando necessário)**
- **Redução de dimensionalidade** (seleção de atributos mais relevantes)

Todas as transformações foram documentadas e justificadas conforme a necessidade analítica.

---

## Análise Exploratória dos Dados (EDA)

Ferramentas e técnicas utilizadas:

- Estatísticas descritivas (médias, medianas, desvio padrão)
- Gráficos de histograma e boxplot
- Gráficos de barras e pizza (produtos mais vendidos e mais recomprados)
- Mapas de calor (correlações entre variáveis numéricas)
- Séries temporais agregadas (análise por dia da semana, hora do dia, posição no carrinho)

Essas análises foram fundamentais para responder às perguntas analíticas e orientar futuras aplicações de Machine Learning.

---
Devido ao seu tamanho final superior 100 MB, ele não pôde ser hospedado diretamente neste repositório GitHub.
Você pode baixá-lo através do link abaixo:

🔗 [Clique aqui para acessar arquivos no Google Drive](https://drive.google.com/drive/folders/1DQar2vxabo_mPO0yLvIkUxy_TWzMNZl4?usp=sharing)

Ou atráves do arquivo txt, que encontra-se no repositório GitHub.

## Referências

- **KAGGLE**. *Instacart Market Basket Analysis*. Disponível em: [https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis). Acesso em: junho de 2025.

---

## Status do Projeto

**Concluído — Aquisição, Pré-Processamento e Análise Exploratória Finalizadas.**  
**Em planejamento — Aplicação de algoritmos de Machine Learning para previsão de recompra.**

---

## Equipe

- Alexandre Teixeira da Silva
- César Braz de Oliveira
- Ícaro Guimarães Canto
- Priscila Leylianne da Silva Gonçalves
