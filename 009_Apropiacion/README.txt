
**Nombre del Archivo:** LAB_IMG_007_Feito_Segmentación por Color.ipynb  

**Proyecto:** Segmentación Simple por Color  

**Fecha:** 15/04/2025  

**Autor:** Valeria Feito  

---

### Tecnologías utilizadas
- Python 3.x  
- NumPy  
- OpenCV (cv2)  
- matplotlib  

---

### Se trata de:
**Contenido del Notebook**
- Ejemplo introductorio de segmentación de imágenes basado en el **color**.
- Importación de librerías necesarias (`numpy`, `cv2`, `matplotlib.pyplot`).
- Función `info_img(img)`:
  - Imprime las dimensiones de la imagen, y sus valores máximo y mínimo.
  - Usa `img.shape`, `img.max()` y `img.min()`.
- Carga de imagen desde archivo con `cv2.imread()`.
- Conversión del espacio de color BGR a HSV (Matiz, Saturación, Valor), más útil para segmentación por color.
- Definición de un **rango de color HSV** para segmentar.
- Creación de una **máscara binaria** con `cv2.inRange()`: 
  - Los píxeles dentro del rango definido se marcan en blanco (255).
  - Los demás se marcan en negro (0).
- Aplicación de la máscara sobre la imagen original con `cv2.bitwise_and()`.
- Creación de una nueva imagen con fondo negro y la región segmentada.
- Visualización de la imagen original, la máscara y el resultado segmentado.

---

### Instrucciones de uso
1. Abrí el notebook en **Deepnote**.  
2. Ejecutá las celdas en orden:  
   - Importación de librerías  
   - Definición de funciones  
   - Carga y procesamiento de imagen  
3. Modificá los valores de `lower_bound` y `upper_bound` para cambiar el color que se desea segmentar (en espacio HSV).  
4. Probá cargar distintas imágenes para observar cómo se comporta la segmentación.  

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**  
Este notebook tiene como objetivo explorar la **segmentación por color** como una técnica sencilla y eficaz para aislar objetos en imágenes, especialmente en contextos con fondos contrastantes.

---

### Actividades sugeridas
- Ajustar los **rangos HSV** para segmentar diferentes colores.  
- Probar con imágenes de diferentes escenas y colores dominantes.  
- Aplicar filtros como **blur** o **reducción de tonos** para mejorar la segmentación (como se hizo en los ejemplos del gato y el auto).  
- Analizar la calidad del resultado al modificar los parámetros de segmentación.  
- Investigar la segmentación en otros espacios de color (por ejemplo, LAB o YCrCb).  
