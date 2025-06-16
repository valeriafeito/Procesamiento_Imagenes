
**Nombre del Archivo:**  
`LAB_IMG_029_Feito_Integrador_CNN_básica_con_Keras_y_TensorFlow.ipynb`

---

**Proyecto:**  
Clasificación de imágenes con una CNN básica – Actividad Integradora Final

**Fecha:** 16/06/2025  
**Autor:** Valeria Feito

---

### Tecnologías utilizadas:
- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

### Se trata de:  
**Contenido del Notebook**
- Desarrollo de una red neuronal convolucional (CNN) básica para clasificación de imágenes.
- Uso del dataset `fashion_mnist`, incluido en Keras.
- Visualización de las imágenes y etiquetas originales del dataset.
- Preprocesamiento: normalización de los datos de entrada.
- Construcción de la arquitectura del modelo CNN con capas `Conv2D`, `MaxPooling2D`, `Flatten` y `Dense`.
- Compilación y entrenamiento del modelo.
- Evaluación sobre el conjunto de prueba.
- Visualización de métricas de desempeño y predicciones sobre nuevas imágenes.
- Inclusión de ejemplos individuales y visualización de errores del modelo.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 y las siguientes librerías instaladas:
   ```bash
   pip install tensorflow matplotlib numpy
   ```
2. Abrí el notebook en Jupyter Notebook, Deepnote o Google Colab.
3. Ejecutá las celdas secuencialmente para construir, entrenar y evaluar el modelo.
4. Modificá hiperparámetros o probá con otras imágenes para seguir experimentando.

---

### Este repositorio se usa para:  
**Actividad Integradora Final del Módulo de Visión por Computadora**  
Busca consolidar los conocimientos adquiridos sobre redes convolucionales, preprocesamiento y evaluación de modelos aplicados a clasificación de imágenes.

---

### Actividades sugeridas:
- Modificar la arquitectura de la red (agregar capas, cambiar tamaños de filtros).
- Evaluar otros datasets (por ejemplo, CIFAR-10 o MNIST clásico).
- Aplicar técnicas de regularización como Dropout o Data Augmentation.
- Comparar los resultados con redes densas (sin convoluciones).
- Implementar un sistema de predicción en tiempo real para imágenes cargadas por el usuario.
