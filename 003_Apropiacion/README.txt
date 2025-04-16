**Nombre del Archivo:** LAB_IMG_008_Feito_Apropiación_Muestreo_Cuantización.ipynb

**Proyecto:** Apropiación de Trabajo sobre Muestreo y Cuantización de Imágenes

**Fecha:** 08/04/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas:
- Python 3.x
- OpenCV (cv2)
- scikit-image
- matplotlib
- NumPy
- watermark (para obtener información del entorno)

---

### Se trata de:
**Contenido del Notebook**
- Apropiación del trabajo de un compañero sobre muestreo y cuantización de imágenes.
- Instalación e importación de librerías necesarias.
- Lectura de una imagen desde una URL.
- Visualización de la imagen original.
- Análisis de la imagen con la función data_img():
  - Muestra dimensiones, valores máximo y mínimo, y tipo de dato.
- Aplicación de muestreo con diferentes factores (factor_muestreo = 2, 4, 8).
- Cuantización de la imagen para reducir niveles de color.
- Combinación de técnicas de muestreo y cuantización para observar los efectos acumulados.
- Análisis del impacto visual y sobre la cantidad de información de cada técnica aplicada.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:.
   ```
   pip install opencv-python scikit-image matplotlib watermark
   ``` 
4. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
5. Ejecutá las celdas paso a paso para visualizar los efectos de cada transformación.
6. Modificá los valores de factor_muestreo y factor_cuantizacion para experimentar.

---

### Este repositorio se usa para:
Trabajo de Laboratorio: Edición y Procesamiento de Imágenes
El objetivo de este notebook es apropiarse del trabajo original de un compañero, comprendiendo y replicando las técnicas básicas del tratamiento digital de imágenes, como lectura, visualización, muestreo y cuantización, además de incorporar reflexiones personales.

---

### Actividades sugeridas:
- Cambiar la URL de la imagen y repetir los análisis.
- Probar diferentes combinaciones de factores de muestreo y cuantización.
- Reflexionar sobre la pérdida de información en cada caso.
- Explorar cómo se modifica el histograma con la cuantización.
- Evaluar qué combinaciones conservan mejor la calidad visual con menor tamaño de datos.
