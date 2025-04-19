### 📄 Nombre del Archivo: `LAB_IMG_011_Feito_Apropiacion.ipynb`

**Proyecto:** Apropiación de Técnicas de Procesamiento de Imágenes  
**Fecha:** 14/04/2025  
**Autor:** Valeria Feito  

---

### 🧰 Tecnologías utilizadas

- Python 3.x  
- OpenCV (`cv2`)  
- `scikit-image`  
- `matplotlib`  
- `NumPy`  
- `watermark` (para obtener información del entorno)  

---

### 🧠 Se trata de:

**Contenido del Notebook:**

- Apropiación del trabajo de un compañero sobre segmentación por color.
- Instalación e importación de librerías necesarias.
- Lectura de imagen desde archivo local.
- Visualización de la imagen original.
- Conversión de la imagen del espacio de color BGR a HSV.
- Definición de umbrales para segmentar un color específico (amarillo).
- Creación de máscara binaria con `cv2.inRange()`.
- Extracción de la región segmentada mediante operaciones lógicas (`bitwise_and`).
- Visualización de resultados: imagen original, máscara y segmentación.
- Reflexión sobre el uso de `blur` y reducción de tonos para mejorar los resultados.

---

### ▶️ Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:

   ```bash
   pip install opencv-python scikit-image matplotlib watermark
   ```

3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas en orden para observar el proceso de segmentación paso a paso.
5. Podés modificar los valores de los umbrales HSV para experimentar con diferentes colores o imágenes.

---

### 🎯 Este repositorio se usa para:

**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**

El objetivo de este notebook es **comprender y aplicar técnicas básicas de segmentación por color** y apropiarse del trabajo de otro estudiante mediante la exploración, análisis crítico y expansión del enfoque original.

---

### 💡 Actividades sugeridas

- Cambiar la imagen por otra con colores bien definidos.
- Probar con otros rangos HSV para segmentar distintos objetos.
- Aplicar `blur` u otras técnicas de preprocesamiento para mejorar los resultados.
- Comparar la segmentación con distintas iluminaciones.
- Analizar el impacto del color y la iluminación en la precisión de la máscara.