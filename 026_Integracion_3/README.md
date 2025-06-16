**Nombre del Archivo:**  
---  
`LAB_IMG_026_Feito_Integracion.ipynb`  
---  

**Proyecto:** Integración de Técnicas de Procesamiento Digital de Imágenes  
**Fecha:** 13/05/2025  
**Autor:** Valeria Feito  

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- matplotlib  
- scikit-learn (`KMeans`)  
- MediaPipe (opcional)  
- watermark (para información del entorno)  

---

### Se trata de:
**Contenido del Notebook**
- Actividad integradora con una duración estimada de 1 hora.
- Carga de imagen con contenido humano para detección y segmentación.
- Conversión del espacio de color BGR a HSV para filtrado cromático.
- Aplicación de máscaras por rango de color (en este caso, tonos amarillos).
- Uso de operaciones morfológicas (`closing`, `opening`) para limpieza de ruido.
- Segmentación mediante clustering con K-means.
- Detección de bordes y superposición de contornos.
- Exploración opcional de landmarks faciales mediante MediaPipe.
- Visualización secuencial de los resultados intermedios y finales.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.  
2. Instalá las dependencias necesarias ejecutando:  
   ```bash
   pip install opencv-python matplotlib numpy scikit-learn mediapipe watermark
   ```  
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.  
4. Ejecutá las celdas en orden para visualizar el proceso completo de segmentación y detección.  
5. Podés modificar los parámetros de filtrado, el número de clusters o el tipo de operaciones morfológicas para experimentar.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Actividad de integración final de la unidad**  
Su propósito es aplicar de manera articulada las distintas técnicas de procesamiento de imágenes, reconociendo su complementariedad y valor práctico.

---

### Actividades sugeridas
- Cambiar la imagen de entrada por una con diferente contenido cromático.
- Ajustar los valores HSV para segmentar otros colores (rojo, azul, verde, etc.).
- Añadir filtros adicionales (blur, sharpening) antes del clustering.
- Comparar la segmentación de K-means con otras técnicas (thresholding, watershed).
- Documentar los resultados con capturas “antes y después” de cada etapa.