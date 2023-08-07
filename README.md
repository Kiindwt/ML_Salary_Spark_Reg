# Projeto Spark: Previsão de Salário usando DataFrame e Machine Learning
Este é um projeto desenvolvido utilizando o Apache Spark para prever o salário com base em um conjunto de dados contendo informações sobre idade, gênero, nível de educação, cargo, anos de experiência, salário atual, país e raça dos indivíduos. O projeto foi implementado utilizando operações de DataFrame, SQL do Spark e um modelo de regressão do Spark para realizar a previsão de salários.

## Objetivo
O objetivo deste projeto é criar um pipeline de processamento de dados usando o Apache Spark para tratar os dados brutos, realizar análises exploratórias e, em seguida, desenvolver um modelo de regressão capaz de prever salários com base nas informações fornecidas.

## Tecnologias Utilizadas
+ Apache Spark: Plataforma de processamento distribuído para análise de dados em larga escala.
+ Spark DataFrame: API de manipulação de dados tabulares do Spark.
+ Spark SQL: Módulo do Spark para executar consultas SQL em conjuntos de dados.
+ Spark MLlib: Biblioteca do Spark para machine learning, incluindo algoritmos de regressão.

## Etapas do Projeto
+ Preparação dos Dados: Inicialmente, os dados brutos contendo as colunas Age, Gender, Education Level, Job Title, Years of Experience, Salary, Country e Race são carregados no Spark DataFrame. Quaisquer tratamentos iniciais, como remoção de dados faltantes e dados duplicados, são realizados nesta etapa.

+ Análise Exploratória: Utilizando operações do DataFrame e consultas SQL, são realizadas análises exploratórias para compreender melhor a distribuição dos dados, identificar tendências e padrões. Visualizações e estatísticas descritivas podem ser geradas para facilitar a compreensão dos dados.

+ Pré-Processamento dos Dados: Nesta fase, foi realizado transformações nos dados, como codificação de variáveis categóricas para preparar os dados para o treinamento do modelo.

+ Criação do Modelo de Regressão: Utilizando a biblioteca MLlib do Spark, um modelo de regressão é construído. Pode-se optar por usar Linear Regression, Random forest regression e Gradient Boosted Tree Regression. Os dados de treinamento são utilizados para ajustar o modelo.

+ Avaliação do Modelo: O modelo treinado é avaliado utilizando métricas de desempenho apropriadas para problemas de regressão, como o erro médio quadrático (RMSE) e coeficiente de determinação (R²). Isso permite entender quão bem o modelo está realizando as previsões.

+ Ajuste dos hiperparâmetros: Com base nos resultados da avaliação, o melhor modelo passou pelo processo de ajuste de hiperparâmetros para melhorar o desempenho da previsão.

+ Previsões: Uma vez que o modelo está treinado e avaliado, ele foi usado para fazer previsões de salário com base nos dados de teste e em novos dados não vistos anteriormente.