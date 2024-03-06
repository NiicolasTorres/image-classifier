MNIST Handwritten Digits Recognition
This project uses TensorFlow and TensorFlow Datasets to train a neural network model capable of recognizing handwritten digits in the MNIST dataset.

Project Contents:

1. Dataset Loading:
   - TensorFlow Datasets is used to load the MNIST dataset, splitting it into training and testing sets.

2. Data Preprocessing:
   - Normalization of images and labels within the range [0, 1].

3. Data Visualization:
   - Displays an image from the training set to verify data loading and preprocessing.

4. Model Definition:
   - A sequential neural network model is created with Flatten and Dense layers for digit classification.

5. Model Compilation and Training:
   - The model is compiled using the appropriate loss function and optimizer, and then trained with the training dataset.

6. Model Evaluation:
   - The model is evaluated on the test dataset, showing test images alongside predictions and actual labels.

Requirements and Execution:
- Requires TensorFlow and TensorFlow Datasets.
- Execute the script in a Python environment.




-----------------------------Español-----------------------------



MNIST Handwritten Digits Recognition
Este proyecto utiliza TensorFlow y TensorFlow Datasets para entrenar un modelo de red neuronal que puede reconocer dígitos escritos a mano en el conjunto de datos MNIST.


Contenido del Proyecto:

1. Carga del Conjunto de Datos:
- Se utiliza TensorFlow Datasets para cargar el conjunto de datos MNIST, dividiéndolo en conjuntos de entrenamiento y prueba.
  
2.  Preprocesamiento de Datos:
- Normalización de imágenes y etiquetas en el rango [0, 1].

2. Visualización de Datos:
- Muestra una imagen del conjunto de entrenamiento para verificar la carga y preprocesamiento de datos.

3. Definición del Modelo:
- Se crea un modelo de red neuronal secuencial con capas Flatten y Dense para la clasificación de dígitos.

4. Compilación y Entrenamiento del Modelo:
- Se compila el modelo utilizando la función de pérdida y el optimizador adecuado, y luego se entrena con el conjunto de datos de entrenamiento.

5. Evaluación del Modelo:
- Se evalúa el modelo en el conjunto de datos de prueba, mostrando imágenes de prueba junto con predicciones y etiquetas reales.

Requisitos y Ejecución
- Requiere TensorFlow y TensorFlow Datasets.
- Ejecutar el script en un entorno de Python.
