## Descripción del proyecto
Este proyecto analiza datos históricos sobre atletas que hayan participado y sus resultados obtenidos en los Juegos olípicos desde sus inicios hasta la edición de Rio 2016. Este análisis se hace mediante Python y la librería Pandas.

El análisis usa datos sobre edad, sexo, estatura, peso, deporte, temporada y medallas, entre otras para estudiar cómo estas características han cambiado a través del tiempo y qué grupos de atletas han tenido una mayor proporción de resultados con medalla.

## Integrantes y roles

- **David Ruiz**: Líder de Datos -  Limpieza, transformación y análisis de los datos 

- **Ometh Mejia**: Líder de Repositorio - Gestión de ramas, Pull Requests y conflictos 

- **Alejandro Pachón**: Líder de Reporte - Redacción, documentación y presentación de resultados

## Objetivos del proyecto
- Analizar la evolución histórica de la participación y los resultados de los atletas en los Juegos Olímpicos mediante el uso de Pandas y aplicando procesos de carga, limpieza, transformación, agrupación y visualización de datos.
- Comparar la participación olímpica por época, sexo y temporada.
- Analizar la frecuencia y proporción de resultados con medalla.
- Explorar la relación entre las características de los atletas y la obtención
  de medalla

## Instrucciones para ejecutar el código
1. Clonar el repositorio
2. Entrar al colab del script final, ubicado en la carpeta notebooks/
3. Descargar los datos y guardarlos en una carpeta llamada "Datos" dentro del panel de archivos de colab
4. Ejecutar el notebook

## Estructura del proyecto
```text
taller-pandas-olimpiadas-grupoX/
├── README.md
├── .gitignore
├── requirements.txt
├── data/
│   └── README.md
├── notebooks/
│   └── proyecto_olimpiadas.ipynb
├── src/
│   ├── cargue_datos.py
│   └── analisis_olimpiadas.py
├── outputs/
│   ├── tablas/
│   └── graficos/
└── docs/
    ├── informe_final.pdf
    └── conflictos_github.md
