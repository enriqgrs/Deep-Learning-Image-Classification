# Deep-Learning-Image-Classification

Implementación y evaluación de modelos de aprendizaje profundo para la clasificación automatizada de imágenes. El proyecto aborda el diseño de arquitecturas de redes neuronales, desde perceptrones multicapa (MLP) hasta redes neuronales convolucionales (CNN), utilizando los datasets MNIST y CIFAR-10.

### Contribuciones y Evolución:

El desarrollo se centró en la exploración de arquitecturas de aprendizaje profundo y la optimización de sus capacidades de generalización:

- **Diseño de Arquitecturas**: Implementación de modelos basados en Perceptrón Multicapa para dígitos (MNIST) y Redes Neuronales Convolucionales para objetos (CIFAR-10) mediante Keras y TensorFlow.
- **Ingeniería de Redes Convolucionales**: Configuración de capas de convolución, pooling y normalización para la extracción jerárquica de características en imágenes en color.
- **Optimización y Regularización**: Aplicación de técnicas para prevenir el sobreentrenamiento (overfitting), incluyendo el ajuste de funciones de activación, optimizadores y la gestión de hiperparámetros de entrenamiento.
- **Análisis de Predicciones**: Implementación de mecanismos de visualización para inspeccionar las predicciones del modelo y realizar un diagnóstico detallado de las clasificaciones erróneas.

### Donde se analiza:

- **Comparativa de Arquitecturas**: Evaluación del rendimiento entre redes densas tradicionales y redes convolucionales, demostrando la superioridad de las CNN en la detección de patrones espaciales complejos.
- **Diagnóstico de Errores en CIFAR-10**: Análisis de la matriz de confusión donde se identifican sesgos del modelo en clases con alta similitud visual, como la confusión recurrente entre las etiquetas 'gato' y 'perro'.
- **Impacto de la Complejidad de los Datos**: Estudio de cómo la transición de imágenes en escala de grises a imágenes en color con fondos complejos afecta a la capacidad de convergencia y precisión del modelo.

### Uso de tecnologías:

Python, TensorFlow/Keras, Numpy y Matplotlib para la visualización de resultados y análisis de errores.
