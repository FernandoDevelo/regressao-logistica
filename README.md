# 📊 Previsão de Churn de Clientes com Machine Learning

Este projeto tem como objetivo analisar o comportamento de clientes e desenvolver um modelo preditivo capaz de identificar aqueles com maior risco de cancelamento (*churn*).

---

## 📌 Contexto

A retenção de clientes é um dos principais desafios de empresas orientadas a dados. Neste projeto, utilizo uma base contendo informações demográficas e financeiras — como país, gênero, score de crédito, idade, saldo e engajamento — para entender os fatores que influenciam o churn.

A partir dessa análise, foi desenvolvido um modelo de Machine Learning para prever a probabilidade de evasão de clientes, permitindo a criação de estratégias mais assertivas de retenção.

---

## 🎯 Objetivo

- Identificar padrões associados ao churn  
- Explorar os dados através de visualizações  
- Construir um modelo preditivo  
- Apoiar a tomada de decisão com base em dados  

---

## 📊 Análise Exploratória de Dados (EDA)

Foram realizadas análises visuais para entender o comportamento das variáveis:

### 🔹 Variáveis categóricas
- País  
- Sexo  
- Posse de cartão de crédito  
- Cliente ativo  

Utilizando gráficos de barras e histogramas com segmentação por churn, foi possível observar diferenças de comportamento entre grupos.

### 🔹 Variáveis numéricas
- Score de crédito  
- Idade  
- Tempo de relacionamento  
- Saldo  
- Salário estimado  

Através de boxplots, foram identificados padrões e possíveis outliers, além de diferenças relevantes entre clientes que cancelaram e os que permaneceram.

---

## 🤖 Modelo de Machine Learning

Foi utilizado um modelo de **Árvore de Decisão** para classificação do churn.

O modelo permite:
- Interpretabilidade  
- Identificação de padrões não lineares  
- Aplicação prática em cenários de negócio  

### 📌 Exemplo de previsão

O modelo retorna:

- `0` → Baixo risco de churn  
- `1` → Alto risco de churn  

Além disso, pode-se utilizar probabilidades para avaliar o nível de risco de cada cliente.

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Plotly  
- Scikit-learn  

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```bash
https://github.com/FernandoDevelo/regressao-logistica.git

2. instale as dependencias
pip install -r requirements.txt

3. execute o notebook
jupyter notebook
