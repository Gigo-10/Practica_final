# Proyecto Final - Análisis Académico de Estudiantes

Este proyecto tiene como objetivo analizar información académica de estudiantes universitarios utilizando Python, Pandas, SQLite y Matplotlib.

## Fuentes de datos

El proyecto utiliza dos fuentes de datos:

1. Archivo CSV: estudiantes.csv, con 5000 registros.
2. Base de datos SQLite: universidad.db, con una tabla llamada notas y 5000 registros.

## Herramientas utilizadas

- Python
- JupyterLab
- Pandas
- SQLite
- Matplotlib

## Estructura del proyecto

- data/estudiantes.csv
- data/dataset_final.csv
- data/universidad.db
- /GENERAR.CSV.ipynb
- /crear_db.ipynb
- /analisis_estudiantes.ipynb

## Descripción

Se cargó un dataset de estudiantes desde un archivo CSV y otro dataset de notas desde una base de datos SQLite. Posteriormente, se unieron ambos datasets usando el campo id_estudiante. Finalmente, se generaron visualizaciones para analizar el rendimiento académico por carrera, materia y asistencia.
