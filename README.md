# Sensores-inteligentes-para-IoT
Este projeto foi desenvolvido como parte de um desafio do curso Formação IoT Specialist oferecido pela DIO (Digital Innovation One). O objetivo do desafio é criar uma aplicação que utiliza técnicas de visão computacional para detectar objetos em imagens e fornecer descrições em áudio, com o intuito de ajudar pessoas com deficiência visual a compreenderem melhor o ambiente ao seu redor.

A aplicação simula um aplicativo de detecção de objetos, que captura uma imagem, identifica os objetos presentes utilizando o modelo de Deep Learning YOLOv5 e converte a descrição desses objetos para áudio em português, utilizando a biblioteca gTTS (Google Text-to-Speech). Esta abordagem tem um grande potencial para ser integrada em dispositivos IoT, como câmeras inteligentes, ajudando pessoas com deficiência visual a se orientarem em espaços públicos e privados.
# Detecção de Objetos em Imagens e Conversão para Áudio

Este projeto utiliza o modelo YOLOv5 para detectar objetos em imagens e converte a descrição dos objetos detectados para áudio usando a biblioteca `gTTS` (Google Text-to-Speech). O projeto é implementado no Google Colab e pode ser usado para ajudar pessoas com deficiência visual a entender o que está em uma imagem.

## Demonstração

<img src="/exemplo1.png" alt="Exemplo de Detecção de Objetos" width="500"/>

> Imagem com objetos detectados e rotulados usando YOLOv5.
[Clique aqui para ouvir o áudio de exemplo](caminho/para/seu/audio.mp3)

> Ouça a descrição dos objetos detectados na imagem.

## Funcionalidades

- Detecta múltiplos objetos em uma imagem utilizando o modelo YOLOv5.
- Rotula os objetos detectados diretamente na imagem.
- Converte a descrição dos objetos detectados para áudio em português.
- Exibe a imagem processada com rótulos no Google Colab.

## Requisitos

- Python 3.6+
- Google Colab (ou ambiente local com suporte a Jupyter Notebook)
- Bibliotecas Python: `torch`, `opencv-python`, `gtts`, `IPython`


