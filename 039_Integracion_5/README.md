**Nombre del Archivo:**  
`LAB_IMG_039_Computer_Vision_YOLO.ipynb`  
`LAB_IMG_039_Computer_Vision_YOLO.pptx`  


**Proyecto:** Clasificador de Residuos con YOLOv8 y Visión por Computadora  

**Fecha:** 16/06/2025  

**Autores:** Hernan Alvarenga - Valeria Feito - Ignacio Mendiola - Hugo Peña  

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV  
- Ultralytics YOLOv8  
- PIL (Pillow)  
- Google Colab (para procesamiento con GPU)  
- matplotlib  
- os, shutil  

---

### Se trata de:
**Contenido del Notebook**
- Desarrollo de un proyecto de clasificación de residuos reciclables y no reciclables utilizando un modelo preentrenado YOLOv8.
- Carga de imágenes de prueba desde un conjunto predefinido.
- Detección de objetos con el modelo YOLOv8, destacando las clases detectadas.
- Comparación entre objetos reciclables y no reciclables mediante listas de IDs.
- Visualización de resultados con bounding boxes y etiquetas.
- Ejecución del modelo tanto con imágenes individuales como en lote.
- Preparación para integración con cámara en tiempo real (comentado).

---

### Instrucciones de uso
1. Abrí el notebook en Google Colab para aprovechar el soporte de GPU.
2. Ejecutá las celdas paso a paso:
   - Instalación de `ultralytics`
   - Carga del modelo `yolov8n.pt` o uno más potente si se desea.
   - Subida o selección de imágenes para clasificar.
3. Observá la salida con detecciones destacadas en color.
4. Si se desea usar cámara en vivo, descomentá las celdas correspondientes (requiere permisos del navegador).

---

### Este repositorio se usa para:
**Trabajo Integrador de la materia Procesamiento Digital de Imágenes (PDI)**  
El objetivo es demostrar la capacidad de aplicar técnicas avanzadas de visión por computadora con redes neuronales convolucionales para resolver un problema real: la clasificación de residuos mediante imágenes.

---

### Actividades sugeridas
- Probar con un modelo más robusto (`yolov8m.pt`, `yolov8l.pt`) para mejorar precisión.
- Reentrenar YOLOv8 con un dataset personalizado de residuos.
- Agregar un filtro para contar residuos reciclables vs. no reciclables.
- Integrar detección en tiempo real con webcam para un prototipo funcional.
- Conectar el clasificador con una acción física (por ejemplo, Arduino + servomotor).
