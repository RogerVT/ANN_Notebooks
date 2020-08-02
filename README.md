# ANN_Notebooks

Implementación de una red neuronal artificial para clasificar números segmentados (usando KMeans). La NN fue entrenada usando el dataset MNIST. Más detalles serán incluidos (y quizás un tutorial) serán incluidos en este README. 

##Uso

`pip install -r requirements.txt`

Las libretas se encuentran divididas en dos partes: 
  * La implementación de KMeans para segmentar los inputs (véase la carpeta test_data) y las predicciones realizadas por el modelo (proyecto_mnist.h5).
  * El código que generó el modelo usado
  
Se recomienda correr primero la libreta **clasificador_mnist2** para generar y almacenar el modelo y después correr las pruebas con **segmentacion_pruebas**.
