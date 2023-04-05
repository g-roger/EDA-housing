# Exploratory Data Analysis (EDA): House Prices

## Autor

Projeto desenvolvido por Gabriel Roger do Nascimento.


## Fonte de dados

O dataset utilizado neste projeto é proveniente do segundo capítulo do livro "Hands-On Machine learning" de Aurélien Géron. As informações presentes no conjunto de dados referem-se a casas na Califórnia, construídas nos anos 90.

## Objetivo

O objetivo deste projeto é explorar as características do dataset House Prices para criar uma regressão que projete preços de casas futuras. Para isso, serão aplicados processos de Machine Learning, com destaque para a regressão linear.

## Resumo do projeto

O projeto está disponível no arquivo EDA_housing.ipynb e foi dividido em etapas:

- Entendimento dos dados: nessa fase, foram realizados processos para compreender melhor o conjunto de dados. Foi criado um mapa para visualização das latitudes e longitudes.
- Tratamento de valores: nesta fase, foram tratados valores nulos, duplicados e outliers, utilizando a técnica do IQR.
- Análise exploratória: nesta fase, foram criadas hipóteses para o projeto e foi realizada uma análise mais detalhada das características das casas.
- Entendendo a importância das features: nessa fase, foi avaliada a importância de cada feature para o modelo de regressão.
- Aplicando regressão linear: utilizando as técnicas de Machine Learning, foi aplicada a regressão linear para projetar os preços de casas futuras.
- Métricas de avaliação do projeto: foram utilizadas diversas métricas, como o coeficiente de determinação (R²), o Mean Squared Error (MSE) e o Root Mean Squared Error (RMSE), para avaliar a eficácia do modelo de regressão.

## Bibliotecas

| Biblioteca | Descrição |
|------------|-----------|
| Pandas     | Biblioteca para manipulação e análise de dados em Python |
| Numpy      | Biblioteca para computação científica em Python |
| SimpleImputer | Classe do Scikit-learn para preenchimento de valores ausentes |
| Matplotlib | Biblioteca para visualização de dados em Python |
| Seaborn    | Biblioteca de visualização de dados estatísticos em Python |
| Folium     | Biblioteca para visualização de dados geográficos interativos em Python |
| Sklearn    | Biblioteca de aprendizado de máquina em Python |
| Mean_squared_error | Função do Sklearn para cálculo do erro quadrático médio |
| Mean_absolute_error | Função do Sklearn para cálculo do erro absoluto médio |
| R2_score   | Função do Sklearn para cálculo do coeficiente de determinação |
| Math       | Módulo em Python com funções matemáticas |
| Pearsonr   | Função do SciPy para cálculo do coeficiente de correlação de Pearson |
