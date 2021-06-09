# cu_turismo_inteligente

Este repositorio contiene códigos de ejemplos para la realización de Caso de Uso de Turismo Inteligente.

Cada uno de estos ejemplos se encuentra en un Jupyter Notebook.

Ademas de los Jupyter Notebook, se encuentra las siguientes carpetas:

- `recursos_yolo`. Carpeta con los ficheros de configuracion de YOLO. Debido al tamaño del fichero es necesario realizar la descarga de pesos de yolov3, que se puede realizar desde el siguiente link https://pjreddie.com/media/files/yolov3.weights
- `entradas`. Carpeta donde se leen las imagenes de entrada
- `salidas`. Carpeta donde se almacenan las imagenes de salida

## Biliotecas necesarias

Para las ejecuciónes de estos ejemplos es necesario tener instaladas las bibliotecas que se listan a continuación.

### Tensor Flow

Para la intalación de esta biblioteca abrir la consola de anacodna y ejecutar el siguiente comando:

`conda install tensorflow`

### Keras
Para la instalación de esta biblioteca abrir la consola de anaconda y ejecutar el siguiente comando:

`conda install keras`

### Open CV

Biblioteca para el procesamiento de imágenes. Para la intalación de esta biblioteca abrir la consola de anacodna y ejecutar el siguiente comando:

`conda install -c menpo opencv`

### Gensim

Biblioteca para el trabajo con Doc2Vec. Para la intalación ejecutar el comando:

`conda install gensim` 

## Ejemplos

### 1. Detección de elementos

En este notebook se implementa un ejemplo de detección de objetos haciendo uso de YoloV3.

## 2. Extracción de *features* imágenes

En este noteook se implementa un ejemplo de extraccion de **features** de alto nivel de una imagen mediante el uso de CNN, usando las implementaciones disponibles en keras.

## 3. Recomendador basado en contenidos

En este ejemplo se implementa un recomendador basado en contenidos generado a partir de los comentarios de los recursos turisticos.

## 4. Doc2Vec

En este ejemplo se muesrta como obtener features de alto nivel para datos textuales.