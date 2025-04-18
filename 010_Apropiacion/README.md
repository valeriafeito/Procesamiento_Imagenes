# LAB_IMG_010_Feito_Apropiación.ipynb

**Proyecto:** Apropiación de Técnicas de Segmentación y Transformaciones Básicas  
**Fecha:** 14/04/2025  
**Autor:** Valeria Feito  

---

## Tecnologías utilizadas
- Python 3.x  
- OpenCV (cv2)  
- scikit-image  
- matplotlib  
- NumPy  
- watermark (para obtener información del entorno)  

---

## Se trata de:
**Contenido del Notebook**
- Apropiación del trabajo de un compañero para estudiar técnicas básicas de segmentación de imágenes.
- Instalación e importación de las librerías necesarias para procesamiento.
- Lectura de imagen desde archivo.
- Conversión de imagen a escala de grises.
- Aplicación de un umbral simple para separar objetos del fondo.
- Uso de filtros para suavizar la imagen (blur y median blur).
- Exploración de la función `cv2.threshold` con distintos tipos de umbralado.
- Aplicación de `cv2.inRange` para aislar un rango específico de intensidades.
- Visualización de resultados para comparar el impacto de cada técnica.
- Análisis visual de la segmentación y su sensibilidad a los parámetros.

---

## Instrucciones de uso
1. Asegurate de tener Python 3 instalado.  
2. Instalá las dependencias necesarias ejecutando:  
   ```bash
   pip install opencv-python scikit-image matplotlib watermark
   ```
3. Abrí el notebook con **Jupyter Notebook**, **Deepnote** o **Google Colab**.  
4. Ejecutá las celdas paso a paso para observar los efectos de cada transformación aplicada.  
5. Probá distintos valores de umbral y parámetros de suavizado para experimentar con la segmentación.  

---

## Este repositorio se usa para:
**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**  
Este notebook tiene como objetivo **apropiarse y comprender técnicas básicas de segmentación digital**, especialmente aquellas basadas en el umbralado, filtros y rangos de intensidad, a partir del análisis del trabajo de un compañero y la incorporación de nuevos enfoques o interpretaciones.

---

## Actividades sugeridas
- Cambiar la imagen de entrada para analizar otros objetos.  
- Probar diferentes tipos de filtros antes del umbralado.  
- Ajustar los valores de `cv2.threshold` y `cv2.inRange` para estudiar la sensibilidad del resultado.  
- Analizar el histograma de la imagen para fundamentar la elección de umbrales.  
- Comparar visualmente los resultados de distintas técnicas de segmentación.