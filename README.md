# IBM Data Analyst Capstone Project – Módulo 1  
## Jobs_API & Colecta de datos con APIs

Este repositorio contiene dos archivos principales desarrollados como parte del **Módulo 1** del proyecto final del curso **IBM Data Analyst Capstone Project**:

### Contenido

Jobs_API.py: Implementa una API local en Flask que sirve datos de ofertas de empleo cargados desde el archivo `jobs.json`.  
  Permite realizar búsquedas filtradas por tecnología, ubicación y otros campos.
Collecting_job_data_using_APIs-Lab.ipynb:  Notebook que interactúa con la API creada en `Jobs_API.py`, consultando los datos de tecnologías específicas y generando un archivo Excel con los resultados obtenidos.

---

### Archivos adicionales
jobs.json:  Contiene las ofertas de trabajo en formato JSON.  
Job-postings.xlsx: Archivo Excel generado por el notebook con los resultados de las consultas a la API.  **Se incluye en este repositorio** para facilitar la visualización del resultado sin necesidad de ejecutar el notebook.


### Cómo usar
Ejecuta Jobs_API.py para iniciar la API en http://127.0.0.1:5000.

Abre y ejecuta Collecting_job_data_using_APIs-Lab.ipynb para consultar datos de tecnologías específicas y guardar los resultados en Excel.
