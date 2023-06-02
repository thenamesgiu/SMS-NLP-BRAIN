## Desafio SMS - NLP

O repositório em questão apresenta um projeto de Natural Language Processing para predizer quais mensagens em um dataset são spam ou não

## O que foi utilizado?

- pandas;
- seaborn;
- sklearn;
- numpy;
- TensorFlow - Keras;
- matplotlib;
- NLTK.

## Processo:

- Preparação do ambiente com download do dataset e bibliotecas necessárias para NLP;
- O dataset é um file sem extensão, então salvei como .txt e converti para .csv em seguida;
- Preparação dos dados - limpei os dados removendo caracteres especiais, forçando lowcase, removendo stop words e fazendo stemming;
- Vetorizei os dados com Tfidf;
- Treino de modelo Random Forest Classifier - precisão de 97%;
- Treino de modelo Support Vector Machine (SVC) - precisão de 97%;
- Criação de modelo Long-Short Term Memory com Keras do TensorFlow - precisão de 98%, após sequenciação;
- Visualização de melhores resultados com heatmap de matriz de confusão.
