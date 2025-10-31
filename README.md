# Detecção de Fraude em Cartão de Crédito com Redes Neurais

## Objetivo

Desenvolver um classificador de transações fraudulentas utilizando Redes Neurais, conforme orientações do [Projeto Final da disciplina de Engenharia de Redes Neurais Artificiais](09_Intrucoes_para_Projeto_Final.md). O projeto aborda a resolução de um problema real de engenharia com redes neurais, explorando diferentes arquiteturas, funções de perda, otimizadores e regularizações por meio de um estudo de ablação.

## Projeto final requisitos

- Resolver um problema prático de engenharia (fraudes em cartão de crédito).
- Desenvolver e avaliar arquiteturas de Redes Neurais Artificiais (MLP, RandomForest, XGBoost, LightGBM).
- Realizar estudo de ablação: adição/removal de camadas, comparação de funções de perda, ajuste de otimizadores/taxa de aprendizado.
- Comparar resultados utilizando métricas adequadas (Precision, Recall, F1, ROC AUC).
- Apresentação dos resultados como solicitado no cronograma da disciplina.

## Base de Dados

- **Fonte:** [creditcard.csv](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Descrição:** Conjunto de dados de transações ocorridas em setembro de 2013 por titulares europeus. Possui 284.807 transações, sendo 492 fraudes (menos de 0,2%).

## Metodologia

- Exploração e pré-processamento dos dados.
- Separação em treino e teste estratificados.
- Testes de múltiplas arquiteturas e configurações de redes.
- Estudo de ablação conforme requisitos do projeto final.

## Principais Métricas

- `Accuracy`
- `Precision`
- `Recall`
- `F1 Score`
- `ROC AUC`

Este projeto foi desenvolvido por [owMath](https://github.com/owMath) para a disciplina de Engenharia de Redes Neurais Artificiais, seguindo o arquivo de instruções [09_Intrucoes_para_Projeto_Final.md](09_Intrucoes_para_Projeto_Final.md).
