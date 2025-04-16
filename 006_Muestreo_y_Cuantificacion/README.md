
**Nombre del Archivo:** LAB_IMG_006_Feito_Muestreo y Cuantización.ipynb  

**Proyecto:** Muestreo y Cuantización de Imágenes 

**Fecha:** 09/04/2025  

**Autor:** Valeria Feito  

---

### Tecnologías utilizadas
- Python 3.x  
- OpenCV (cv2)  
- scikit-image
- matplotlib  
- NumPy  
- watermark (para información del entorno)  

---

### Se trata de:
**Contenido del Notebook**
- Estudio de los efectos del muestreo y la cuantización en imágenes digitales.
- Lectura de imagen desde URL.
- Visualización y análisis inicial de la imagen original.
- Aplicación de diferentes factores de muestreo (factor_muestreo = 2, 4, 8), con reescalado para facilitar la visualización.
- Reducción de niveles de color mediante técnicas de cuantización (factor_cuantizacion = 64, 32, 16, 8).
- Análisis de los efectos combinados: primero muestreo y luego cuantización, y viceversa.
- Comparación visual de los resultados.
- Observación del impacto en la calidad visual y reducción del volumen de información.

---

### Instrucciones de uso
1. Asegurate de tener Python 3 instalado.  
2. Instalá las dependencias necesarias ejecutando:  
   ```
   pip install opencv-python matplotlib watermark
   ```  
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.  
4. Ejecutá las celdas una a una para observar cómo se manipula la información de color.  
5.Probá modificar los valores de factor_muestreo y factor_cuantizacion para experimentar.

---

### Este repositorio se usa para:
**Trabajo de Laboratorio: Edición y Procesamiento de Imágenes**  
Este notebook tiene como objetivo profundizar en los procesos de **muestreo espacial y cuantización de niveles de gris**, observando sus efectos individuales y combinados sobre la representación de una imagen..

---

### Actividades sugeridas
- Cambiar la imagen de entrada para probar con diferentes contenidos.
- Evaluar la pérdida de calidad según el orden de las transformaciones.
- Medir el ahorro en espacio de almacenamiento.
- Comparar resultados visuales entre aplicar primero muestreo o primero cuantización.
- Investigar cómo estas técnicas afectan la percepción del contenido por parte del usuario.
