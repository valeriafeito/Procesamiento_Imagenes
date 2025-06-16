**Nombre del Archivo:**  
`LAB_IMG_027_Feito_Clasificacion.ipynb`

---

**Proyecto:**  
Clasificación de Objetos en Imágenes con KNN

**Fecha:** 16/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (`cv2`)  
- scikit-learn  
- matplotlib  
- NumPy  
- watermark

---

### Se trata de:
**Contenido del Notebook**
- Ejercicio práctico de clasificación supervisada utilizando imágenes artificiales.
- Generación de un conjunto de datos con círculos y cuadrados de diferentes colores y tamaños.
- Extracción de características visuales simples:
  - Color promedio
  - Área del objeto
  - Tipo de forma
- Codificación de etiquetas para clasificación binaria (círculo vs cuadrado).
- División del dataset en conjunto de entrenamiento y prueba.
- Entrenamiento de un clasificador **K-Nearest Neighbors (KNN)**.
- Evaluación del modelo con métricas como **accuracy** y matriz de confusión.
- Visualización de resultados y discusión sobre la capacidad del modelo para distinguir formas simples.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python scikit-learn matplotlib numpy watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá todas las celdas para generar datos, entrenar el modelo y evaluar su rendimiento.
5. Experimentá cambiando parámetros como número de vecinos (k) o las características extraídas.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio sobre Clasificación Supervisada**  
El objetivo es aplicar técnicas básicas de aprendizaje automático a partir de datos visuales simples, desarrollando la intuición sobre cómo se construyen modelos clasificadores desde imágenes.

---

### Actividades sugeridas
- Probar con distintos valores de `k` en el clasificador KNN.
- Incorporar otras formas (triángulos, estrellas) para extender la clasificación.
- Agregar ruido a las imágenes y observar cómo afecta al rendimiento del modelo.
- Utilizar otros clasificadores como `DecisionTree` o `SVM` para comparar resultados.
- Reflexionar sobre los límites del aprendizaje supervisado con características simples.
