# Clasificador de Imágenes con CNN - CIFAR-10

## Descripción

Proyecto desarrollado en Python utilizando TensorFlow y Keras para la clasificación automática de imágenes mediante una Red Neuronal Convolucional (CNN).

El modelo fue entrenado utilizando el conjunto de datos CIFAR-10, compuesto por 60.000 imágenes a color de 32x32 píxeles distribuidas en 10 categorías diferentes.

## Categorías

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Tecnologías utilizadas

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pandas
* Google Colab

## Funcionalidades

* Carga automática del dataset CIFAR-10.
* Normalización de imágenes.
* Visualización de muestras del conjunto de entrenamiento.
* Entrenamiento de una Red Neuronal Convolucional (CNN).
* Evaluación mediante métricas Accuracy y Loss.
* Predicción sobre imágenes externas cargadas por el usuario.
* Visualización de probabilidades por clase.
* Comparación entre predicción y etiqueta real.

## Arquitectura del modelo

* Conv2D (32 filtros, kernel 3x3, ReLU)
* MaxPooling2D (2x2)
* Conv2D (32 filtros, kernel 3x3, ReLU)
* MaxPooling2D (2x2)
* Flatten
* Dense (64 neuronas, ReLU)
* Dense (10 neuronas de salida)

## Resultados

El modelo fue entrenado utilizando el conjunto CIFAR-10 y evaluado sobre datos de verificación obteniendo métricas de Accuracy y Loss para medir el rendimiento de la red neuronal.

## Ejecución

1. Clonar el repositorio:

```bash
git clone https://github.com/usuario/cifar10-image-classifier-cnn.git
```

2. Instalar dependencias:

```bash
pip install tensorflow numpy matplotlib pandas pillow
```

3. Ejecutar el notebook:

```bash
jupyter notebook
```

o abrir directamente en Google Colab.

## Autor

Proyecto académico desarrollado como práctica de Redes Neuronales e Inteligencia Artificial.

