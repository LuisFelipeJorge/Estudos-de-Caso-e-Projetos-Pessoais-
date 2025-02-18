# Análise Estatística de Fatores de Risco para Doença Arterial Coronariana (DAC)

## Motivação

A estatística desempenha um papel fundamental na análise e interpretação de dados, permitindo a extração de insights relevantes para tomada de decisão. O objetivo deste estudo é aplicar conceitos estatísticos para investigar a relação entre fatores de risco e a probabilidade de desenvolvimento da Doença Arterial Coronariana (DAC). Se procura neste projeto aplicar especialmente modelos lineares generalizados (GLMs), ferramentas relevantes na análise de dados pela forma que permitem agregar interpretação sobre o relacionamento entre diferentes varáiveis em um problema.   

Além disso, a implementação deste projeto visa fortalecer habilidades essenciais na área de **ciência de dados e estatística**, como:  
- **Análise exploratória de dados (EDA)** para identificação de padrões e possíveis relações entre variáveis.  
- **Ajuste e interpretação de modelos estatísticos**, considerando hipóteses, suposições e métricas de avaliação.  
- **Tomada de decisão baseada em evidências**, utilizando critérios estatísticos para a seleção de variáveis relevantes.  

## Desafio
Durante a condução do projeto, surgiram desafios fundamentais que impulsionaram o aprendizado:  

- **Exploração aprofundada dos dados:** Entender a estrutura do dataset e aplicar técnicas de visualização menos conhecidas fora do ambiente acadêmico para identificar padrões, colinearidades e potenciais interações entre variáveis.  
- **Preparação dos dados:** Avaliar e testar diferentes estratégias de tratamento de valores ausentes e outliers, analisando seus impactos na modelagem.  
- **Ajuste e seleção de modelos:** Compreender a influência de diferentes transformações e ajustes nos dados sobre a performance do modelo, além de utilizar critérios estatísticos para selecionar as variáveis mais relevantes.  
- **Desbalanceamento da variável-alvo:** Explorar abordagens para lidar com a baixa incidência de eventos positivos no dataset, como a técnica SMOTE, visando melhorar a capacidade preditiva do modelo.  

## Proposta
Para enfrentar esses desafios, este estudo utiliza **Modelos Lineares Generalizados (GLMs)** para modelar a probabilidade de ocorrência de DAC com base em variáveis clínicas e demográficas disponíveis no dataset público *Framingham Heart Study* [(Kaggle)](https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset).

O pipeline do projeto inclui as seguintes etapas:  

1. **Análise exploratória de dados (EDA)**: inspeção da distribuição das variáveis, identificação de padrões e pré-seleção de variáveis candidatas.  
2. **Pré-processamento dos dados**: tratamento de valores ausentes, criação de variáveis dummies e técnicas de balanceamento de classes.  
3. **Ajuste de modelos estatísticos**: implementação de modelos GLMs para entender a relação entre os fatores de risco e a DAC.  
4. **Avaliação do modelo**: análise da significância das variáveis, interpretação dos coeficientes e validação dos resultados.  
5. **Aprimoramento do modelo**: exploração de técnicas como SMOTE e comparação de diferentes abordagens para otimizar a capacidade preditiva.  

O estudo é conduzido com **foco na interpretação estatística dos resultados**, buscando entender não apenas a performance do modelo, mas também os **insights clínicos que ele pode proporcionar**.  

Este projeto faz parte de um estudo independente para aprofundamento em **estatística aplicada e modelagem preditiva**, consolidando conhecimentos que podem ser aplicados em diferentes contextos de ciência de dados. 🚀  


---

# Statistical Analysis of Risk Factors for Coronary Heart Disease (CHD)

## Motivation

Statistics plays a fundamental role in the analysis and interpretation of data, allowing the extraction of relevant insights for decision-making. The aim of this study is to apply statistical concepts to investigate the relationship between risk factors and the likelihood of developing coronary heart disease (CHD). In particular, this project seeks to apply generalized linear models (GLMs), which are relevant tools in data analysis because they allow interpretation of the relationship between different variables in a problem.   

In addition, the implementation of this project aims to strengthen essential skills in the area of **data science and statistics**, such as:  
- **Exploratory data analysis (EDA)** to identify patterns and possible relationships between variables.  
- **Fitting and interpreting statistical models**, considering hypotheses, assumptions and evaluation metrics.  
- Evidence-based decision making**, using statistical criteria to select relevant variables.  

## Challenge
During the course of the project, fundamental challenges arose that drove learning:  

- **In-depth data exploration:** Understanding the structure of the dataset and applying lesser-known visualization techniques outside the academic environment to identify patterns, collinearities and potential interactions between variables.  
- **Data preparation:** Evaluate and test different strategies for dealing with missing values and outliers, analyzing their impact on modeling.  
- **Model adjustment and selection:** Understand the influence of different transformations and adjustments to the data on the model's performance, as well as using statistical criteria to select the most relevant variables.  
- **Target variable imbalance:** Explore approaches to dealing with the low incidence of positive events in the dataset, such as the SMOTE technique, with a view to improving the model's predictive capacity.  

## Proposal
To address these challenges, this study uses **Generalized Linear Models (GLMs)** to model the probability of CAD occurrence based on clinical and demographic variables available in the public dataset *Framingham Heart Study* [(Kaggle)](https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset).

The project pipeline includes the following steps:  

1. **Exploratory data analysis (EDA)**: inspection of the distribution of variables, identification of patterns and pre-selection of candidate variables.  
2. **Data pre-processing: treatment of missing values, creation of dummy variables and class balancing techniques.  
3. **Fitting statistical models**: implementation of GLM models to understand the relationship between risk factors and CAD.  
4. **Model evaluation**: analysis of the significance of the variables, interpretation of the coefficients and validation of the results.  
5. **Model improvement**: exploration of techniques such as SMOTE and comparison of different approaches to optimize predictive capacity.  

The study is conducted with a **focus on the statistical interpretation of the results**, seeking to understand not only the performance of the model, but also the **clinical insights it can provide**.  


This project is part of an independent study to delve deeper into **applied statistics and predictive modeling**, consolidating knowledge that can be applied in different data science contexts. 🚀  
