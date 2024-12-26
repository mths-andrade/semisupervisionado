# Aprendizado semi-supervisionado

Projeto de classificação de machine learning com aprendizado semi-supervisionado, mais especificamente, de classificação da qualidade de amostras de leite de uma indústria de laticínios. A principal ferramenta que utilizei foi a Scikit-Learn.

Trabalhei num motebook do Google Colab e, além do Scikit-Learn, usei também a biblioteca Pandas, para o tratamento inicial dos dados.

Tabela dos dados: [Qualidade do leite](https://github.com/mths-andrade/semisupervisionado/blob/0fa89c88762ef2ab7c2e1417b0a68c6ca40635ec/qualidade_leite.csv)

O conjunto de dados utilizado contém diversas características a respeito de amostras de leite, no intuito de serem utilizadas para classificar a qualidade do leite entre três categorias:

Qualidade baixa (Ruim)

Qualidade média (Moderada)

Qualidade alta (Boa)

A tabela é composta por 7 variáveis independentes: pH, temperatura, sabor, odor, gordura, turbidez e cor. Essas informações estão em formato numérico e desempenham um papel fundamental na análise preditiva do leite.

Se sabor, odor, gordura e turbidez estiverem em ótimas condições, serão designados como 1. Caso contrário, serão designados como 0. Já a temperatura e o pH estão apresentados com seus valores reais, sendo a temperatura em graus Celsius e o pH entre os valores de 0 a 14, determinando a acidez ou basicidade do leite.
