**Nombre del Archivo:**  
`LAB_IMG_023_Feito_Operaciones_Morfologicas_1.ipynb`
`LAB_IMG_023_Feito_Operaciones_Morfologicas_2.ipynb`

---

**Proyecto:**  
Técnicas Morfológicas en Imágenes Binarias

**Fecha:** 16/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- matplotlib  
- watermark (para identificar versiones del entorno)

---

### Se trata de:
**Contenido del Notebook**
- Trabajo práctico introductorio a las operaciones morfológicas básicas en imágenes binarias.
- Carga de imagen desde archivo local o URL, conversión a escala de grises y binarización.
- Aplicación de las operaciones fundamentales:
  - **Erosión**: reducción del área blanca en la imagen.
  - **Dilatación**: expansión de regiones blancas.
  - **Apertura**: erosión seguida de dilatación (elimina ruido).
  - **Cierre**: dilatación seguida de erosión (rellena huecos).
- Visualización comparativa de resultados usando `matplotlib` en una grilla.
- Introducción al concepto de *kernel estructurante* y su impacto en los resultados.
- Ensayo con distintos tamaños de kernel para observar el efecto sobre la imagen procesada.

---

### Instrucciones de uso
1. Verificá que tengas instalado Python 3.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python numpy matplotlib watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas paso a paso para observar el efecto de cada operación morfológica.
5. Modificá el tamaño del kernel para experimentar con distintos resultados.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio sobre Morfología Matemática**  
El objetivo es comprender el comportamiento de las operaciones morfológicas sobre imágenes binarias, y cómo se pueden aplicar para limpiar ruido, resaltar estructuras o mejorar segmentaciones.

---

### Actividades sugeridas
- Probar distintos tamaños de kernel y comparar los resultados.
- Aplicar las técnicas sobre otras imágenes binarias (formas, texto, contornos).
- Combinarlas con técnicas previas como segmentación por color o umbralado.
- Analizar el resultado visual de aplicar operaciones encadenadas (ej. cierre + apertura).
- Justificar técnicamente en qué casos conviene usar apertura o cierre.
