<p align="center"><img src="assets/banner.svg" alt="Planteles Educativos de República Dominicana" width="100%"></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=geopandas&logoColor=white" alt="GeoPandas">
  <img src="https://img.shields.io/badge/Folium-77B829?style=flat-square&logo=folium&logoColor=white" alt="Folium">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
</p>

<p align="center">
  Parte del portafolio de <a href="https://github.com/drjay2018"><b>Jasser R. Moreno</b></a> · Análisis de Datos y Business Intelligence ·
  <a href="https://www.linkedin.com/in/jasser-moreno-medina">LinkedIn</a>
</p>

## La pregunta

¿Cómo se distribuyen los planteles, los estudiantes y los docentes en el país? El análisis explora el catálogo de más de 7,000 planteles educativos con su matrícula del año 2021 y lo lleva a un mapa donde se pueden ver todos los puntos por nivel educativo.

## Qué incluye el análisis

| Sección del notebook | Qué responde |
|---|---|
| Mapa de ubicación de planteles | Mapa interactivo con todos los planteles, visibles por nivel |
| Cantidad de planteles por provincia | Dónde se concentra la oferta educativa |
| Estudiantes matriculados por provincia | Dónde se concentra la demanda |
| Cantidad de planteles por nivel | Composición de la oferta por nivel |
| Top de distritos educativos | Distritos con más estudiantes |
| Promedio de estudiantes por plantel | Tamaño típico de un plantel en cada provincia |
| Estudiantes atendidos por docente | Carga docente por provincia |
| Reportes automáticos de exploración | Perfiles del dataset generados con Sweetviz y Pandas Profiling |

## Fuentes de datos

| Dato | Detalle |
|---|---|
| Centros educativos de República Dominicana 2021 | Portal de datos abiertos [datos.gob.do](https://datos.gob.do/dataset/centros-educativos-de-republica-dominicana/resource/42486490-51a6-4001-9349-db4604ee06a9) |
| Coordenadas de provincias | Tabla de apoyo geográfico |
| Shapefiles del Censo 2010 | Límites de provincia, municipio, sector y barrio/paraje |

## Stack

`pandas` · `numpy` · `fiona` · `geopandas` · `folium` · `plotly` · `matplotlib` · `seaborn` · `sweetviz` · `pandas-profiling`

## Cómo ejecutarlo

1. Abre `escuelas-rd.ipynb` en Jupyter o en Kaggle.
2. Carga los datasets de la tabla anterior.
3. Ejecuta las celdas en orden. La primera celda instala las librerías de reportes.

> Las rutas de los archivos están configuradas para el entorno de Kaggle (`/kaggle/input/...`). Para correrlo en local, descarga los datasets y ajusta esas rutas.

## Mejoras previstas

- Parametrizar las rutas de entrada en una sola celda de configuración.
- Exportar el mapa como HTML independiente para compartirlo sin ejecutar el notebook.
- Cruzar la matrícula con los resultados de las Pruebas Nacionales (ver [este análisis](https://github.com/drjay2018/analisis-pruebas-nacionales-rd)).

<p align="center"><sub>Datos públicos del Estado dominicano. Proyecto de análisis exploratorio con fines educativos y de portafolio.</sub></p>
