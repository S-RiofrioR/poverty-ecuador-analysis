Análisis de la pobreza en Ecuador (2015–2023)

Descripción

Este proyecto realiza un análisis estadístico y econométrico de la pobreza en Ecuador utilizando los microdatos de la Encuesta Nacional de Empleo, Desempleo y Subempleo (ENEMDU). Se enfoca en identificar cómo diversas variables socioeconómicas influyen en la probabilidad de que un hogar se encuentre bajo la línea de pobreza.
Objetivo
Evaluar la incidencia de la pobreza a nivel nacional y regional, identificando los factores críticos (educación, empleo, ubicación geográfica) que determinan los niveles de ingresos en la población ecuatoriana durante los últimos años.

Datos utilizados
Se utilizan las bases de datos oficiales proporcionadas por el Instituto Nacional de Estadística y Censos (INEC):

Fuente: ENEMDU (Bases de datos anuales y trimestrales).

Formatos: .sav (SPSS) procesados en entornos de programación.

Nota: Debido al peso de los archivos originales, estos deben descargarse directamente desde el repositorio de datos del INEC y colocarse en la carpeta /data/raw/.

Herramientas
  Para el procesamiento y modelado de datos se emplearon las siguientes tecnologías:

Lenguaje: Python.
  1. Librerías principales: * tidyverse para manipulación de datos.
     - car y sjPlot para diagnósticos de multicolinealidad y visualización de modelos.
     - ggplot2 para la visualización de indicadores sociales.
  2. Control de versiones: Git y GitHub.

Principales hallazgos
  1. Identificación de la brecha de pobreza entre zonas urbanas y rurales.
  2. Correlación significativa entre el nivel de instrucción del jefe de hogar y el ingreso per cápita.
  3. Análisis de multicolinealidad en variables predictoras de modelos logit/probit.

Cómo ejecutar
Para replicar este análisis en tu entorno local:
1. Clonar el repositorio:
   - git clone https://github.com/S-RiofrioR/poverty-ecuador-analysis.git
   - Preparar los datos: Descargar los archivos .sav de la ENEMDU y guardarlos en la carpeta data/raw/.
   - Ejecutar scripts: Abrir el archivo principal (ej. analisis_pobreza.R o el notebook en Colab) y ejecutar todas las celdas.
