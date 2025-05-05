
### Nombre del Archivo: `LAB_IMG_021_Feito_Mejoras_del_Color.ipynb`

**Proyecto:** Mejora de Color, Contraste y Luminosidad en Imágenes  
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
- Instalación de librerías necesarias para Google Colab o entorno local.
- Carga de una imagen de ejemplo desde URL.
- Visualización de la imagen original como referencia inicial.
- Aplicación de mejoras de imagen mediante:
  - Conversión al espacio de color HSV.
  - Modificación del canal V (Value) para ajustar la luminosidad.
  - Ecualización del histograma para mejorar contraste.
- Comparación visual entre imagen original y corregida.
- Discusión sobre los efectos perceptivos de cada técnica aplicada.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python numpy matplotlib scikit-image watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas en orden para observar los efectos de las técnicas de mejora.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Técnicas de Mejora de Imagen**  
El objetivo del notebook es aplicar técnicas simples y efectivas para mejorar visualmente una imagen digital, lo cual resulta útil en etapas de preprocesamiento o visualización.

---

### Actividades sugeridas:
- Probar otras imágenes con distintos niveles de iluminación.
- Aplicar la ecualización solo sobre regiones específicas.
- Comparar mejoras en espacios de color alternativos (YUV, LAB).
- Superponer resultados antes y después para análisis visual.
- Explorar otros métodos como `cv2.equalizeHist()` sobre el canal Y en YUV.
