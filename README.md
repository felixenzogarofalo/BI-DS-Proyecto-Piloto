# PROYECTO PILOTO DE BUSINESS INTELLIGENCE Y DATA SCIENCE PARA EMPRESA DE VENTA DE SOFTWARE
## ABSTRACT
Propuesta inicial para la creación de procesos de extracción, procesamiento y análisis de datos de negocio haciendo uso de inteligencia de negocio y ciencia de datos junto con la aplicación de algoritmos de aprendizaje automático para la predicción de ventas

## OBJETIVOS
### OBJETIVO GENERAL
Crear un algoritmo predictivo de montos de ventas a ser alcanzados por el equipo de ventas a fin de definir adecuadamente metas para el mismo equipo.
### OBJETIVOS ESPECÍFICOS
●	Extraer datos desde fuentes internas (CRM) y fuentes externas (Banco Central de Chile) y automatizar el proceso de preparación y limpieza para ser utilizados en pasos siguientes.

●	Llevar a cabo un Análisis Exploratorio de Datos para comprender la naturaleza de los datos de entrada e identificar patrones explotables por el algoritmo de predicción.

●	Comparar el rendimiento de diversos modelos predictivos con distintas configuraciones e identificar el que mejor se ajuste al alcance de las metas propuestas.

●	Crear un tablero de visualización utilizando el esquema DAR para mejorar la toma de decisiones relativa al equipo de ventas.

## SOLUCIÓN PLANTEADA
A fin de lograr los objetivos propuestos se siguió una metodología de seis (6) pasos que englobaron el ciclo completo de los datos desde su obtención hasta su uso en el entrenamiento de redes neuronales. Tal y como se mencionó brevemente en la introducción los pasos fueron los siguientes:
1.	Obtener datos de las fuentes principales.
2.	Automatizar el proceso de Extracción, Transformación y Carga de datos.
3.	Realizar un Análisis Exploratorio de Datos.
4.	Ejecutar la ingeniería de características y de modelos predictivos.
5.	Preparar datos para inteligencia de negocios.
6.	Crear un tablero de inteligencia de negocios para el equipo de ventas.
El detalle de cada uno de esos pasos se desglosa a continuación.

## RESUMEN
En el presente trabajo se propone la creación de un algoritmo predictivo utilizando Machine Learning que facilite y mejore la estimación de ventas futuras de la empresa tomando en cuenta factores macroeconómicos del mercado en cuestión y datos históricos de ventas. También se propone la creación de un tablero de inteligencia de negocios que facilite la tarea general de gestión del equipo de trabajo, más allá de la creación del algoritmo, que presente datos útiles y oportunos para la toma de decisiones relacionadas con el equipo V1.

Los resultados obtenidos con el entrenamiento del algoritmo predictivo resultan aceptables en exactitud a fines de establecer metas razonables y oportunas. Al mismo tiempo, gracias al desarrollo de tablero para BI se ha facilitado el análisis de datos por parte de la alta gerencia, quien ahora tiene la intención de invertir en este tipo de desarrollo para otros departamentos.

El procedimiento seguido para lograr la solución planteada fue el siguiente:
1.	Obtener datos de fuentes principales: como base del proceso digital se encuentra la recolección oportuna de datos. Como fuente de datos interna se utilizó el CRM de la empresa. Y como fuente de datos externa se utilizó la página oficial del Banco Central de Chile de donde se tomaron datos de variables macroeconómicas.
2.	Proceso ETL: a fin de limpiar los datos de valores espurios se automatizó el proceso de lectura, tratamiento y guardado en un formato oportuno de las tablas extraídas directamente de las fuentes de información. El proceso ETL fue vertido en un cuaderno de Jupyter para facilitar la documentación y entendimiento a actores futuros.
3.	Análisis Exploratorio de Datos (EDA): en base a los datos previamente tratados se llevó a cabo una exploración más profunda de los datos desde un punto de vista estadístico. Y luego se procedió a buscar patrones útiles con la creación de gráficos e incluso algunos modelos estadísticos. Este paso igualmente quedó plasmado en un cuaderno de Jupyter.
4.	Ingeniería de Características y Modelos: utilizando conocimiento del dominio se procedió a seleccionar y validar las variables a partir de los datos originales, buscando mejorar de esta manera el rendimiento de los algoritmos a ser creados. Finalmente se crearon diversos modelos predictivos, comparando su rendimiento, para seleccionar el de mejor desempeño en el cuaderno de Jupyter. Este modelo será llevado a producción en etapas futuras de desarrollo.
5.	Preparación de Datos para Inteligencia de Negocio: debido a que en los tableros de visualización en necesario mostrar métricas específicas y personalizadas, se procedió a crear un cuaderno de Jupyter específicamente dirigida al pre-procesado de dichas métricas y KPIs de interés para el equipo de ventas.
6.	Creación de Tablero en Power BI: finalmente se creó un tablero siguiendo el esquema DAR (Dashboard - Analysis - Report) para facilitar la inspección y seguimiento de métricas para el equipo de ventas.

Las predicciones obtenidas con el algoritmo creado demostraron capacidad de tomar en cuenta variaciones significativas de ventas, incluso a frecuencia diaria. Esta información facilitará el establecimiento de metas objetivas en función de las condiciones del mercado. Igualmente, el tablero de Power BI para inteligencia de negocios referido al equipo de ventas ha facilitado el seguimiento por parte de la gerencia y se planea repetir el procedimiento para otros departamentos.
