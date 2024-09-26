# PROYECTO "OBSERVATORIO LAFT: ANALÍTICA DE DATOS PARA LA PREVENCIÓN DE LAFT"

## Descripción del Proyecto

El proyecto aborda el desafío de clasificar a los clientes de una entidad financiera colombiana que ofrece billeteras digitales, con el fin de cumplir con las regulaciones de prevención de Lavado de Activos y Financiación del Terrorismo (LAFT). Estas normativas exigen que los clientes sean agrupados en función de factores de riesgo, de manera que los grupos resultantes sean homogéneos interna y claramente diferenciados entre sí. Este proceso es clave para identificar comportamientos inusuales en las transacciones financieras.

### Objetivo

El objetivo principal es desarrollar un modelo de segmentación basado en técnicas de aprendizaje no supervisado, que permita identificar patrones de comportamiento para categorizar a los clientes según el riesgo que representan en términos de LAFT. Esto garantizará la homogeneidad dentro de los segmentos y la heterogeneidad entre ellos, facilitando la detección de operaciones inusuales y el cumplimiento normativo.

## Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

- **_1_Datasets_**: Esta carpeta contiene una muestra sintética de los archivos fuente utilizados en el análisis. Ojo: Estos archivos no son los utilizados originalmente para el análisis, debido a que, por acuerdos de confidencialidad con la entidad financiera, se acordó no poner a disponibilidad pública los datos utilizados, sin embargo, adjuntamos una muestra sintética de los datos para que puedan identificar su estructura original.
  - `BASE_CUENTAS.csv`: Datos de cuentas de los clientes.
  - `BASE_TRX.csv`: Datos de transacciones realizadas por los clientes.

- **_2_Código_**: Aquí se encuentra el código utilizado para el análisis.
  - `Codigo_propuesta_inicial.ipynb`: Notebook que contiene el código del avance inicial del proyecto.

- **_3_Documento_del_Proyecto_**: Carpeta donde se encuentra el informe final del proyecto.
  - `Informe_Proyecto_ANS.pdf`: Informe que contiene el análisis detallado y las conclusiones.

- **_4_Resultados_preliminares_**: Carpeta donde se encuentran los resultados obtenidos de la fase inicial del proyecto.
  - `1_VARIANZA_EXPLICADA.jpg`: Imagen con el análisis de la varianza explicada para la selección de los componentes.
  - `2_RESULTADOS_KNN.jpg`: Resultados del KNN para cálculo del eps con el corte correspondiente.
  - `3_SEGMENTACIÓN_DBSCAN`: Imagen en 2D que permite observar los clústeres generados y el ruido.
  - `4_SEGMENTOS_DBSCAN`: Imagen animada que permite observar los diferentes clústeres generados y el ruido.
  - 
## Tecnologías Utilizadas

- **Python**: Para el desarrollo de los modelos y análisis de datos.
- **Bibliotecas de Python**: Scikit-learn, Pandas, Matplotlib, Seaborn, entre otras.

## Instrucciones para Reproducir el Análisis

1. Clonar el repositorio: 
   ```bash
   git clone https://github.com/CBERAUN/ENTREGA_FINAL_ANS_TEAM22.git
2. Navegar a la carpeta del proyecto:
   ```bash
   cd ENTREGA_FINAL_ANS_TEAM22
3. Ejecutar el notebook Codigo_propuesta_inicial.ipynb para reproducir el análisis. En este paso es crucial que nos haga el requerimiento de los datos completos utilizados en el análisis, ya que por acuerdos de confidencialidad con la entidad financiera, estos no se pueden poner a disponibilidad pública.

## Contribuciones
Este proyecto fue desarrollado como parte de la materia de Aprendizaje No Supervisado de la Maestría en Inteligencia Analítica de Datos de la Universidad de los Andes, Colombia. Si tienes alguna sugerencia o encuentras algún problema, por favor abre un issue o envía una pull request.
