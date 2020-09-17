# StatisticalLearning2_Parte1
Parte 1 Proyecto Final Statistical Learning 2

Este repositorio presenta la Parte No. 1 del Proyecto Final del Curso, correspondiente a el diseño de una FeedForward Neural Network.

En este notebook se trabaja sobre un dataset denominado "Parkinsons" (aprobado para el proyecto) que recopila información biomédica de voces de pacientes con esta enfermedad.

El trabajo consiste en encontrar una arquitectura de red neuronal FeedForward para un clasificador binario, que prediga con una exactitud de al menos 85% si un paciente tiene o no la enfermedad basado en la información biomédica de su voz.

La experimentación incluye: Inicialización Aleatoria, Normalización de Batch, Normalización Dropout, Experimentación con Número de Unidades y Profundidad, con la API de Keras.

El repositorio consta de:
1. Notebook "Parte1.ipynb"
2. Modelo Entrenado Final "FFN_Parkinsons.h5"
3. Dataset "parkinsons.csv"
4. Carpeta con LOGS de TensorBoard
5. Carpeta de Imágenes (utilizadas para mostrar arquitectura final y experimentación en TensorBoard dentro del notebook).
6. Carpeta de Checkpoints, donde se guarda el modelo cada ciertas iteraciones, con el objetivo de evidenciar que se guarda el progreso del entrenamiento. Se utiliza Keras Callbacks.
