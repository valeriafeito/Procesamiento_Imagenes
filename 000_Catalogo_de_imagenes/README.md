# Nombre del Archivo: Catalogo_de_Imagenes.ipynb

## Proyecto: Exploración de Catálogo de Imágenes

**Fecha:** 25/04/2025  
**Autor:** Valeria Feito

---

## Tecnologías utilizadas

- Python 3.x  
- OpenCV (cv2)  
- Matplotlib  
- NumPy  
- os, glob (para manejo de archivos)  

---

## Se trata de:

### Contenido del Notebook

- Exploración de un directorio de imágenes.
- Lectura y visualización sistemática de múltiples archivos con OpenCV.
- Reescalado de imágenes a un tamaño uniforme para facilitar su análisis y visualización.
- Visualización en grilla con `matplotlib` para comparación simultánea.
- Extracción y visualización de histogramas por canal (RGB) de cada imagen.
- Evaluación comparativa de características visuales entre las imágenes del catálogo.
- Uso de estructuras iterativas para automatizar el análisis por lotes.

---

## Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instala las dependencias ejecutando:

```bash
pip install opencv-python matplotlib numpy
```

3. Ubicá las imágenes a analizar dentro de un directorio local y actualizá la ruta en el notebook.
4. Ejecutá el notebook desde Jupyter, Deepnote o Colab.
5. Explorá los resultados visuales y experimentá con otras imágenes o tamaños de visualización.

---

## Este repositorio se usa para:

**Trabajo de Laboratorio: Catálogo de Imágenes**  
El objetivo es automatizar la carga, visualización y análisis de un conjunto de imágenes, promoviendo habilidades en procesamiento por lotes y comparación visual basada en histogramas de color.

---

## Actividades sugeridas

- Cambiar el conjunto de imágenes y repetir el análisis.
- Modificar el tamaño de reescalado para evaluar el impacto visual.
- Incorporar métricas adicionales (por ejemplo, similitud de histogramas).
- Clasificar las imágenes según características dominantes de color.
- Implementar filtros por nombre o tipo de archivo dentro del catálogo.