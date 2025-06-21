
## **Nombre del Archivo:**

`LAB_IMG_044_Feito_Transferencia_de_Aprendizaje.ipynb`

**Proyecto:** Introducción al Transfer Learning en Visión por Computadora

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

- Introducción conceptual y práctica al **Transfer Learning** (Transferencia de Aprendizaje) para problemas de clasificación de imágenes.
- Utilización de modelos preentrenados disponibles en `torchvision.models`.
- Preparación de un dataset de ejemplo adaptado a una nueva tarea de clasificación.
- Modificación de la capa de salida del modelo para adaptarla al nuevo número de clases.
- Congelamiento de capas para ajustar sólo la parte final del modelo (fine-tuning parcial).
- Entrenamiento y validación del modelo adaptado.
- Visualización de los resultados y discusión sobre la utilidad del enfoque transferido.

---

### Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install torch torchvision numpy matplotlib pillow
   ```
3. Prepará el dataset en las carpetas correspondientes (por ejemplo `data/train/` y `data/val/`).
4. Ejecutá el notebook paso a paso en Jupyter Notebook, Deepnote o Google Colab.
5. Analizá el entrenamiento y los resultados de clasificación obtenidos.

---

### Este repositorio se usa para:

**Trabajo de Laboratorio: Introducción al Transfer Learning en Procesamiento de Imágenes**\
El objetivo es comprender las ventajas del uso de modelos previamente entrenados sobre grandes datasets, permitiendo adaptar y entrenar modelos eficientes con pocas muestras y menos recursos computacionales.

---

### Actividades sugeridas

- Probar distintas arquitecturas preentrenadas disponibles en torchvision (VGG, DenseNet, EfficientNet).
- Comparar el entrenamiento congelando distintas cantidades de capas.
- Evaluar el impacto de utilizar datasets con pocas muestras (low data regime).
- Explorar el uso de data augmentation para mejorar la generalización.
- Discutir la aplicabilidad del Transfer Learning en contextos industriales, médicos o educativos.
