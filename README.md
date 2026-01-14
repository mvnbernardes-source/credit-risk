# Credit Risk Prediction

## Objetivo
Construir um modelo baseline de Machine Learning para previsão de inadimplência,
utilizando dados reais de crédito e avaliando os desafios de dados desbalanceados.

## Dataset
Dataset público **Home Credit Default Risk** (Kaggle).

Os arquivos de dados não estão versionados devido ao tamanho.
Para reproduzir o projeto, baixe o arquivo `application_train.csv` e coloque-o
na pasta `data/`.

Link:
https://www.kaggle.com/c/home-credit-default-risk

## Metodologia
- Seleção de variáveis numéricas
- Tratamento simples de valores ausentes
- Modelo Random Forest
- Avaliação com ROC AUC e métricas por classe

## Resultados
O modelo apresentou dificuldade em identificar a classe minoritária,
evidenciando o impacto do desbalanceamento dos dados.

## Conclusão
O projeto demonstra limitações reais de modelos simples em risco de crédito
e serve como baseline para estudos mais avançados.
