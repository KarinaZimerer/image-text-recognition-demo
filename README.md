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







