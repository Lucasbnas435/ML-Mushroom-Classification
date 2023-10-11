# Mushroom Classification - Machine Learning
### [Autor: Lucas Barbosa Nascimento](https://github.com/Lucasbnas435)

O modelo de Machine Learning realiza classificação binária (binary classification), prevendo se determinada amostra de cogumelo é venenosa (1) ou comestível (0).

## Dataset
Cada linha desse conjunto de dados representa uma amostra hipotética de um cogumelo pertencente aos gêneros _Agaricus_ ou _Lepiota_, contemplando, no total, 23 espécies. Assim, são apresentadas variáveis categóricas e uma avaliação quanto à venenosidade de cada porção registrada.

Colunas e valores possíveis:

-    Cap-shape: bell=b, conical=c, convex=x, flat=f, knobbed=k, sunken=s
-    Cap-surface: fibrous=f, grooves=g, scaly=y, smooth=s
-    Cap-color: brown=n, buff=b, cinnamon=c, gray=g, green=r, pink=p, purple=u, red=e, white=w, yellow=y
-    Bruises: bruises=t, no=f
-    Odor: almond=a, anise=l, creosote=c, fishy=y, foul=f, musty=m, none=n, pungent=p, spicy=s
-    Gill-attachment: attached=a, descending=d, free=f, notched=n
-    Gill-spacing: close=c, crowded=w, distant=d
-    Gill-size: broad=b, narrow=n
-    Gill-color: black=k, brown=n, buff=b, chocolate=h, gray=g, green=r, orange=o, pink=p, purple=u, red=e, white=w, yellow=y
-    Stalk-shape: enlarging=e, tapering=t
-    Stalk-root: bulbous=b, club=c, cup=u, equal=e, rhizomorphs=z, rooted=r, missing=?
-    Stalk-surface-above-ring: fibrous=f, scaly=y, silky=k, smooth=s
-    Stalk-surface-below-ring: fibrous=f, scaly=y, silky=k, smooth=s
-    Stalk-color-above-ring: brown=n, buff=b, cinnamon=c, gray=g, orange=o, pink=p, red=e, white=w, yellow=y
-    Stalk-color-below-ring: brown=n, buff=b, cinnamon=c, gray=g, orange=o, pink=p, red=e, white=w, yellow=y
-    Veil-type: partial=p, universal=u
-    Veil-color: brown=n, orange=o, white=w, yellow=y
-    Ring-number: none=n, one=o, two=t
-    Ring-type: cobwebby=c, evanescent=e, flaring=f, arge=l, none=n, pendant=p, sheathing=s, zone=z
-    Spore-print-color: black=k, brown=n, buff=b, chocolate=h, green=r, orange=o, purple=u, white=w, yellow=y
-    Population: abundant=a, clustered=c, numerous=n, scattered=s, several=v, solitary=y
-    Habitat: grasses=g, leaves=l, meadows=m, paths=p, urban=u, waste=w, woods=d

## Desenvolvimento do Projeto
A aplicação foi desenvolvida em Python 3.10, utilizando [Jupyter Notebooks](https://jupyter.org/) hospedados e executados na plataforma [Google Colaboratory](https://colab.research.google.com/). Além disso, foram usadas as bibliotecas [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Plotly](https://plotly.com/python/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), [Scikit-learn](https://scikit-learn.org/stable/), [XGBoost](https://xgboost.readthedocs.io/en/stable/) e [Joblib](https://joblib.readthedocs.io/en/stable/).

No notebook data-visualization.ipynb, encontra-se um trabalho de visualização dos dados, expondo informações e gráficos diversos, referências fundamentais para a realização da Análise Exploratória inicial.

No início do notebook model-training.ipynb, tem-se o tratamento dos dados, além da divisão do dataset entre parte de treinamento e parte de testes. Logo depois, é efetuado o treinamento dos modelos com os algoritmos XGBoost, RandomForest e Decision Tree. Por fim, os modelos gerados são exportados, permitindo seu compartilhamento e uso em outros locais.

## Resultados
Todos os três modelos apresentam uma acurácia de **100%**. Essa métrica, a matriz de confusão e o classification report são exibidos nesta imagem:

![](https://github.com/Lucasbnas435/ML-Mushroom-Classification/blob/master/src/docs/results.png?raw=true)

## Estrutura de Pastas
```
.
├── README.md
└── src
    ├── dataset
    │   └── mushrooms.csv
    ├── docs
    │   └── results.png
    ├── models
    │   ├── DecisionTreeModel.joblib
    │   ├── RandomForestModel.joblib
    │   └── XGBoostModel.json
    └── notebooks
        ├── data-visualization.ipynb
        └── model-training.ipynb
```

## Fonte dos Dados
https://www.kaggle.com/datasets/uciml/mushroom-classification

## Contato
Muito obrigado por acessar esse projeto!

Vamos nos conectar?

- GitHub: https://github.com/Lucasbnas435
- LinkedIn: https://linkedin.com/in/lucasbnas
- E-mail: lucasbnas435@gmail.com
