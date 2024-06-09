# Implementação de Rede Neural para Classificação de Imagens

## Motivação
O objetivo principal deste projeto foi desenvolver uma Convolutional Neural Network (CNN) baseada na arquitetura [LeNet](https://en.wikipedia.org/wiki/LeNet), uma das precursoras na área da visão computacional, com o intuito de avaliar sua eficácia na classificação de imagens. Para realizar essa avaliação, foram utilizados dois conjuntos de dados amplamente reconhecidos na academia para propósitos didáticos e como *benchmarks* para modelos de aprendizado: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) e [SVHN (Street View House Numbers)](https://www.tensorflow.org/datasets/catalog/svhn_cropped).

Para tornar o experimento mais próximo de situações reais, simulei a presença de ruído gaussiano nas imagens durante o processo de treinamento, refletindo a diversidade de fontes e condições de captura de imagens num ambiente real, isto é, onde existem dispositivos com diferentes câmeras de captura com as mais variadas resoluções.

Ao final, examinei o impacto dessa estratégia na performance dos modelos, buscando insights valiosos para aplicações práticas de redes neurais convolucionais em ambientes variados e desafiadores.

## Desafio 
Aprender a tratar e trabalhar sobre dados de imagens, desenvolver estratégias para consumir os altos volumes de dados inerentes dos bancos de imagens e otimizar a execução do código para permitir o desenvolvimento. Aprender a utilizar de forma prática e eficiente os recursos de paralelismo de TPU disponíveis pela plataforma do Google Colab por meio da implementação de redes neurais com pacote Keras na linguagem Python. Avaliar impacto da estratégia de treinamento com ruído sobre a performance dos modelos.

## Proposta

A proposta deste estudo de caso é analisar e compreender a implementação de uma rede neural convolucional e lidar com suas especificidades. Também é do interesse desse estudo de caso avaliar a técnica de inserção de ruídos aleatórios no processo de treinamento da rede profunda. 


---

# Neural Network Implementation for Image Classification

## Motivation
The primary objective of this project was to develop a Convolutional Neural Network (CNN) based on the [LeNet architecture](https://en.wikipedia.org/wiki/LeNet), one of the pioneering models in the field of computer vision, to evaluate its effectiveness in image classification. For this evaluation, two widely recognized datasets were used for educational purposes and as benchmarks for learning models: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) and [SVHN (Street View House Numbers)](https://www.tensorflow.org/datasets/catalog/svhn_cropped).

To make the experiment closer to real-world situations, I simulated the presence of Gaussian noise in the images during the training process, reflecting the diversity of sources and capture conditions in a real environment, i.e., where there are devices with different cameras capturing images at various resolutions.

In the end, I examined the impact of this strategy on the models' performance, seeking valuable insights for practical applications of convolutional neural networks in varied and challenging environments.

## Challenge
To learn how to process and work with image data, develop strategies to handle the high volumes of data inherent in image datasets, and optimize code execution to facilitate development. To learn how to practically and efficiently use the parallelism resources of TPUs available on the Google Colab platform through the implementation of neural networks using the Keras package in Python. To evaluate the impact of the training strategy with noise on the models' performance.

## Proposal

The proposal of this case study is to analyze and understand the implementation of a convolutional neural network and deal with its specificities. This case study also aims to evaluate the technique of adding random noise during the training process of the deep network.