
### Nombre del Archivo: `LAB_IMG_020_Feito_Deteccion_de_rostros.ipynb`

**Proyecto:** Detección de Rostros en Imágenes Estáticas  
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
- IPython.display (YouTubeVideo)

---

### Se trata de:
**Contenido del Notebook**
- Introducción teórica al algoritmo de **Viola & Jones** (2001) y su vigencia actual.
- Instalación de dependencias necesarias en Google Colab o entorno local.
- Carga de imágenes con rostros humanos.
- Aplicación de detección de caras mediante clasificadores Haar preentrenados (`haarcascade_frontalface_default.xml`).
- Visualización de resultados con bounding boxes sobre las regiones detectadas.
- Incorporación de material de apoyo visual como video de YouTube y esquemas explicativos.
- Discusión sobre el concepto de **ventana deslizante** y el uso de **cascadas de clasificadores**.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python numpy matplotlib scikit-image watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Asegurate de tener el archivo `haarcascade_frontalface_default.xml` descargado en el mismo directorio.
5. Ejecutá las celdas paso a paso para realizar detección facial.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Introducción a la Detección de Objetos (Face Detection)**  
El objetivo del notebook es experimentar con un método tradicional y eficaz de detección de rostros, aplicable en aplicaciones en tiempo real, dispositivos móviles y sistemas embebidos.

---

### Actividades sugeridas:
- Probar el clasificador Haar con distintas imágenes propias.
- Modificar los parámetros de `scaleFactor` y `minNeighbors` para mejorar la detección.
- Combinar la detección con anotaciones usando `cv2.putText()`.
- Explorar la detección de ojos o sonrisas con clasificadores alternativos.
- Investigar comparaciones con métodos basados en redes neuronales como MTCNN o Dlib.
