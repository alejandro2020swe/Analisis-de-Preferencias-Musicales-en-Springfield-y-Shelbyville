# Análisis de Preferencias Musicales en Springfield y Shelbyville

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar las preferencias musicales de los usuarios de dos ciudades, Springfield y Shelbyville, utilizando datos de transmisión de música en línea. A través de este análisis, se busca probar la hipótesis de que la actividad musical de los usuarios difiere según el día de la semana y la ciudad.

El proyecto se divide en tres etapas:

1. **Descripción de los Datos**: Exploración inicial de los datos para entender su estructura y características.
2. **Preprocesamiento de Datos**: Limpieza y preparación de los datos para su análisis.
3. **Prueba de Hipótesis**: Evaluación de la hipótesis mediante el análisis de los datos preprocesados.

## Hipótesis

La hipótesis que se prueba en este proyecto es:

> La actividad de los usuarios y las usuarias difiere según el día de la semana y dependiendo de la ciudad.

## Datos

Los datos se encuentran en el archivo `datasets/music_project_en.csv` y contienen las siguientes columnas:

- **userID**: Identificador único de cada usuario o usuaria.
- **Track**: Título de la canción.
- **artist**: Nombre del artista.
- **genre**: Género musical.
- **City**: Ciudad del usuario o usuaria.
- **time**: Hora del día en la que se reprodujo la pista (HH:MM:SS).
- **Day**: Día de la semana.
