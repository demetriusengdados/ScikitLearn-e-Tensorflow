# Mini Projeto de introdução a Redes Neurais utilizando Machine Learning, Perceptron e MLP.

Utilizando dados de um pequeno dataset, **hearth_failure.csv**, desenvolvi as seguintes etapas:

__A)__ Desenvolva uma análise exploratória dos dados adequada;

__B)__ Faça a preparação dos dados para treinar os modelos;

__C)__ Teste pelo menos 3 modelos de _Machine Learning_ convencional;

__D)__ Desenvolva uma rede neural _Perceptron_ para fazer a separação entre as classes;

__E)__ Monte duas redes neurais MLP utilizando combinações de camadas diferentes;

__F)__ Qual dos modelos teve a melhor performance entre os modelos convencionais, _Perceptron_ e MLP?

Resumo da **acurácia** dos modelos utilizados:   

. **Regressão Logística: 0.83**   
. Árvore de Decisão: 0.73   
. **Random Forest: 0.83**   
. Gradient Boosting: 0.80   
. Xgbrf: 0.80   
. **Lightgbm: 0.83**   
. Perceptron: 0.50   
. Rede Neural 1: 0.68   
. Rede Neural 2: 0.68   

Os modelos com a melhor performance foram **Regressão Logística**, **Random Forest** e **Lightgbm**, todos convencionais.

A performance do Perceptron e das Redes Neurais aumenta conforme mais dados são utilizados, diferentemente dos modelos convencionais, em que a performance é estabilizada após certa quantidade de dados (e está explicado o resultado obtido).   

Modelos de Deep Learning funcionam melhor nos cenários em que há muitos dados disponíveis.
