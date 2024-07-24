# Ensemble-Learning
Neste repositório temos uma pequena amostra da técnica de ensemble learning. Nos Métodos Ensemble, encontramos uma das etapas mais interessantes do aprendizado de machine learning. Estes métodos constroem vários modelos de machine learning, utilizando o resultado de cada modelo na definição de um único resultado, obtendo-se assim um valor final único.
Isso significa que a resposta agregada de todos esses modelos é que será dada como o resultado final para cada dado que se está testando. Aqui estamos falando de algoritmos mais robustos e complexos, que envolvem mais operações, com um custo computacional um pouco maior, mas que, geralmente, têm uma performance melhor!
Os métodos mais usados são:
- RandomForest
- ExtraTrees
- AdaBoost
- GradientBoosting
- Bagging

Neste exemplo usaremos o GradientBoosting, que consiste em treinar novos modelos diretamente no erro dos modelos anteriores. Ou seja, os novos modelos tentam prever o erro dos modelos anteriores em vez de prever independentemente o target. Dessa forma, obtemos a predição final somando a predição de todos os weak learners.

A base que usamos é muito utilizada de exemplo para aulas e estudos da aréa, você pode encontra-la nesse site [https://archive.ics.uci.edu/dataset/73/mushroom] ou usar o comando **!pip install ucimlrepo** no google colab ou no notebook que estiver utilizando.
