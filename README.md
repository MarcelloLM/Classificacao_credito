# Projeto de Análise de Crédito

Este projeto consiste na análise de um conjunto de dados relacionados à concessão de crédito para determinar a probabilidade de um cliente se tornar inadimplente. Utilizamos técnicas de aprendizado de máquina para criar modelos preditivos e avaliar a eficácia desses modelos.

## Descrição dos Arquivos

- **demo01.csv**: Conjunto de dados contendo informações sobre clientes e sua situação de crédito.
- **Classificacao_de_credito_Marcello_Lassalla.ipynb**: Notebook Jupyter contendo o código Python utilizado para análise e modelagem dos dados.
- **README.md**: Este arquivo, fornecendo uma visão geral do projeto.

## Pré-processamento de Dados

Realizamos diversas etapas de pré-processamento nos dados, incluindo:

- Remoção de duplicatas.
- Conversão de variáveis categóricas em variáveis dummy.
- Divisão dos dados em conjuntos de treinamento e teste.

## Modelagem

Utilizamos dois algoritmos de classificação para construir nossos modelos:

- **Random Forest Classifier**
- **Decision Tree Classifier**

## Avaliação de Modelos

Avaliamos o desempenho dos modelos utilizando métricas como:

- Acurácia
- Matriz de Confusão
- Taxa de Falsos Positivos e Negativos

## Resultados

Os resultados indicam uma acurácia de 95.72% para o modelo final, com uma proporção de 0.34% de proponentes classificados como "maus". A matriz de confusão e outras métricas de avaliação podem ser encontradas no notebook de análise.

## Dependências

Para executar o código, são necessárias as seguintes bibliotecas Python:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Como Utilizar

1. Baixe os arquivos do repositório.
2. Execute o notebook Jupyter `Classificacao_de_credito_Marcello_Lassalla.ipynb`.
3. Analise os resultados e ajuste conforme necessário.

