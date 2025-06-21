
## **Nombre del Archivo:**

`LAB_IMG_042_Feito_faker.ipynb`

**Proyecto:** Generación de Datos Sintéticos con Faker

**Fecha:** 17/06/2025**Autor:** Valeria Feito

---

### Tecnologías utilizadas

- Python 3.x
- Faker
- Pandas
- NumPy
- watermark (para información del entorno)

---

### Se trata de:

**Contenido del Notebook**

- Introducción a la generación de datos sintéticos.
- Instalación e importación de la librería `faker` para simular datos ficticios.
- Creación de un conjunto de datos artificial que incluye:
  - Nombres
  - Direcciones
  - Correos electrónicos
  - Teléfonos
  - Fechas de nacimiento
  - Nacionalidades
- Conversión de los datos generados en un `DataFrame` de pandas.
- Visualización y exportación del dataset simulado.
- Aplicación de funciones de `watermark` para documentar el entorno de ejecución.

---

### Instrucciones de uso

1. Asegurate de tener Python 3 instalado.
2. Instalá las dependencias necesarias ejecutando:
   ```bash
   pip install faker pandas numpy watermark
   ```
3. Abrí el notebook con Jupyter Notebook, Deepnote o Google Colab.
4. Ejecutá las celdas en orden para generar el dataset sintético.
5. Modificá los parámetros (cantidad de registros, campos) según necesidades particulares de simulación.

---

### Este repositorio se usa para:

**Práctica de Generación de Datos Artificiales**El objetivo es introducir el uso de `faker` como herramienta para generar datos falsos de prueba, útiles para experimentación, desarrollo de modelos, o testeo de pipelines de procesamiento.

---

### Actividades sugeridas

- Ampliar el conjunto de atributos generados (por ejemplo: profesiones, empresas, tarjetas de crédito).
- Ajustar el número de registros generados para distintas escalas de prueba.
- Exportar el dataset a distintos formatos (CSV, JSON, Excel) según el destino del ejercicio.
- Aplicar transformaciones sobre los datos generados (normalización, enmascaramiento, validación).
- Integrar los datos generados en pipelines de entrenamiento de modelos de Machine Learning o pruebas de ETL.
