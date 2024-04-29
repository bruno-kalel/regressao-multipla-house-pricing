# 🏠 Previsão de Valores Imobiliários com Regressão Linear Múltipla

![Static Badge](https://img.shields.io/badge/python-%233776AB?style=for-the-badge&logo=python&logoColor=white)
![Static Badge](https://img.shields.io/badge/scikit--learn-%23F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Static Badge](https://img.shields.io/badge/pandas-%23150458?style=for-the-badge&logo=pandas&logoColor=white)
![Static Badge](https://img.shields.io/badge/matplotlib-%23135F9B?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/seaborn-%23444876?style=for-the-badge)

Este projeto utiliza técnicas de regressão linear múltipla para prever os preços de imóveis com base em diversas características. Os dados incluem informações como área, número de garagens, banheiros, lareiras, presença de acabamento em mármore e número de andares.

## 📊 Métricas de Avaliação do Modelo:

* **Coeficiente de Determinação (R²)**: 0.67
* **Erro Quadrático Médio (EQM)**: 5.02e+07
* **Raiz do Erro Quadrático Médio (REQM)**: 7.08e+03

## 📋 Descrição do Dataset
O conjunto de dados, [disponível no Kaggle](https://www.kaggle.com/datasets/greenwing1985/housepricing), contém informações sobre preços de imóveis e suas características associadas. As variáveis incluem:

* `precos`: Preço dos imóveis em uma determinada unidade de moeda.
* `area`: Área do imóvel em metros quadrados.
* `garagem`: Número de vagas de garagem.
* `banheiros`: Número de banheiros.
* `lareira`: Número de lareiras no imóvel.
* `marmore`: Indicador binário (0 ou 1) se o imóvel possui acabamento em mármore branco.
* `andares`: Indicador binário (0 ou 1) se o imóvel possui mais de um andar.

## 🛠️ Etapas do Projeto
* **Conhecendo o Dataset**: Importação das bibliotecas necessárias e leitura do conjunto de dados.
* **Análises Preliminares**: Exploração inicial dos dados, incluindo estatísticas descritivas e matriz de correlação para entender as relações entre as variáveis.
* **Visualização dos Dados**: Utilização de gráficos de boxplot e histograma para entender a distribuição dos dados e identificar possíveis outliers. Também plotagem de gráficos de dispersão para observar as relações entre as variáveis.
* **Estimando um Modelo de Regressão Linear**: Divisão dos dados em conjuntos de treino e teste. Também instanciação do modelo de regressão linear e ajuste aos dados de treino.
* **Previsões Pontuais**: Geração de previsões para dados de teste e exemplos específicos usando o modelo treinado.
* **Avaliação do Modelo**: Avaliação da performance do modelo utilizando métricas como o coeficiente de determinação (R²), erro quadrático médio (EQM) e raiz do erro quadrático médio (REQM).
