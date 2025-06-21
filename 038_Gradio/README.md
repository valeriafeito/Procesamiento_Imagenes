**Nombre del Archivo:** LAB_IMG_038_Feito_PDI_con_Gradio.ipynb

**Proyecto:** Aplicación de Procesamiento Digital de Imágenes con Interfaz Gráfica Gradio

**Fecha:** 18/06/2025

**Autor:** Valeria Feito

---

### Tecnologías utilizadas
- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib
- Gradio
- watermark (para información del entorno)

---

### Se trata de:
**Contenido del Notebook**
- Integración de procesamiento de imágenes con el desarrollo de una interfaz gráfica interactiva.
- Instalación e importación de librerías necesarias.
- Lectura de imagen desde archivo o subida por el usuario.
- Conversión de espacios de color para su posterior segmentación.
- Segmentación de regiones de la imagen según rango de color (HSV).
- Visualización de la imagen original y del resultado de la segmentación.
- Desarrollo de una aplicación web simple usando **Gradio** que permite al usuario:
  - Subir su propia imagen.
  - Ajustar parámetros de segmentación en tiempo real.
  - Visualizar el resultado procesado directamente desde el navegador.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
```bash
pip install opencv-python numpy matplotlib gradio watermark
```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas en orden para cargar el entorno y levantar la interfaz Gradio.
5. Interactuá con la aplicación web para probar la segmentación sobre distintas imágenes y parámetros.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Procesamiento Digital de Imágenes con Desarrollo Interactivo**
El objetivo es integrar el procesamiento digital de imágenes con el diseño de interfaces simples para usuarios finales, permitiendo experimentar de manera intuitiva con los parámetros de segmentación.

---

### Actividades sugeridas
- Probar con diferentes imágenes de entrada.
- Ajustar los rangos de color HSV para segmentar distintas regiones.
- Extender la interfaz agregando otros tipos de procesamiento (por ejemplo: filtros, detección de bordes, transformaciones geométricas).
- Implementar la posibilidad de guardar las imágenes resultantes.
- Compartir la aplicación en la nube a través de Gradio para demostraciones remotas.