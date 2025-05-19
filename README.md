# EDA-IngenioProvidencia-G4


## Cristian Camilo Cardona
## Juan Ordoñez Jimenez
## Santiago Jose Belalcazar

### Contexto 

El Ingenio Providencia cuenta con un conjunto de datos históricos que recoge información relevante sobre la producción de caña de azúcar. Este taller tiene como objetivo que ustedes, como estudiantes, apliquen los conocimientos adquiridos en el curso para desarrollar modelos que permitan desarrollar las siguientes tareas.

Objetivo de negocio: Construir y validar un modelo de IA para predecir o bien la variable porcentaje de sacarosa en caña de azúcar o bien las  Toneladas de caña por hectárea (TCH)

A continuación encuentra una Base de Datos desde el año 2017 con datos asociados a las variables mas importantes para un ingenio (TCH y sacarosa). La idea en este laboratorio es avanzar en el análisis exploratorio (EDA) para explorar el conjunto de datos, limpiarlo y dejarlo listo para ingesta de  modelos de IA con el objetivo de  hacer predicciones mencionadas.
 

1. Regresión (HISTORICO_SUERTES.xlsx): Predecir dos variables clave:

Toneladas de caña por hectárea (TCH): Indicador de la productividad de la tierra.

Porcentaje de sacarosa (%Sac.Caña): Medida de la calidad de la caña y la cantidad de azúcar extraíble.

 

2. Clasificación (BD_IPSA_1940.xlsx): A partir de las variables continuas (TCH y %Sac.Caña), crear categorías que permitan clasificar los registros en niveles de desempeño:

Para %Sac.Caña: Niveles de sacarosa alto, medio y bajo.

Para TCH: Niveles alto, medio y bajo.

La correcta predicción y categorización de estas variables le permitirá al ingenio tomar decisiones más informadas y eficientes en términos de planificación y manejo de cultivos.

Instrucciones Generales


1. Análisis Exploratorio de Datos (EDA):


2. Modelo de Regresión
Realizar una exploración inicial del conjunto de datos: identificar variables relevantes, detectar valores faltantes y posibles outliers

Visualizar la distribución de las variables de interés (TCH y %Sac.Caña).

 3. Modelo de clasificación

Creación de Categorías:

Definir umbrales para transformar las variables continuas TCH y %Sac.Caña en categorías: alto, medio y bajo. Justificar la metodología empleada para definir estos cortes (por ejemplo, percentiles, criterios de negocio, etc.).




Criterios de Evaluación

Claridad y Rigor en el Análisis:

Presentación concisa, clara y  ordenada del EDA.

Justificación de las decisiones tomadas durante la transformación y preprocesamiento de datos.


Entregable EDA: En grupos de exclusivamente tres o cuatro estudiantes deben entregar un reporte en PDF con los nombres de los integrantes. En esta primera parte no deben entregar modelos ajustados, deben entregar sólo el EDA, una descripción detallada del proceso  que llevaron a cabo y el análisis preparatorio de los datos para ser entregados a los modelos. 


### Entregable 2: Modelos de regresion y clasificacion

Entregable Modelos: En grupos de exclusivamente tres o cuatro estudiantes deben entregar un reporte en PDF (no mas de cuatro páginas) con los nombres de los integrantes. En esta segunda parte deben entregar la descripción de al menos tres modelos distintos ajustados,  el reporte debe tener una comparación detallada de las métricas,  una de ellas debe ser kappa, una explicación de la elección de estas, debe hacer una selección de los mejores hiperparámetros de cada uno de los modelos, debe elegir el mejor modelo con base en algún criterio fundamentado y finalmente debe hacer un análisis de sus resultados en el contexto de negocio.

Nota: el notebook fue actualizado con los modelos 