# Tópicos em Engenharia de Software
Este trabalho propõe um sistema com YOLO + EasyOCR para detecção e validação automática de placas.

## Alunos integrantes da equipe

* Bruno Pontes Duarte
* Caio Elias Araújo
* Juliana Serra Camargo Gomes
* Letícia de Assis Fraga
* Samuel Marques Sousa Leal

## Professor responsável

* Leonardo Vilela Cardoso

## Instruções de Uso

* Faça o download do notebook [Trabalho_TES.ipynb](códigos/Trabalho_TES.ipynb)
* Abra o notebook em um ambiente compatível (por exemplo, [Google Colab](https://colab.research.google.com/))
* Adicione o [dataset utilizado](https://universe.roboflow.com/trabalho-jnal6/placa-de-carro-oz0eg/dataset/3) ao projeto:
  * Acesse o dataset neste link: [Placa de Carro - Roboflow](https://universe.roboflow.com/trabalho-jnal6/placa-de-carro-oz0eg/dataset/3)
  * Faça o download do dataset no formato YOLOv11.
  * Extraia os arquivos e adicione-os à pasta do notebook.
* Atualize o caminho (`path`) para o dataset no notebook, na seção **Treinamento**, de acordo com a localização dos arquivos no seu ambiente:
  *  ```!yolo train model=yolo11n.pt data=[caminho_para_o_dataset]/data.yaml epochs=60 imgsz=640 lr0=0.0005```
* Execute todas as células
