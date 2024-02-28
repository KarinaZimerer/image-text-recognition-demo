# Reconhecimento de Texto em Imagens

Este repositório contém uma demonstração de reconhecimento de texto em imagens usando técnicas de processamento de imagem e OCR (Optical Character Recognition).

## Processo

1. **Inputs e Outputs**: As imagens de entrada estão localizadas na pasta 'inputs'. Os resultados do reconhecimento de texto são armazenados na pasta 'output'.

2. **Reconhecimento de Texto**: Utilizamos um código JSON para representar o reconhecimento de texto na imagem "Karina.Zimerer.png". O código é o seguinte:

```json
[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 163,
      "height": 224,
      "left": 215,
      "top": 23
    },
    "faceLandmarks": {
      // Coordenadas dos pontos faciais
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  }
]


Salvando Resultados: Os resultados do reconhecimento de texto são armazenados no formato JSON na pasta 'output'.
Insights e Possibilidades

Aprendemos a utilizar técnicas de processamento de imagem e OCR para reconhecer texto em imagens.
Há possibilidades de expandir esse projeto para reconhecimento de texto em vídeos, documentos digitalizados e muito mais.
O uso de modelos de aprendizado de máquina pode melhorar a precisão e a velocidade do reconhecimento de texto.



<img width="1129" alt="Captura de Tela 2024-02-28 às 18 25 06" src="https://github.com/KarinaZimerer/image-text-recognition-demo/assets/104630037/ecff2299-6a24-4e04-a3d8-46e96bf57085">




