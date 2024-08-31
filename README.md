# Sensores-inteligentes-para-IoT
Este projeto foi desenvolvido como parte de um desafio do curso Formação IoT Specialist oferecido pela DIO (Digital Innovation One). O objetivo do desafio é criar uma aplicação que utiliza técnicas de visão computacional para detectar objetos em imagens e fornecer descrições em áudio, com o intuito de ajudar pessoas com deficiência visual a compreenderem melhor o ambiente ao seu redor.

A aplicação simula um aplicativo de detecção de objetos, que captura uma imagem, identifica os objetos presentes utilizando o modelo de Deep Learning YOLOv5 e converte a descrição desses objetos para áudio em português, utilizando a biblioteca gTTS (Google Text-to-Speech). Esta abordagem tem um grande potencial para ser integrada em dispositivos IoT, como câmeras inteligentes, ajudando pessoas com deficiência visual a se orientarem em espaços públicos e privados.
# Detecção de Objetos em Imagens e Conversão para Áudio

Este projeto utiliza o modelo YOLOv5 para detectar objetos em imagens e converte a descrição dos objetos detectados para áudio usando a biblioteca `gTTS` (Google Text-to-Speech). O projeto é implementado no Google Colab e pode ser usado para ajudar pessoas com deficiência visual a entender o que está em uma imagem.

## Demonstração

<img src="/exemplo1.png" alt="Exemplo de Detecção de Objetos" width="300"/>

> Imagem com objetos detectados e rotulados usando YOLOv5.

Você pode acessar o código completo do projeto no [notebook Jupyter disponível aqui](https://colab.research.google.com/drive/14dyFYTxi3J1gy4QApOBlzwRE58PcSqyT?usp=sharing).



## Funcionalidades

- Detecta múltiplos objetos em uma imagem utilizando o modelo YOLOv5.
- Rotula os objetos detectados diretamente na imagem.
- Converte a descrição dos objetos detectados para áudio.
- Exibe a imagem processada com rótulos no Google Colab.

## Requisitos

- Python 3.6+
- Google Colab (ou ambiente local com suporte a Jupyter Notebook)
- Bibliotecas Python: `torch`, `opencv-python`, `gtts`, `IPython`
## Conclusão

Este trabalho pode ser expandido e melhorado de várias maneiras, como adicionar suporte para múltiplos idiomas na conversão de texto para áudio, integrar com outros modelos de detecção para uma melhor acurácia, ou até mesmo desenvolver uma aplicação móvel completa que utilize essas funcionalidades. O potencial para crescimento e inovação neste campo é vasto, e este projeto é apenas um ponto de partida.

Convidamos os colaboradores e a comunidade a explorar, utilizar e aprimorar este projeto para criar soluções inclusivas e inovadoras.





