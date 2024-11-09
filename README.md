# **Face Emotion Detection**

En este repositorio, desarrollaremos una red neuronal convolucional para clasificar emociones faciales y detectar emociones en tiempo real mediante el uso de una cámara web.

## Entrenamiento en Google Colab

Realizaremos el entrenamiento en Google Colab, configurando un entorno con las siguientes versiones de librerías:

- TensorFlow 
- Keras 

Puedes encontrar el código para ejecutar el entrenamiento en Colab en el siguiente enlace:

[FaceEmotion.ipynb](https://github.com/Josefo22/Detector-Emociones/blob/main/Face%20emotion.ipynb)

## Dataset

Usaremos el siguiente dataset de Kaggle para el entrenamiento:

[Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)

### Preparación del Entorno

Para configurar el entorno, sigue estos pasos:

```bash
$ conda create -n FaceEmotion python=3.7
$ conda activate FaceEmotion
$ pip install tensorflow==2.4.1
$ pip install keras==2.4.3
$ pip install imutils opencv-python h5py
$ pip install matplotlib==3.2.2
