
### Nombre del Archivo: `LAB_IMG_018_Feito_Recorte_extraccion_y_perspectiva.ipynb`

**Proyecto:** Recorte y Corrección de Perspectiva en Imágenes  
**Fecha:** 05/05/2025  
**Autor:** Valeria Feito

---

### Tecnologías utilizadas:
- Python 3.x  
- OpenCV (cv2)  
- NumPy  
- matplotlib  
- scikit-image  
- watermark

---

### Se trata de:
**Contenido del Notebook**
- Instalación de dependencias para entorno Colab o local.
- Descarga de imagen con perspectiva oblicua desde una URL.
- Identificación manual de los cuatro puntos de una carta (rey de picas).
- Construcción de una matriz de transformación de perspectiva con `cv2.getPerspectiveTransform()`.
- Aplicación de la transformación mediante `cv2.warpPerspective()`.
- Visualización del resultado: recorte corregido, orientado en vista frontal.
- Introducción visual y práctica al cambio de perspectiva en visión por computadora.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python numpy matplotlib scikit-image watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas paso a paso para seguir el proceso de recorte y transformación.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Manipulación de Zonas de Interés en Imágenes**  
El objetivo del notebook es comprender cómo seleccionar una región específica en una imagen y corregir su perspectiva para obtener una visualización más clara y útil.

---

### Actividades sugeridas:
- Cambiar la imagen por otra con un objeto en perspectiva y realizar el mismo procedimiento.
- Experimentar con distintas ubicaciones de los puntos para observar el efecto en la transformación.
- Aplicar la técnica a documentos escaneados torcidos para “alinearlos”.
- Combinar esta técnica con segmentación previa o detección automática de esquinas.
- Usar `cv2.boundingRect()` y `cv2.approxPolyDP()` para automatizar parte del recorte.
