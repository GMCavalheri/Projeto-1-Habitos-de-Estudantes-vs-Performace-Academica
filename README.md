# Análise dos Hábitos dos Estudantes vs Performace Acadêmica

Este projeto tem como objetivo analisar e tratar os dados sobre hábitos de estudantes, utilizando dados reais, técnicas de ETL em Python, visualização e análise dos dados em Microsoft Power BI.

## Análise Realizada (Python)

A análise foi conduzida no Jupyter Notebook [`Notebook_de_testes.ipynb`](Notebook_de_testes.ipynb). Foram escolhidas e tratadas as colunas com as características que gostariamos de analisar no Power BI. O processo foi todo comentando no próprio codigo, como mostra a figura abaixo.

![Python 1](/imagens/Python1.png)


## Base de Dados

A base de dados utilizada, [`student_habits_performance.csv`](student_habits_performance.csv), foi obtido no **[kaggle](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)**. Possui 16 colunas, sendo 1 de ID único e 15 de atributos categóricos e numéricos. Não iremos trabalhar com todas, apenas as: ID, Alimentação, Horas de sono, Horas de estudo e resultado do exame final.

## Bibliotecas Utilizadas

As principais bibliotecas utilizadas, listadas em [`requirements.txt`](requirements.txt), são:

1. **[pandas](https://pandas.pydata.org/)** - Manipulação e análise de dados.

2. **[jupyter](https://jupyter.org/)** - Ambiente interativo para notebooks.

## Visualização (Power BI)

Dados tratados utilizados no Power BI.

![Power BI imagem 1](/imagens/Power1.png)

Temos abaixo análise de cada atributo e seu impacto no resultado final. Foram dividios os estudantes em 3 grupos, de acordo com a sua alimentação: Pobre, Razoável e Boa. 

![Power BI imagem 2](/imagens/Power2.png)

## Conclusões

O principal objetivo desse estudo, era mostrar qual atributo tem o mair impacto no performace acadêmica, visto que essa é uma pergunta muito recorrente entre estudantes. Podendo escolher qual hábito deve ser priorizado, chegamos nas seguintes conclusões:

1- O número de horas de estudo foi o principal fator de impacto nas notas. De todos os atributos, esse deveria ser priorizado.

2 - Alimentação é um fator mediano no impacto das notas. Ter uma qualidade de alimentação razoável, já representa uma grande melhora, em relação a qualidade pobre, porém não se observa um ganho muito expressivo, se aumentarmos a qualidade para boa.

3 - Horas de sono apresentou um impacto baixo nas notas finais, porém para estudantes com alimentação pobre, mais horas de sono tiveram um impacto mais positivo do que estudantes com alimentação boa. 


