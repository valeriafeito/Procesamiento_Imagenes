**Nombre del Archivo:**
---
`LAB_IMG_041_FEITO_img_caption.ipynb`

**Proyecto:** Generación de Descripciones de Imágenes (Image Captioning)

**Fecha:** 17/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (cv2)  
- Matplotlib  
- NumPy  
- PIL (Pillow)  
- torch (PyTorch)  
- torchvision  
- transformers (Hugging Face)  
- watermark (para información del entorno)

---

### Se trata de:
**Contenido del Notebook**
- Implementación de un sistema básico de *Image Captioning*.
- Lectura y visualización de una imagen desde archivo.
- Utilización de modelos preentrenados de la librería **transformers** para generar descripciones automáticas de la imagen cargada.
- Ejemplo de aplicación de modelos de Visión por Computadora combinados con NLP.
- Visualización del resultado con la imagen y su descripción generada.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python matplotlib numpy pillow torch torchvision transformers watermark
   ```
3. Abrí el notebook en Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas en orden para cargar la imagen, ejecutar el modelo y visualizar el resultado.
5. Podés probar reemplazando la imagen por otras para generar nuevas descripciones.

---

### Este repositorio se usa para:
**Laboratorio de Práctica de Image Captioning**  
El objetivo es experimentar con la generación automática de descripciones a partir de imágenes, integrando modelos preentrenados de visión y lenguaje.

---

### Actividades sugeridas
- Probar con distintas imágenes y analizar la calidad de las descripciones generadas.
- Investigar otros modelos preentrenados disponibles en la librería `transformers`.
- Comparar los resultados obtenidos con distintas arquitecturas (por ejemplo BLIP, Flamingo, etc.).
- Implementar un pequeño dataset de prueba con varias imágenes para evaluar el sistema en lote.
- Discutir limitaciones y potenciales aplicaciones de los modelos de *Image Captioning*.
