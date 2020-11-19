# Módulo de Aprendizado de Máquina
Projeto Integrador 2 - Grupo 11 - 2020/1

# Esteira Seletora de Laranjas

## O Projeto

A esteira seletora de frutas, trata-se de um projeto desenvolvido coletivamente pela equipe 11, para a disciplina de Projeto Integrador para Engenharias 2. Estas engenharias englobam todos os cursos em vigência na Universidade de Brasília - Campus Gama (FGA), sendo estas, Engenharia de Software, Aeroespacial, de Energia, Automotiva e Eletrônica. 

O projeto foi idealizado como uma alternativa a seleção manual de frutas para agricultores de todos os portes, automatizando o processo utilizando inteligência artificial e mecanismos eletrônico-estruturais de engenharia para realizar tal feito. Afunilamos o escopo para o de laranjas, de forma a simplificar o escopo e viabilizar o projeto no prazo estipulado. Por se tratar da fruta mais consumida no mundo e principalmente, no Brasil, escolhemos a laranja como nosso aporte frutífero.

## Este repositório

Este repositório contêm o módulo de machine learning do projeto de seletor de frutas, onde, utilizamos, principalmente, o Keras para treinamento do e estruturação de nossa rede neural, que feito todo o processo, é capaz de realizar a classificação de imagens referentes a laranjas boas, boas com mancha e ruins. Este código então gera um .h5 que é resultado de todo o processo, para alimentar a API do projeto, que será unificada com os demais componentes do projeto. Este módulo encontra-se localizado no [repositório](https://github.com/Projeto-Integrador-2-Grupo-11/orange-classifier-api-upload).

## Requisitos para execução do código

É necessário ter as seguintes bibliotecas instaladas para a execução do projeto, além do Python 3.7+ :

* Pickle
* Pandas
* Numpy
* Keras
* tqdm
* OpenCV
* Tensorflow
* Matplotlib
* Pytorch (Opcional)
 
## O Dataset

O dataset utilizado foi criado utilizando imagens obtidas através de diversos meios. Inicialmente obtivemos imagens de outros projetos com vieses semelhantes ao nosso, contudo, devido a incapacidade de alimentar nosso algoritmo apenas com este, partimos para a captura de imagens por parte da equipe. Compramos frutas e tiramos as fotos, subindo-as no nosso Google Drive, estas então, sendo utilizadas no projeto.

O dataset construído possui 4.87gb de tamanho e pode ser encontrado [neste link](https://www.kaggle.com/jppgomes/dataset-laranjas).

Nota: É possível que se tenha que fazer alterações no path, dentro do código para acesso correto das imagens.