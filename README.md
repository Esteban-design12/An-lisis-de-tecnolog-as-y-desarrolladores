# Análisis de tecnologías, experiencia y adopción de IA entre desarrolladores

**Proyecto de análisis de datos | Portafolio de Data Analyst**

Análisis exploratorio de la encuesta [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/), utilizando Python, Pandas, NumPy y Matplotlib para identificar patrones en las tecnologías utilizadas, la experiencia de los desarrolladores y la adopción de inteligencia artificial.

## Descripción del proyecto

Este proyecto tiene como objetivo analizar las respuestas de la encuesta Stack Overflow Developer Survey 2025 para explorar las principales tecnologías utilizadas por los desarrolladores, su experiencia en programación y sus respuestas sobre el uso de herramientas de inteligencia artificial.

Mediante técnicas de análisis exploratorio de datos (EDA), limpieza, transformación y visualización, se busca convertir los datos de la encuesta en información comprensible que permita identificar tendencias dentro de la comunidad encuestada.

## Objetivos

* Identificar los lenguajes de programación más mencionados.
* Analizar las bases de datos utilizadas por los desarrolladores.
* Examinar la distribución geográfica de los participantes.
* Explorar los años de experiencia en programación.
* Analizar las respuestas sobre la adopción de inteligencia artificial.
* Comparar las respuestas relacionadas con IA entre diferentes grupos de experiencia.

## Herramientas utilizadas

* **Python:** lenguaje utilizado para el análisis.
* **Google Colab:** entorno de desarrollo y ejecución del notebook.
* **Pandas:** manipulación, limpieza y transformación de datos.
* **NumPy:** operaciones numéricas.
* **Matplotlib:** visualización de datos.

## Dataset

**Fuente:** Stack Overflow Developer Survey 2025.

El proyecto utiliza los archivos proporcionados por la encuesta:

* `survey_results_public.csv`: respuestas de los participantes.
* `survey_results_schema.csv`: esquema y descripción de las variables.

Los datos contienen información sobre países, experiencia, roles de desarrollo, lenguajes de programación, bases de datos y respuestas sobre inteligencia artificial.

Los archivos originales pueden obtenerse desde el [sitio oficial de la encuesta](https://survey.stackoverflow.co/2025/).

## Metodología

El análisis se desarrolló mediante las siguientes etapas:

1. **Carga de datos:** importación de los archivos CSV en Google Colab utilizando Pandas.
2. **Exploración inicial:** revisión de dimensiones, columnas, tipos de datos y valores faltantes.
3. **Selección de variables:** elección de las columnas relevantes para responder las preguntas del proyecto.
4. **Limpieza y transformación:** preparación de las variables, separación de respuestas múltiples y conversión de los años de experiencia a valores numéricos aproximados.
5. **Análisis exploratorio:** cálculo de frecuencias, porcentajes y estadísticas descriptivas.
6. **Visualización:** creación de gráficas para facilitar la identificación e interpretación de patrones.
7. **Conclusiones:** síntesis de los principales hallazgos y reconocimiento de las limitaciones del análisis.

## Principales preguntas de análisis

* ¿Cuáles son los lenguajes de programación más mencionados?
* ¿Qué bases de datos tienen mayor presencia entre los participantes?
* ¿Qué países registran más respuestas?
* ¿Cómo se distribuyen los desarrolladores según su experiencia?
* ¿Qué patrones se observan en las respuestas sobre el uso de IA?
* ¿Existen diferencias en las respuestas sobre IA según la experiencia?

## Principales hallazgos

A partir de la exploración realizada en el proyecto, se identificaron los siguientes resultados:

* **Lenguaje de programación:** JavaScript fue el lenguaje con mayor número de menciones en los datos analizados.
* **Base de datos:** PostgreSQL registró la mayor cantidad de menciones.
* **Participación geográfica:** Estados Unidos fue el país con mayor número de respuestas.
* **Adopción de IA:** las respuestas muestran una presencia importante del uso diario de IA entre los participantes. En la revisión inicial, la proporción de quienes planean comenzar a utilizarla próximamente se estimó cercana al 5 %; esta cifra debe contrastarse con la categoría exacta y la tabla de resultados antes de considerarse definitiva.

Estos hallazgos describen las respuestas de los participantes y no deben interpretarse como una representación estadística de todos los desarrolladores del mundo.

## Visualizaciones

El notebook incluye visualizaciones relacionadas con:

* Los lenguajes de programación más mencionados.
* Las bases de datos más utilizadas.
* Los roles de los desarrolladores.
* La distribución de los participantes por país.
* Los grupos de experiencia en programación.
* Las respuestas sobre adopción de IA y su comparación por experiencia.

> Se pueden agregar aquí imágenes de las gráficas principales para facilitar la consulta de los resultados desde GitHub.

## Conclusiones

El análisis permitió identificar tecnologías destacadas entre los desarrolladores participantes de la encuesta, con JavaScript como el lenguaje con más menciones y PostgreSQL como la base de datos más mencionada. Estados Unidos registró la mayor participación por país dentro de la muestra analizada.

Asimismo, las respuestas sobre inteligencia artificial reflejan su presencia en las actividades de los participantes. El análisis por grupos de experiencia permite explorar diferencias en las respuestas, aunque estas asociaciones no permiten establecer relaciones causales.

Este proyecto permitió aplicar conocimientos de Python, Pandas y Matplotlib en un proceso de análisis exploratorio, desde la preparación de los datos hasta la interpretación de resultados y la comunicación de hallazgos.

## Limitaciones

* La encuesta se basa en respuestas voluntarias y no constituye un censo de desarrolladores.
* Las menciones de tecnologías no representan directamente la demanda laboral ni el nivel de dominio de cada herramienta.
* La presencia de valores faltantes puede hacer que el número de respuestas válidas varíe entre variables.
* Los valores numéricos asignados a ciertas categorías de experiencia son aproximaciones.
* Los resultados son descriptivos y no permiten demostrar causalidad.

## Estructura del repositorio

```text
analisis-stack-overflow-2025/
│
├── notebook/
│   └── Analisis_Stack_Overflow_2025_organizado.ipynb
│
├── images/
│   └── (gráficas principales del análisis)
│
├── README.md
└── requirements.txt
```

## Cómo ejecutar el proyecto

1. Descarga o clona este repositorio.
2. Descarga los archivos CSV de la encuesta desde el sitio oficial de Stack Overflow.
3. Abre el notebook en [Google Colab](https://colab.research.google.com/).
4. Sube los archivos `survey_results_public.csv` y `survey_results_schema.csv` al entorno de Colab, en la ruta que espera el código.
5. Ejecuta las celdas en orden para reproducir el análisis.

## Autor

Proyecto desarrollado como parte de un portafolio de aprendizaje en análisis de datos, con enfoque en tecnología e inteligencia artificial.
