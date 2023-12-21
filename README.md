# Tecnologias Utilizadas
## OpenCV
O OpenCV (Open Source Computer Vision Library) é uma biblioteca de código aberto voltada para visão computacional. Neste projeto, o OpenCV é empregado para detecção de faces em imagens, utilizando um modelo pré-treinado.

## imutils
A biblioteca imutils é utilizada para facilitar operações comuns em imagens, como redimensionamento e rotação. No contexto deste projeto, é empregada para redimensionar a imagem capturada pela webcam.

## JavaScript no Colab
O Google Colab permite a integração de código JavaScript para interações específicas, como captura de imagem da webcam. Essa funcionalidade é explorada para criar uma interface de captura de fotos.

# Funcionamento
## 1.Captura de Imagem pela Webcam: 
A função take_photo utiliza código JavaScript para acessar a webcam e capturar uma imagem.

## 2.Detecção de Faces: 
O OpenCV carrega um modelo de detecção facial pré-treinado e o utiliza para detectar rostos na imagem capturada. O modelo é baseado na arquitetura SSD (Single Shot Detector) com uma rede base ResNet.

## 3.Exibição dos Resultados: 
As faces detectadas são destacadas na imagem, indicando a região correspondente. A probabilidade de detecção é exibida junto à caixa delimitadora.

# Conclusão
Este projeto oferece uma implementação simples de detecção de faces humanas, demonstrando a aplicação de tecnologias como OpenCV e imutils para análise de imagens em tempo real. A integração com JavaScript no ambiente Colab possibilita interações amigáveis, como a captura de imagens pela webcam.

<h2> Como o projeto se comporta quando finalizado:</h2>

![ml deteccao facial](https://user-images.githubusercontent.com/109180231/208197510-642063a7-2800-4f12-ad85-38ed854fbb6f.png)
