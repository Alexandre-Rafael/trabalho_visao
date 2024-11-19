# Classificação de Imagens no Conjunto de Dados MPEG7 Modificado

Este projeto implementa um pipeline para classificação de imagens do conjunto de dados MPEG7 modificado, utilizando os classificadores *k-NN* e *Random Forest*. O trabalho foi desenvolvido no contexto da disciplina de Introdução à Visão Computacional da Universidade Federal de Viçosa.

## Estrutura do Projeto
- **classificando_imagens.py**: Script principal com todo o pipeline, incluindo a extração de características, normalização dos dados, e treinamento/teste dos classificadores.
- **morphological_features.csv**: Arquivo gerado contendo as características extraídas.
- **confusion_matrix_knn.png**: Matriz de confusão para o classificador k-NN.
- **confusion_matrix_rf.png**: Matriz de confusão para o classificador Random Forest.
- **relatorio.pdf**: Relatório detalhado do projeto (se disponível).

## Pré-requisitos
Para executar este projeto, é necessário ter as seguintes bibliotecas instaladas:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- opencv-python
- torch (opcional, dependendo da versão do script)

Você pode instalar todas as dependências usando:
```bash
pip install -r requirements.txt
