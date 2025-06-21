
## **Nombre del Archivo:**

`LAB_IMG_043_Feito_ResNet18.ipynb`

**Proyecto:** Clasificación de Imágenes con Transfer Learning - ResNet18

**Fecha:** 21/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas

- Python 3.x
- PyTorch (torch, torchvision)
- NumPy
- Matplotlib
- PIL (Pillow)

---

### Se trata de:

**Contenido del Notebook**

- Implementación de un modelo de clasificación de imágenes utilizando **Transfer Learning** con la arquitectura **ResNet18** preentrenada.
- Preparación del dataset de imágenes personalizado.
- Aplicación de transformaciones de preprocesamiento: redimensionamiento, normalización y data augmentation.
- Carga del modelo ResNet18 desde `torchvision.models` y modificación de su última capa para adaptarla al número de clases del problema.
- Entrenamiento del modelo sobre el nuevo dataset.
- Evaluación del rendimiento del modelo sobre datos de validación y prueba.
- Visualización de resultados de predicción sobre nuevas imágenes.

---

### Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install torch torchvision numpy matplotlib pillow
   ```
3. Prepará el dataset en las carpetas correspondientes (por ejemplo `dataset/train/` y `dataset/test/`).
4. Ejecutá el notebook paso a paso en Jupyter Notebook, Deepnote o Google Colab.
5. Observá el entrenamiento y evaluación del modelo transferido.

---

### Este repositorio se usa para:

**Trabajo de Laboratorio: Transfer Learning aplicado a Clasificación de Imágenes**\
El objetivo es explorar el uso de modelos preentrenados como base para resolver problemas personalizados de clasificación, comprendiendo los beneficios de reutilizar arquitecturas previamente entrenadas y optimizar su adaptación a nuevos conjuntos de datos.

---

### Actividades sugeridas

- Probar distintas arquitecturas disponibles en `torchvision.models` (por ejemplo, ResNet34, ResNet50).
- Modificar los hiperparámetros de entrenamiento (learning rate, batch size, epochs).
- Incorporar más clases en el dataset y observar el impacto en el rendimiento.
- Aplicar distintas técnicas de data augmentation para mejorar la generalización.
- Analizar los resultados visualizando las predicciones correctas y los errores del modelo.
