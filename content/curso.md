---
title: Curso
---

El curso presenta el flujo de trabajo ilustrado en el siguiente diagrama:

![](/./curso_files/data-science.png)

Todos los proyectos de análisis de datos incluyen estas etapas en distintos niveles de complejidad: importar los datos, transformarlos, modelizarlos, visualizarlos y comunicar los resultados obtenidos. Las herramientas del `tidyverse` dan soporte a este flujo de trabajo para que el proceso de análisis de datos sea __reproducible__.  


## Módulo 1: Visualización con `ggplot`


+ Sesión 1: La gramática de gráficos y `ggplot` [ [slides](https://modulo1.netlify.com/) ]
    + Introducción
    + Aesthetics
    + Geoms
    + Facets
+ Sesión 2: La gramática de gráficos y `ggplot`
    + Transforms
    + Posición
    + Ejercicios: Gráficos de Torta, gráficos de barra, gráficos de línea

## Módulo 2: Importar datos

R permite importar datos desde una gran variedad de fuentes (archivos de texto plano, formatos de otros paquetes estadísticos, bases de datos relacionales y APIs online). En este módulo nos centramos en las funciones para importar desde archivos de texto y planillas de excel.

+ Sesión 2: Importar datos con `readr` 
    + Importar archivos de texto plano con `read_csv()`
    + Importar archivos de excel con `read_xls()` y `read_xlsx()`

## Módulo 3: Transformar Datos con `dplyr`

+ Sesión 4 `dplyr` (1) -
    + Seleccionar columnas con `select()`
    + Crear nuevas columnas con `mutate()`
    + Filtrar filas con `filter()`
    + Ordenar con `arrange()`
+ Sesión 5 `dplyr` (2)
    + Pasar de wide a long con `gather`
    + Unir tablas con `*_join()`
    + Pasar de long a wide con `spread`
    
+ Sesión 6 `forcats` & `lubridate`


## Módulo 4: Modelos

Ajustar modelos.

## Módulo 5: Comunicación de Resultados

Los proyectos de análisis de datos tienen como resultado un output con las conclusiones que puede ser un documento word o pdf, una presentación de power point, una página web, etc. Comunicar los resultados obtenidos es una parte esencial del proceso de análisis de datos, y R tiene herramientas para darle soporte.

+ Sesión 7 Markdown y RMarkdown
