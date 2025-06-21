
## **Nombre del Archivo:**

`LAB_IMG_045_Feito_VGG16_modelo_preentrenado.ipynb`

**Proyecto:** Transfer Learning con VGG16 - Clasificación de Imágenes

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

- Implementación de un modelo de clasificación de imágenes utilizando **Transfer Learning** con la arquitectura **VGG16** preentrenada.
- Carga del modelo desde `torchvision.models` con pesos previamente entrenados en ImageNet.
- Modificación de la última capa totalmente conectada para ajustarla al nuevo número de clases.
- Preparación del dataset personalizado con estructura de carpetas por clase.
- Aplicación de transformaciones de preprocesamiento: redimensionamiento, normalización y data augmentation.
- Entrenamiento y validación del modelo adaptado.
- Evaluación de desempeño sobre imágenes de prueba y visualización de resultados.

---

### Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install torch torchvision numpy matplotlib pillow
   ```
3. Prepará el dataset organizado en carpetas (`data/train/`, `data/val/`).
4. Ejecutá el notebook paso a paso en Jupyter Notebook, Deepnote o Google Colab.
5. Analizá el proceso de entrenamiento y validación sobre el nuevo conjunto de datos.

---

### Este repositorio se usa para:

**Trabajo de Laboratorio: Transfer Learning con VGG16 en Visión por Computadora**\
El objetivo es comprender el uso de redes convolucionales profundas preentrenadas, reutilizando sus capacidades de extracción de características generales para problemas personalizados de clasificación.

---

### Actividades sugeridas

- Probar el entrenamiento congelando distintas capas del modelo.
- Evaluar el impacto de modificar los hiperparámetros (learning rate, epochs, batch size).
- Experimentar con distintos tipos de data augmentation.
- Comparar el rendimiento entre el modelo totalmente congelado, parcialmente congelado y completamente entrenado.
- Discutir las ventajas del Transfer Learning en entornos con datasets reducidos.
