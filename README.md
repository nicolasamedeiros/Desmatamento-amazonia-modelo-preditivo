# Previsão de Desmatamento na Amazônia 🇧🇷 🌳

Este projeto explora modelos preditivos para estimar **como pode evoluir o desmatamento na Amazônia nos próximos cinco anos** com base em dados históricos. A proposta central é comparar duas abordagens estatísticas — **Regressão Linear Simples** e **Modelos ARIMA (AutoRegressive Integrated Moving Average)** — avaliando as diferenças entre elas e o quão representativas são para esse tipo de série temporal.

---

## 🧠 Objetivo

O objetivo do projeto é **realizar previsões quantitativas do desmatamento futuro** utilizando séries temporais históricas, buscando:

* Identificar tendências de crescimento ou redução do desmatamento;
* Comparar modelos estatísticos simples e avançados;
* Avaliar o desempenho de cada abordagem na projeção de dados ambientais;
* Demonstrar a aplicação prática de modelos de séries temporais em problemas reais.

---

## 📈 Metodologias Utilizadas

### 🔹 Regressão Linear Simples

* Modelo estatístico básico que ajusta uma linha reta aos dados históricos;
* Permite identificar tendências gerais ao longo do tempo;
* Utilizado como **modelo de referência (baseline)** para comparação com métodos mais robustos.

### 🔹 Modelo ARIMA

* Modelo clássico para análise e previsão de séries temporais;
* Capaz de capturar dependências temporais, tendência e padrões históricos;
* Muito utilizado em previsões econômicas, ambientais e financeiras;
* Apresenta maior flexibilidade quando comparado à regressão linear.

---

## 📁 Estrutura do Repositório

```
├── desmatamento_regressao_linear.ipynb   # Análise utilizando regressão linear
├── arima_x_regressao_linear.ipynb        # Comparação entre ARIMA e regressão
├── prodes_desmatamento.csv               # Base de dados histórica (PRODES)
├── requirements.txt                     # Dependências do projeto
└── README.md                             # Documentação do projeto
```

---

## 🧪 Resultados Esperados

Com este projeto, espera-se:

* Visualizar projeções futuras do desmatamento na Amazônia;
* Comparar o comportamento dos modelos preditivos;
* Identificar qual técnica apresenta melhor aderência aos dados históricos;
* Reforçar a importância da análise de séries temporais em estudos ambientais.

---

## 🚀 Tecnologias Utilizadas

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Statsmodels**
* **Matplotlib / Seaborn**

---

## 📌 Considerações Finais

Modelos preditivos aplicados a dados ambientais são ferramentas importantes para apoiar políticas públicas, estudos científicos e análises de impacto ambiental. Este projeto tem caráter **educacional e exploratório**, demonstrando como técnicas estatísticas podem ser utilizadas para entender fenômenos complexos como o desmatamento da Amazônia.
