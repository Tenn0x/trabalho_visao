#### Trabalho Final de Visão Computacional
## Detecção de objetos utilizando a base de dados ExDark (Exclusively-Dark-Image-Dataset)
O objetivo deste projeto foi explorar a detecção de objetos utilizando machine learning, utilizando o dataset a seguir:
### Dataset
### Exclusively-Dark-Image-Dataset (ExDark)
O dataset escolhido possui imagens em diferentes tons de escuridão, com 12 classes diferentes e cerca de 600 imagens para cada uma.
Suas anotações contém a sua classe, coordenadas iniciais, a largura e a altura de suas caixas correspondentes.

https://github.com/cs-chan/Exclusively-Dark-Image-Dataset

https://paperswithcode.com/dataset/exdark

<img src="/images/exdarkimg.gif">

<img src="/images/annotations.png">

## Implementação do YoloV3 usando Google Colab

Foi utilizado uma implementação base do YoloV3 da darknet no Google Colab, feita pelo https://www.youtube.com/@ArtificiallyIntelligents, e-mail: sajidurrehman1@gmail.com.

Esta implementação era originalmente para detecção de armas (apenas uma classe).

Assim, modifiquei a implementação para ser treinada e testada com o dataset ExDark.

## Teste com vídeos capturados localmente

<img src="/images/gif1_teste.gif">

<img src="/images/gif2_teste.gif">

<img src="/images/gif3_teste.gif">
