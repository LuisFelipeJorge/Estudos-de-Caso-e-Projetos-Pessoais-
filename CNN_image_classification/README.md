# Implementação de Rede Neural para Classificação de Imagens

## Motivação
O objetivo principal deste projeto foi desenvolver uma Convolutional Neural Network (CNN) baseada na arquitetura [LeNet](https://en.wikipedia.org/wiki/LeNet), uma das precursoras na área da visão computacional, com o intuito de avaliar sua eficácia na classificação de imagens. Para realizar essa avaliação, foram utilizados dois conjuntos de dados amplamente reconhecidos na academia para propósitos didáticos e como *benchmarks* para modelos de aprendizado: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) e [SVHN (Street View House Numbers)](https://www.tensorflow.org/datasets/catalog/svhn_cropped).

Para tornar o experimento mais próximo de situações reais, simulei a presença de ruído gaussiano nas imagens durante o processo de treinamento, refletindo a diversidade de fontes e condições de captura de imagens num ambiente real, isto é, onde existem dispositivos com diferentes câmeras de captura com as mais variadas resoluções.

Ao final, examinei o impacto dessa estratégia na performance dos modelos, buscando insights valiosos para aplicações práticas de redes neurais convolucionais em ambientes variados e desafiadores.

## Desafio 
Aprender a tratar e trabalhar sobre dados de imagens, desenvolver estratégias para consumir os altos volumes de dados inerentes dos bancos de imagens e otimizar a execução do código para permitir o desenvolvimento. Aprender a utilizar de forma prática e eficiente os recursos de paralelismo de TPU disponíveis pela plataforma do Google Colab por meio da implementação de redes neurais com pacote Keras na linguagem Python. Avaliar impacto da estratégia de treinamento com ruído sobre a performance dos modelos.

## Proposta

A proposta deste estudo de caso é analisar e compreender a implementação de uma rede neural convolucional e lidar com suas especificidades. Também é do interesse desse estudo de caso avaliar a técnica de inserção de ruídos aleatórios no processo de treinamento da rede profunda. 