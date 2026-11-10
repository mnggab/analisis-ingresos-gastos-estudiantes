# Análisis de ingresos y egresos de estudiantes universitarios

## Descripción del proyecto

Este proyecto forma parte del trabajo final integrador de análisis de datos. Su objetivo es explorar los ingresos, la ayuda financiera y los gastos de estudiantes universitarios, utilizando Python, Power BI y GitHub.

Objetivo y preguntas de investigación

Objetivo general

El objetivo de este proyecto es analizar el comportamiento de los ingresos y gastos de estudiantes universitarios, identificando patrones y diferencias según distintas características, como la edad, el género y el año de cursada.

A través del análisis exploratorio de datos y la creación de visualizaciones, se busca comprender cómo se distribuyen los ingresos, cuáles son las principales categorías de gastos y qué diferencias pueden observarse entre los distintos grupos de estudiantes.

Preguntas de investigación

Para orientar el análisis, se plantearon las siguientes preguntas:

1. ¿Cómo se distribuyen las edades de los estudiantes incluidos en el conjunto de datos?
2. ¿Cómo se distribuyen los ingresos mensuales de los estudiantes?
3. ¿Qué categorías concentran el mayor gasto promedio?
4. ¿Existen diferencias en los ingresos promedio según el año de cursada?
5. ¿Se observan diferencias en los ingresos promedio según el género?

Alcance del análisis

El análisis se realizó sobre un conjunto de 499 registros y 17 variables, luego del proceso de limpieza y preparación de los datos.

Las visualizaciones permiten explorar tendencias y diferencias dentro de la muestra analizada. Los resultados son descriptivos y no permiten establecer relaciones causales ni generalizar automáticamente las conclusiones a toda la población universitaria.
## Dataset

Se trabajó con un conjunto de datos de 499 registros y 18 columnas originales. Luego de revisar la información, se eliminó la columna Unnamed: 0, ya que funcionaba como un índice consecutivo y no aportaba información relevante. El dataset limpio quedó compuesto por 499 filas y 17 variables.

## Limpieza y preparación

Se realizó una auditoría de calidad de datos. No se encontraron valores nulos ni filas duplicadas. También se analizaron posibles valores atípicos mediante el método del rango intercuartílico (IQR), sin detectar casos que requirieran eliminación.

## Análisis exploratorio

Se realizaron cinco visualizaciones en Python para analizar la distribución de edades e ingresos, los gastos promedio por categoría y las diferencias de ingresos según el año de cursada y el género.

Entre los resultados observados, la categoría tuition presentó el mayor gasto promedio. El grupo freshman registró el mayor ingreso promedio según el año de cursada, mientras que non binary presentó el mayor promedio según el género.

## Dashboard

Se desarrolló un dashboard interactivo en Power BI con indicadores de edad promedio, ingreso mensual promedio y ayuda financiera promedio. También se incorporaron gráficos y filtros por género, carrera y año de cursada.

## Limitaciones

El conjunto de datos contiene 499 registros, una cantidad inferior al tamaño recomendado en la consigna. Además, la fuente no especifica claramente la moneda ni el período de referencia de todos los importes, por lo que los resultados se interpretan con cautela y no se atribuye una moneda específica.

## Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- GitHub



- ## Visualizaciones del análisis

### Distribución de edades
![Edades](data/raw/notebooks/edades.png)

### Distribución de ingresos mensuales
![Ingresos mensuales](data/raw/notebooks/ingresos%20mensuales.png)

### Gasto promedio por categoría
![Gastos por categoría](data/raw/notebooks/gastos%20x%20categoria.png)

### Ingreso promedio según año de cursada
![Ingreso según cursada](data/raw/notebooks/ingreso%20promedio%20segun%20cursada.png)

### Ingreso promedio según género
![Ingreso según género](data/raw/notebooks/ingreso%20segun%20genero.png)




## Dashboard de Power BI

El proyecto incluye un dashboard desarrollado en Power BI, con indicadores, gráficos y filtros por género, carrera y año de cursada.

[Ver dashboard completo en PDF](data/raw/notebooks/dashboard/dashboard_tp_finalpdf.pdf)



Conclusión final

A partir del análisis realizado, fue posible explorar el comportamiento económico de los estudiantes universitarios, identificando patrones en sus ingresos y gastos, así como diferencias entre distintos grupos de la muestra.

Los resultados permitieron observar que los gastos asociados a la matrícula (tuition) representan una de las categorías con mayor promedio de gasto, lo que destaca la importancia de los costos educativos dentro de la economía estudiantil. Asimismo, se identificaron diferencias en los ingresos promedio según el año de cursada y el género, aspectos que permiten profundizar en la diversidad de situaciones económicas presentes en la población analizada.

Este proyecto permitió aplicar distintas etapas del proceso de análisis de datos: recopilación, limpieza, transformación, exploración y visualización de la información. La utilización de herramientas como Python, Pandas, Google Colab y Power BI facilitó la organización de los datos y la comunicación de los resultados mediante representaciones gráficas.

En conclusión, el análisis demuestra el valor de los datos como herramienta para comprender distintas realidades económicas y generar información que permita reflexionar sobre la situación financiera de los estudiantes universitarios. Si bien los resultados corresponden únicamente a la muestra estudiada y no permiten generalizar a toda la población, constituyen un punto de partida para futuras investigaciones más amplias y detalladas.



El repositorio se organiza en los siguientes directorios:

📁 TP FINAL
 ├── 📁 data
 │    ├── 📁 raw
 │    └── 📁 processed
 ├── 📁 notebooks
 ├── 📁 dashboard
 ├── 📁 images
 └── 📄 README.md

Esta organización permite mantener separados los datos originales, los archivos procesados, el desarrollo del análisis y los resultados visuales.



## Datos del proyecto

- *Autora:* [Maria Gabirondo]
- *Curso:* [Herramientas Basicas para el Analisis de Datos]
- *Cohorte:* [Sep-Nov 2026]
- *Fuente del dataset:* [Kaggle.com]
