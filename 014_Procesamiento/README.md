
### Nombre del Archivo: `LAB_IMG_014_Feito_Procesamiento.ipynb`

**Proyecto:** Procesamiento Básico de Imágenes en Python  
**Fecha:** 05/05/2025  
**Autor:** Valeria Feito

---

### Tecnologías utilizadas:
- Python 3.x  
- NumPy  
- matplotlib  
- scikit-image  
- PIL (Python Imaging Library)

---

### Se trata de:
**Contenido del Notebook**
- Exploración de técnicas fundamentales del procesamiento digital de imágenes.
- Carga de imágenes utilizando `skimage.data` y descarga de imágenes externas vía URL.
- Aplicación de **muestreo**: reducción de la resolución mediante submuestreo.
- Aplicación de **cuantización**: reducción de niveles de color para comprimir información visual.
- Visualización comparativa entre imagen original, muestreada y cuantizada.
- Guardado de imágenes en distintos formatos (`.png` sin pérdida y `.jpg` con pérdida).
- Análisis de los efectos de cada técnica sobre la calidad y el tamaño de la imagen resultante.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install numpy matplotlib scikit-image pillow
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas en orden para visualizar los efectos de cada transformación sobre la imagen.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Técnicas básicas de Procesamiento Digital de Imágenes**  
El objetivo del notebook es familiarizarse con operaciones elementales como la lectura, visualización, muestreo, cuantización y exportación de imágenes, permitiendo reflexionar sobre el impacto de estas transformaciones.

---

### Actividades sugeridas:
- Cambiar la imagen por otra propia y repetir el proceso.
- Probar diferentes factores de muestreo (por ejemplo, 2, 3, 8).
- Variar la profundidad de cuantización (ej. 2 bits, 4 bits, 6 bits).
- Comparar visualmente los resultados y sus tamaños en disco.
- Analizar qué técnicas conservan mejor la calidad visual con menor tamaño de archivo.
