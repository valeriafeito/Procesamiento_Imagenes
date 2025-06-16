**Nombre del Archivo:**  
`LAB_IMG_024_Feito_Restauracion_1.ipynb`
`LAB_IMG_024_Feito_Restauracion_2.ipynb`

---

**Proyecto:**  
Restauración de Imágenes con Técnicas de Filtrado

**Fecha:** 16/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- matplotlib  
- watermark

---

### Se trata de:
**Contenido del Notebook**
- Actividad práctica para explorar métodos básicos de restauración de imágenes deterioradas por ruido.
- Lectura de imagen y generación artificial de ruido:
  - **Ruido sal y pimienta**
  - **Ruido gaussiano**
- Aplicación de filtros para eliminar ruido y restaurar calidad visual:
  - **Filtro de mediana** para ruido impulsivo.
  - **Filtro gaussiano** para suavizar detalles y reducir variaciones locales.
- Comparación visual del antes y después de cada método.
- Observación de cómo cada filtro afecta la textura, contorno y nitidez de la imagen original.
- Introducción a conceptos de fidelidad y pérdida en la restauración.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python numpy matplotlib watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá cada bloque de código para generar ruido y restaurar imágenes.
5. Compará visualmente los resultados y evaluá el filtro más adecuado según el tipo de ruido.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio sobre Restauración de Imágenes**  
Su objetivo es introducir las técnicas más comunes de restauración aplicadas a imágenes digitales ruidosas, permitiendo desarrollar criterio para elegir el filtro adecuado.

---

### Actividades sugeridas
- Probar con imágenes diferentes y aplicar los mismos filtros.
- Ajustar el nivel de ruido artificial para observar su impacto en la restauración.
- Comparar otros métodos de filtrado como `blur` o `bilateral`.
- Aplicar filtros combinados (por ejemplo: mediana + gaussiano).
- Documentar los resultados mediante grillas visuales y conclusiones técnicas.
