
## **Nombre del Archivo:**

`LAB_IMG_031_Feito_CNNs_Full.ipynb`

**Proyecto:** Redes Neuronales Convolucionales (CNN) - Clasificación de Imágenes

**Fecha:** 21/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV (cv2)
- sklearn
- os

---

### Se trata de:

**Contenido del Notebook**

- Implementación de un modelo completo de **Red Neuronal Convolucional (CNN)** aplicado a clasificación de imágenes.
- Preparación de dataset con dos clases: perros y gatos.
- Carga y preprocesamiento de las imágenes: redimensionamiento, normalización de pixeles y separación en conjuntos de entrenamiento y prueba.
- Definición de la arquitectura de la red:
  - Capas convolucionales, de pooling y fully connected.
  - Funciones de activación ReLU y Softmax.
  - Compilación del modelo con optimizador Adam y función de pérdida categórica.
- Entrenamiento del modelo con validación.
- Evaluación del rendimiento: métricas de precisión, pérdida y visualización de las curvas de aprendizaje.
- Ejemplo de predicción sobre nuevas imágenes.

---

### Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install tensorflow opencv-python numpy matplotlib scikit-learn
   ```
3. Asegurate de disponer del dataset con las carpetas correspondientes (por ejemplo `dataset/Perros/` y `dataset/Gatos/`).
4. Ejecutá el notebook paso a paso desde Jupyter Notebook, Deepnote o Google Colab.
5. Observá el entrenamiento, validación y prueba de la red neuronal.

---

### Este repositorio se usa para:

**Trabajo de Laboratorio: Redes Neuronales Convolucionales (CNN)**\
El objetivo es comprender el flujo completo de desarrollo de un modelo convolucional simple para clasificación binaria de imágenes, permitiendo visualizar el impacto de las distintas etapas de preprocesamiento y arquitectura de red sobre los resultados.

---

### Actividades sugeridas

- Modificar el número de capas o neuronas de la CNN para evaluar su impacto en el rendimiento.
- Incorporar nuevas clases o datasets para ampliar el problema de clasificación.
- Ajustar hiperparámetros como tasa de aprendizaje, épocas o tamaño de batch.
- Probar distintas funciones de activación o funciones de pérdida.
- Implementar técnicas de aumento de datos (data augmentation) para mejorar la generalización.
