\# 🐶🐱 CNN Dog vs Cat Classifier



\##  **Descripción**



Este proyecto implementa un modelo de Deep Learning basado en una Red Neuronal Convolucional (CNN) para la clasificación binaria de imágenes: perros vs gatos.



Se desarrolla un pipeline completo que incluye:



\- Preparación y organización del dataset.

\- Data augmentation.

\- Creación de un Dataset personalizado.

\- Construcción del modelo CNN.

\- Entrenamiento y evaluación.

\- Iteración y análisis de resultados.





\## **Tecnologías utilizadas**



\- Python

\- TensorFlow / Keras

\- OpenCV

\- ImgAug

\- NumPy

\- Pandas

\- Matplotlib



\## **Arquitectura del modelo**



El modelo está compuesto por:



\- Capas convolucionales (Conv2D) para extracción de características.

\- MaxPooling para reducción de dimensionalidad.

\- Capas densas para clasificación.

\- Activación ReLU en capas intermedias.

\- Activación Sigmoid en la capa final para clasificación binaria.





\##  **Resultados y limitaciones**



El modelo inicial obtuvo un rendimiento cercano al 50% de precisión, equivalente a clasificación aleatoria, por lo que  presenta dificultades para generalizar correctamente. Se observan indicios de sobreajuste tras la primera iteración.



Este proyecto se centra en el aprendizaje del pipeline completo más que en optimizar el rendimiento final.





\##  **Dataset**



El dataset utilizado no se incluye en el repositorio debido a su tamaño.





\##  **Posibles mejoras futuras**



\- Añadir matriz de confusión.

\- Probar arquitecturas más profundas.





\##  **Objetivo del proyecto**



Este proyecto forma parte de mi proceso de aprendizaje en Deep Learning. El objetivo ha sido comprender cómo funciona una CNN desde cero, implementando manualmente el pipeline de datos y el entrenamiento del modelo.

