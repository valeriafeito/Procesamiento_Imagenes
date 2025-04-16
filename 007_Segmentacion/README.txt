**Nombre del Archivo:** `LAB_IMG_007_Feito_Segmentación Simple.ipynb`  

**Proyecto:** Segmentación Básica de Imágenes  

**Fecha:** 09/04/2025  

**Autor:** Valeria Feito  

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (`cv2`)  
- scikit-image  
- matplotlib  
- NumPy  
- watermark (para información del entorno)  

---

### Se trata de:
**Contenido del Notebook**
- Introducción a los conceptos de **segmentación de imágenes**.
- Lectura de imagen desde URL o archivo local.
- Visualización inicial de la imagen original.
- Conversión a escala de grises y/o espacios de color alternativos.
- Aplicación de umbralado simple para segmentar regiones.
- Posible uso de filtros previos para suavizar la imagen antes del umbralado.
- Segmentación binaria para separar fondo y objeto(s).
- Visualización de la imagen segmentada y comparación con la original.
- Exploración de los efectos del cambio de umbral.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.  
2. Instalá las dependencias necesarias ejecutando:  
   ```bash
   pip install opencv-python matplotlib scikit-image watermark
   ```  
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.  
4. Ejecutá las celdas en orden para observar cómo se aplica la segmentación paso a paso.  
5. Probá modificar los valores del umbral para mejorar el resultado según el tipo de imagen.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**  
Este notebook tiene como objetivo introducir al estudiante en la técnica de **segmentación por umbralado**, una forma simple pero efectiva de separar objetos del fondo en imágenes digitales.

---

### Actividades sugeridas
- Cambiar la imagen de entrada por otras con distintos niveles de contraste.
- Probar con imágenes en color y convertirlas a distintos espacios antes de segmentar.
- Ajustar el valor del umbral y analizar cómo cambia la segmentación.
- Investigar sobre segmentación automática o por métodos adaptativos.
- Comparar la segmentación con y sin preprocesamiento (como suavizado o realce).
