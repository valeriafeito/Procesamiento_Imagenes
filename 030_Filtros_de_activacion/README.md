
**Nombre del Archivo:**  
`LAB_IMG_030_Feito_filtros_activaciones.ipynb`

---

**Proyecto:**  
Visualización de Filtros y Activaciones en una CNN Entrenada

**Fecha:** 16/06/2025  
**Autor:** Valeria Feito

---

### Tecnologías utilizadas:
- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

### Se trata de:  
**Contenido del Notebook**
- Exploración de filtros y activaciones internas de una red neuronal convolucional (CNN) entrenada.
- Uso del dataset `fashion_mnist` para clasificación de imágenes.
- Entrenamiento previo del modelo CNN con capas convolucionales, de pooling y densas.
- Construcción de un modelo intermedio para visualizar las salidas (activaciones) de cada capa.
- Visualización de filtros aprendidos por la red y cómo responden a una imagen de entrada.
- Análisis visual comparativo de diferentes capas: convolucionales y de pooling.
- Interpretación gráfica del flujo de información y de las transformaciones intermedias en la red.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 y las siguientes librerías instaladas:
   ```bash
   pip install tensorflow matplotlib numpy
   ```
2. Abrí el notebook en Jupyter Notebook, Deepnote o Google Colab.
3. Ejecutá todas las celdas en orden para entrenar el modelo y observar los filtros y activaciones.
4. Cambiá la imagen de entrada para visualizar cómo varían las respuestas de la red.

---

### Este repositorio se usa para:  
**Análisis Visual de Redes Convolucionales**  
El objetivo es comprender cómo funcionan internamente las CNNs observando los filtros aprendidos y las activaciones que se producen al pasar imágenes por la red.

---

### Actividades sugeridas:
- Probar con distintas imágenes del dataset o imágenes externas.
- Comparar activaciones entre distintas capas y tipos de filtros.
- Agregar visualización de activaciones para capas densas finales.
- Explorar cómo cambian los filtros al variar la arquitectura del modelo.
- Usar otras arquitecturas preentrenadas para realizar visualizaciones similares (por ejemplo, VGG16).
