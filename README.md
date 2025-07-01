# TFM

## Análisis de Datos de Hielo Antártico

Este repositorio contiene un flujo de trabajo completo para el análisis y modelado de datos relacionados con la extensión del hielo en la Antártida. A continuación se describen brevemente los archivos principales incluidos:

### Estructura del repositorio

- `1-preprocesado.ipynb`: Notebook encargado de la limpieza y transformación inicial de los datos crudos. Incluye pasos como formateo de fechas, normalización y filtrado de columnas innecesarias.
- `2-reproyección.ipynb`: Realiza la reproyección de datos espaciales para su correcto análisis geográfico. Utiliza librerías GIS para convertir coordenadas a sistemas adecuados.
- `3-datasets-mix.ipynb`: Combina distintas fuentes de datos ya preprocesadas en un solo conjunto coherente, listo para el análisis posterior.
- `4-EDA.ipynb`: Contiene el análisis exploratorio de datos (EDA), incluyendo visualizaciones, estadísticas descriptivas y detección de patrones relevantes.
- `5-modeling.ipynb`: Desarrollo de modelos de Machine Learning para predecir o clasificar comportamientos del hielo antártico a partir de las variables disponibles.

### Datos


Los datos crudos necesarios para reproducir todo el flujo de trabajo pueden obtenerse desde las siguientes fuentes abiertas:

- https://nsidc.org/data/au_land/versions/1#anchor-3
- https://gportal.jaxa.jp/gpr/assets/mng_upload/GCOM-W/AMSR2_Higher_Level_Product_Format_EN.pdf

### Reproducibilidad

Los notebooks 4-EDA.ipynb y 5-modeling.ipynb pueden ejecutarse directamente una vez que los archivos de datos estén disponibles localmente. Dado que estos archivos son demasiado pesados para ser incluidos directamente en el repositorio, deben descargarse manualmente desde el siguiente enlace:

🔗 [Descargar datos desde Google Drive](https://drive.google.com/tu-enlace)


### Entorno de ejecución

Para facilitar la ejecución del proyecto, se incluye un archivo `environment.yml` que define el entorno de Anaconda con todas las librerías necesarias. 

---

Este trabajo está diseñado para ser modular y fácil de seguir, facilitando la comprensión del flujo completo desde los datos en bruto hasta modelos predictivos.
