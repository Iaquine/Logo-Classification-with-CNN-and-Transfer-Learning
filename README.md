# Classificação de Logos com CNN e Transfer Learning

Este projeto implementa um modelo de classificação de imagens para logos de restaurantes, utilizando Redes Neurais Convolucionais (CNN) e Transfer Learning. O objetivo é classificar imagens de fachadas de restaurantes em uma das seguintes classes:

* Burger King
* KFC
* McDonalds
* Other
* Starbucks
* Subway

## Dados

O dataset utilizado foi obtido do Kaggle: [Logos Dataset](https://www.kaggle.com/datasets/kmkarakaya/logos-bk-kfc-mcdonald-starbucks-subway-none).

## Implementação

**Passo 1:** Clonar o repositório do projeto.

**Passo 2:** Instalar as bibliotecas necessárias (TensorFlow, Keras, Matplotlib, Pandas, Scikit-learn).

**Passo 3:** Carregar o dataset do Kaggle e realizar uma análise exploratória básica.

**Passo 4:** Implementar um modelo CNN do zero.

**Passo 5:** Implementar um modelo com Transfer Learning utilizando a arquitetura ResNet50 pré-treinada.

**Passo 6:** Comparar o desempenho dos dois modelos.

## Execução

O código foi desenvolvido para ser executado no Google Colab. 

**Configurações:**

* Certifique-se de ter uma conta Kaggle e uma API key.
* Crie um arquivo `kaggle.json` com sua API key e faça o upload para o Colab.
* Ajuste o nome do repositório e usuário do GitHub no código.

**Observações:**

* O código inclui data augmentation para melhorar a generalização do modelo.
* A análise exploratória básica foi realizada para visualizar a distribuição das classes e algumas imagens do dataset.
* O modelo com Transfer Learning utiliza a arquitetura ResNet50 pré-treinada no ImageNet.
* A comparação de desempenho é feita com base na acurácia dos modelos no conjunto de validação.
