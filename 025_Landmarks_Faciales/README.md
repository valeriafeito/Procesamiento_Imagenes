**Nombre del Archivo:**  
`LAB_IMG_025_Feito_Landmarks_Faciales_1.ipynb`
`LAB_IMG_025_Feito_Landmarks_Faciales_2.ipynb`

---

**Proyecto:**  
Detección de Landmarks Faciales con Mediapipe

**Fecha:** 16/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (`cv2`)  
- mediapipe  
- matplotlib  
- NumPy  
- watermark

---

### Se trata de:
**Contenido del Notebook**
- Ejercicio introductorio para detección de puntos clave (landmarks) en rostros humanos.
- Carga de imagen con un rostro desde URL o archivo local.
- Uso del modelo de **MediaPipe Face Mesh** para localizar automáticamente 468 landmarks faciales.
- Visualización sobre la imagen original de:
  - Todos los puntos detectados.
  - Conexiones que definen mallas faciales (facial meshes).
  - Subconjuntos de landmarks para ojos, nariz, boca y contorno facial.
- Revisión de coordenadas 3D de los puntos clave detectados.
- Aplicaciones sugeridas: reconocimiento facial, expresión emocional, animación, realidad aumentada.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python mediapipe matplotlib numpy watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Subí una imagen de rostro o usá la imagen de ejemplo proporcionada.
5. Ejecutá las celdas paso a paso para observar cómo se detectan los puntos clave faciales.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio sobre Detección Facial**  
Su propósito es explorar el uso de modelos de detección de landmarks para comprender la estructura facial y abrir el camino hacia aplicaciones de reconocimiento, filtros interactivos y análisis biométrico.

---

### Actividades sugeridas
- Cambiar la imagen de entrada por otro rostro (propio o libre de derechos).
- Aplicar zoom sobre regiones específicas como ojos o boca para observar la precisión.
- Comparar la distribución de puntos entre diferentes expresiones faciales.
- Utilizar los landmarks para medir proporciones o detectar simetría.
- Explorar su uso en animación facial o aplicaciones de realidad aumentada.
