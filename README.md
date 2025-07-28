# 📈 ETF-Forecasting-and-Clustering

Previsão do comportamento de ETFs de países selecionados utilizando múltiplos modelos de séries temporais e análise de cluster para identificar padrões entre ativos financeiros internacionais.

---

## 🎯 Objetivo

O projeto visa prever os valores de ETFs (Exchange-Traded Funds) de países do BRICS e outros mercados emergentes com diferentes abordagens estatísticas e de aprendizado de máquina. Além disso, aplicamos técnicas de clusterização para identificar semelhanças e agrupamentos de comportamento entre os ETFs analisados.

---

## 🛠️ Tecnologias e Ferramentas

- Python 🐍
- Pandas / NumPy / Matplotlib / Seaborn
- Scikit-learn
- Statsmodels
- XGBoost 
- Random Forest Regressor
- Gradient Boosting 
- KMeans 
- Yahoo Finance API
- Jupyter Notebook

---

## 🔎 Abordagem

- Coleta de dados históricos de ETFs via **Yahoo Finance API**
- Pré-processamento e análise exploratória
- Aplicação de múltiplos modelos preditivos:

  - XGBoost Regressor/GD Boosting/ Random Forest Regressor 
- Avaliação de desempenho com métricas como MAE, RMSE
- Clusterização dos ETFs com base em comportamento e variáveis derivadas (volatilidade, tendência etc.)

---

## 📊 Forecasting via assembleia de modelos

Abaixo está uma amostra visual do desempenho preditivo de um dos modelos utilizados:

<p align="center">
  <img src="images/comparativo_modelos.png" width="700"/>
  <br>
  <em>Figura: Comparativo de desempenho entre os modelos preditivos aplicados aos ETFs</em>
</p>




---

## 🔍 Clusterização de ETFs

Também foi realizada uma análise de agrupamento (clustering) para observar similaridades entre os ETFs com base em suas séries temporais:

- KMeans com Elbow Method

---


