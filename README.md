# 🔍 Fake News Classifier

Este projeto tem como objetivo construir um classificador de notícias falsas utilizando técnicas de Processamento de Linguagem Natural (PLN) e Machine Learning. O modelo é treinado com um conjunto de dados rotulado contendo notícias verdadeiras e falsas, e ao final é capaz de prever se uma nova notícia é falsa ou verdadeira.

## 📂 Sobre o Projeto

O notebook `FakeNews.ipynb` apresenta todas as etapas do pipeline de machine learning:

- Carregamento do conjunto de dados
- Pré-processamento de texto
- Vetorização (TF-IDF)
- Treinamento de modelo (PassiveAggressiveClassifier)
- Avaliação de desempenho
- Previsão de exemplos

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Natural Language Toolkit (NLTK)
- Matplotlib

## 📊 Dataset

O dataset utilizado possui duas colunas principais:

- `text`: o conteúdo da notícia
- `label`: rótulo (`FAKE` ou `REAL`)

O conjunto foi dividido em treino e teste para validar o desempenho do modelo.

## ✅ Resultados

- **Modelo Utilizado:** PassiveAggressiveClassifier
- **Acurácia:** Cerca de 92% no conjunto de teste
- **Métricas Adicionais:** Precision, Recall, F1-score (apresentadas no relatório de classificação)

