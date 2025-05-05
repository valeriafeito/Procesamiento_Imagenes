
### Nombre del Archivo: `LAB_IMG_016_Feito_Template_Matching.ipynb`

**Proyecto:** Detección de Patrones con Template Matching  
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

---

### Se trata de:
**Contenido del Notebook**
- Instalación de dependencias para entornos como Google Colab.
- Creación de una imagen principal con formas geométricas simples (cuadrado, círculo).
- Generación de una imagen plantilla que se desea localizar dentro de la imagen principal.
- Aplicación de la técnica de Template Matching con OpenCV.
- Visualización del resultado con el área coincidente resaltada.
- Comparación de distintas funciones de coincidencia (`cv2.matchTemplate` con diferentes métodos).
- Análisis del comportamiento de la técnica frente a cambios en posición y tamaño del patrón.

---

### Instrucciones de uso:
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install opencv-python numpy matplotlib scikit-image watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá todas las celdas para ver cómo se detecta la ubicación del patrón en la imagen base.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Técnicas de Coincidencia de Patrones**  
El objetivo del notebook es mostrar el funcionamiento de template matching, una herramienta fundamental para reconocimiento de formas y detección localizada de objetos en imágenes digitales.

---

### Actividades sugeridas:
- Cambiar la plantilla por otra figura contenida en la imagen.
- Probar métodos distintos como `TM_CCOEFF`, `TM_SQDIFF`, `TM_CCORR_NORMED`.
- Añadir ruido a la imagen base y observar el impacto sobre el resultado.
- Intentar detección de plantillas con escalas o rotaciones diferentes.
- Usar imágenes reales y probar la detección de objetos o logotipos.
