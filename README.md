# Classificador de Vinho: Vermelho ou Branco 🍷

Modelo de **Machine Learning** para **classificação binária** que identifica se um vinho é **tinto (red)** ou **branco (white)** com base em suas propriedades físico-químicas (acidez, açúcar residual, SO₂, álcool, pH, etc.).

- **Algoritmo utilizado**: `DecisionTreeClassifier` do scikit-learn  
- **Dataset**: Wine Quality (UCI) – combinação de vinhos tintos e brancos (~6.500 amostras)  
- **Acurácia típica**: > 98–99% (muito alta porque as características diferem bastante entre red e white)

## Visão Geral do Projeto

Objetivo: Treinar um modelo simples e interpretável que classifica o tipo de vinho e visualizar a árvore de decisão para entender quais features mais influenciam (ex: total sulfur dioxide, chlorides, volatile acidity costumam ser decisivas).

## Tecnologias Utilizadas

- Python 3.8+
- scikit-learn (DecisionTreeClassifier)
- pandas, numpy, matplotlib, seaborn
- joblib (para salvar o modelo)


