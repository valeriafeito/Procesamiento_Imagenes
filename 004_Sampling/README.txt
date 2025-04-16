
**Nombre del Archivo:** LAB_IMG_004_Feito_Sampling.ipynb  

**Proyecto:** Muestreo Digital de Imágenes  

**Fecha:** 08/04/2025  

**Autor:** Valeria Feito  

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (cv2)  
- scikit-image  
- matplotlib  
- NumPy  
- watermark (para información del entorno)  

---

### Se trata de:
**Contenido del Notebook**
- Análisis del proceso de muestreo de imágenes digitales.
- Instalación e importación de librerías necesarias.
- Lectura de imagen desde una URL.
- Visualización y análisis de la imagen original.
- Función `data_img()` para inspección de propiedades (dimensiones, valores, tipo).
- Aplicación de muestreo con distintos factores (`factor_muestreo = 2, 4, 8`).
- Reescalado de las imágenes muestreadas para mantener el tamaño de visualización.
- Comparación visual entre la imagen original y las muestreadas.
- Discusión sobre los efectos del muestreo en la calidad y la percepción visual.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.  
2. Instalá las dependencias necesarias ejecutando:  
   ```
   pip install opencv-python scikit-image matplotlib watermark
   ```  
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.  
4. Ejecutá las celdas para visualizar cómo cambia la imagen al aplicar diferentes niveles de muestreo.  
5. Modificá el `factor_muestreo` para experimentar con otras resoluciones.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**  
Este notebook tiene como objetivo explorar el concepto de **muestreo** en el procesamiento digital de imágenes, permitiendo visualizar cómo se reduce la información espacial y cómo esto afecta la calidad percibida.

---

### Actividades sugeridas
- Probar con diferentes imágenes de entrada.  
- Comparar los resultados con y sin reescalado.  
- Combinar muestreo con otras técnicas como cuantización.  
- Medir el impacto en el tamaño del archivo y la calidad visual.  
- Analizar si ciertas imágenes toleran mejor la pérdida de resolución.
