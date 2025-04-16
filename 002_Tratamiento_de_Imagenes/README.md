**Nombre del Archivo:** LAB_IMG_002_Feito_Tratamiento de Img.ipynb

**Proyecto:** Tratamiento Básico de Imágenes

**Fecha:** 01/04/2024

**Autor:** Valeria Feito


---

### Tecnologías utilizadas:
- Python 3.x
- OpenCV (cv2)
- scikit-image
- matplotlib
- NumPy
- watermark (para info de entorno)


---

### Se trata de:
**Contenido del Notebook**
- Instalación de librerías necesarias para el procesamiento.
- Lectura de imágenes desde URL.
- Visualización inicial con matplotlib.
- Función auxiliar data_img() para mostrar tamaño, valores máximos y mínimos.
- Experimentos de muestreo con diferentes factores (factor_muestreo = 2, 4, 8).
- Experimentos de cuantización (reducción de niveles de color).
- Visualización de efectos combinados: muestreo + cuantización.
- Análisis del impacto en la calidad visual y en el tamaño de los datos.


---

### Instrucciones de uso
1. Asegurate de tener Python instalado.
2. Instala las dependencias:
pip install opencv-python scikit-image matplotlib watermark
3. Ejecutá el notebook desde Jupyter, Deepnote o Google Colab.
4. Modificá los valores de factor_muestreo y factor_cuantizacion para observar los efectos.


---

### Este repositorio se usa para
**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**
- Este notebook tiene como objetivo explorar los conceptos básicos del tratamiento digital de imágenes, incluyendo lectura, visualización, muestreo, cuantización y análisis de efectos sobre la calidad visual.


---

### Actividades sugeridas
- Cambiar la imagen de entrada por otras.
- Comparar visualmente las imágenes procesadas.
- Analizar el histograma antes y después de la cuantización.
- Evaluar la compresión alcanzada con cada transformación.
