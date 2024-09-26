# PROYECTO "OBSERVATORIO LAFT: ANALÍTICA DE DATOS PARA LA PREVENCIÓN DE LAFT"

## Descripción del Proyecto

Este proyecto aborda el desafío de segmentar los clientes de una entidad financiera que ofrece billeteras digitales, con el objetivo de cumplir con la normativa de prevención de Lavado de Activos y Financiación del Terrorismo (LAFT) según la Circular Básica Jurídica (C.E. 029/14) y la actualización (C.E. 011/22) de la Superintendencia Financiera de Colombia.

### Objetivo

El objetivo principal es desarrollar un modelo de segmentación basado en técnicas de aprendizaje no supervisado, que permita identificar patrones de comportamiento para categorizar a los clientes según el riesgo que representan en términos de LAFT. Esto garantizará la homogeneidad dentro de los segmentos y la heterogeneidad entre ellos, facilitando la detección de operaciones inusuales y el cumplimiento normativo.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

- **_codigo_**: Aquí se encuentra el código utilizado para el análisis.
  - `Codigo_propuesta_inicial.ipynb`: Notebook que contiene el código del avance inicial del proyecto.

- **_datos_**: Esta carpeta contiene una muestra sintética de los archivos fuente utilizados en el análisis. Ojo: Estos archivos no son los utilizados originalmente para el análisis, debido a que, por acuerdos de confidencialidad con la entidad financiera, se acordó no poner a disponibilidad pública los datos utilizados, sin embargo, adjuntamos una muestra sintética de los datos para que puedan identificar su estructura original.
  - `BASE_CUENTAS.csv`: Datos de cuentas de los clientes.
  - `BASE_TRX.csv`: Datos de transacciones realizadas por los clientes.

- **_documentacion_**: Carpeta donde se encuentra el informe final del proyecto.
  - `Informe_Proyecto_ANS.pdf`: Informe que contiene el análisis detallado y las conclusiones.

- **_resultados preliminares_**: Carpeta donde se encuentran los resultados obtenidos de la fase inicial del proyecto.
  - `descriptivos.png`: Imagen con visualizaciones descriptivas de las distribuciones de las variables.
  - `correlograma.png`: Visualización del correlograma entre las variables numéricas.
  - `graficos_dispersion.png`: Imagen con gráficos de dispersión entre las variables con correlación más alta.

## Tecnologías Utilizadas

- **Python**: Para el desarrollo de los modelos y análisis de datos.
- **Bibliotecas de Python**: Scikit-learn, Pandas, Matplotlib, Seaborn, entre otras.

## Instrucciones para Reproducir el Análisis

1. Clonar el repositorio: 
   ```bash
   git clone https://github.com/marloz03/proyecto_ans_grupo22.git
2. Navegar a la carpeta del proyecto:
   ```bash
   cd proyecto_ans_grupo22
3. Ejecutar el notebook Codigo_propuesta_inicial.ipynb para reproducir el análisis. En este paso es crucial que nos haga el requerimiento de los datos completos utilizados en el análisis, ya que por acuerdos de confidencialidad con la entidad financiera, estos no se pueden poner a disponibilidad pública.

## Contribuciones
Este proyecto fue desarrollado como parte de la materia de Aprendizaje no supervisado de la Maestría en Inteligencia Analítica de Datos de la Universidad de los Andes, Colombia. Si tienes alguna sugerencia o encuentras algún problema, por favor abre un issue o envía una pull request.
