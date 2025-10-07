# Predição de Fechamento do Índice IBOVESPA
📊 Previsão do fechamento do IBOVESPA (Alta ou Baixa no próximo dia)

📌 **Contexto**

Este projeto foi desenvolvido como parte da **pós-graduação em Data Analytics da FIAP**.
O desafio consiste em construir um modelo preditivo capaz de antecipar se o índice IBOVESPA fechará em alta ou baixa no dia seguinte, com acurácia mínima de 75% nos últimos 30 dias analisados.
A solução foi projetada considerando boas práticas de ciência de dados: ingestão, limpeza, análise exploratória, feature engineering e modelagem supervisionada.

🛠️ **Tecnologias e Bibliotecas**
- Python (pandas, numpy, matplotlib, seaborn)
- Estatística e Séries Temporais: statsmodels, Prophet
- Machine Learning: scikit-learn, XGBoost, RandomForestClassifier
- Avaliação de Modelos: accuracy_score, confusion_matrix, classification_report

📂 **Estrutura do Projeto**
- **Importação e Pré-Processamento**
  - Leitura do dataset (Dados Históricos - Ibovespa - 10_Anos.csv)
  - Conversão de tipos (Data, Volume, Variação)
  - Tratamento de nulos e duplicidades
- **Análise Exploratória (EDA)**
  - Estatística descritiva
  - Visualização temporal dos preços de fechamento
  - Identificação de padrões de variação
- **Modelagem Preditiva**
  - Prophet (decomposição da série e previsão)
  - Random Forest Classifier
  - XGBoost Classifier
  - Comparação entre modelos
- **Avaliação dos Modelos**
  - Acurácia global
  - Matriz de confusão
  - Relatório de classificação (precisão, recall, F1-score)

🎯 **Resultados**
- Modelos foram avaliados em dados recentes.
- O melhor modelo alcançou acurácia ≥ 75% nos últimos 30 dias de pregão.
- A análise demonstrou robustez do uso de algoritmos ensemble (Random Forest e XGBoost) para prever movimentos de mercado.
