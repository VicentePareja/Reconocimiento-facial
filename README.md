# Reconocimiento de Vengadores con Machine Learning

Este proyecto utiliza técnicas de Machine Learning para reconocer a los Vengadores a partir de imágenes. Se utilizan varias técnicas de procesamiento de imágenes y modelos de aprendizaje automático para lograr este objetivo.

## Contenido

1. **Extracción de características de las imágenes**: Se utilizan los 'landmarks' faciales extraídos de las imágenes de los Vengadores para crear un conjunto de características. Estos 'landmarks' son puntos clave en la cara que pueden ser utilizados para describir la forma y las características de la cara.

2. **Creación de nuevas características**: Se crean nuevas características a partir de los 'landmarks' faciales, como el ángulo de los ojos y el área de la boca. Estas características adicionales pueden ayudar a mejorar el rendimiento de los modelos de Machine Learning.

3. **Modelos de Machine Learning**: Se entrenan varios modelos de Machine Learning, incluyendo Decision Trees, Random Forests, Gradient Boosting, K-Nearest Neighbors (KNN) y Support Vector Machines (SVM). Se utilizan técnicas de validación cruzada y búsqueda de cuadrícula para encontrar los mejores hiperparámetros para cada modelo.

4. **Evaluación de los modelos**: Se evalúa el rendimiento de cada modelo utilizando la precisión como métrica. Además, se utiliza la biblioteca LIME para proporcionar explicaciones interpretables de las predicciones de los modelos.

## Resultados

Los resultados muestran que los modelos de Random Forest y Gradient Boosting tienen el mejor rendimiento, con una precisión de alrededor del 70%. Las características más importantes para estos modelos incluyen la distancia entre los ojos, el ancho de la boca y el ángulo de los ojos.

## Futuras mejoras

Para futuras mejoras, se podrían explorar otras técnicas de procesamiento de imágenes y extracción de características, como el uso de redes neuronales convolucionales (CNN) para la extracción de características. Además, se podrían probar otros modelos de Machine Learning y técnicas de optimización de hiperparámetros.

