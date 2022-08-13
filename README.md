# PROYECTO PILOTO DE BUSINESS INTELLIGENCE Y DATA SCIENCE PARA EMPRESA DE VENTA DE SOFTWARE
## ABSTRACT
Propuesta inicial para la creación de procesos de extracción, procesamiento y análisis de datos de negocio haciendo uso de inteligencia de negocio y ciencia de datos junto con la aplicación de algoritmos de aprendizaje automático para la predicción de ventas

## RESUMEN
En el presente trabajo se propone la creación de un algoritmo predictivo utilizando Machine Learning que facilite y mejore la estimación de ventas futuras de la empresa tomando en cuenta factores macroeconómicos del mercado en cuestión y datos históricos de ventas. También se propone la creación de un tablero de inteligencia de negocios que facilite la tarea general de gestión del equipo de trabajo, más allá de la creación del algoritmo, que presente datos útiles y oportunos para la toma de decisiones relacionadas con el equipo V1.

Los resultados obtenidos con el entrenamiento del algoritmo predictivo resultan aceptables en exactitud a fines de establecer metas razonables y oportunas. Al mismo tiempo, gracias al desarrollo de tablero para BI se ha facilitado el análisis de datos por parte de la alta gerencia, quien ahora tiene la intención de invertir en este tipo de desarrollo para otros departamentos.

## INTRODUCCIÓN
Vivimos en lo que comúnmente se conoce como la era digital. Un ecosistema superpuesto de tecnologías digitales, cada una de las cuales se basa en las anteriores y cataliza las que vendrán, está transformando no solo nuestras vidas personales y comunitarias, sino también la dinámica de los negocios para organizaciones de todos los tamaños en todas las industrias (Rogers, 2016).
Las tecnologías digitales están transformando no solo 
algún aspecto de la gestión empresarial, sino prácticamente todo aspecto. Están reescribiendo las reglas de los clientes, la competencia, los datos, la innovación y el valor. Responder a estos cambios requiere más que un enfoque fragmentario; exige un esfuerzo integrado total: un proceso de transformación digital integral dentro de la empresa. 
En reconocimiento de la realidad expuesta en las líneas anteriores COMGRAP ha decidido emprender su propio viaje hacia la transformación digital. Esta es sin duda una propuesta ambiciosa y por ello se ha establecido que el proceso sea paulatino, orientado a objetivos estratégicos y, sobre todo, irreversible. La necesidad de volver los procesos de la empresa a ser más orientados a los datos, o Data-Driven, se ha vuelto imperativa en los últimos años, donde ha servido de catalizador el efecto de pandemia sobre el mercado local. De ahí la importancia de que la toma de decisiones se base en hechos medibles, sin dejar de lado la experiencia humana que es de inmenso valor. Sino más bien haciendo una fusión entre ambos (datos y experiencia) que resulte en el beneficio de la organización y sus miembros por individual. 

Como ya se dijo, el proceso de transformación digital de una organización es de por sí una empresa ambiciosa. Y como tal, debe ser abordada de forma adecuada para que no se pierda el impulso inicial y para que la frustración no opaque los logros que puedan obtenerse en etapas tempranas. Es por ello que se ha decidido hacer un estudio de algunas tareas clave de gestión dentro de la empresa que sean especialmente susceptibles a ser mejoradas con el análisis de datos y cuya complejidad resulte adecuada para una primera etapa de implementación. Al poner el foco en optimizar dichas tareas clave, se promueve la obtención de resultados tangibles a la vez que se gana experiencia que resultará útil en las siguientes etapas de implementación.

COMGRAP, empresa en cuestión, es partner de diversas empresas tecnológicas, tales como Autodesk, Adobe, Microsoft y HP. Dichos partners solicitan que sus asociados cumplan con cuotas de ventas mensuales en servicios, software y consumibles. Esto vuelve una tarea vital de gestión la estimación de ventas en meses o trimestres futuros. Y permite identificar la creación de algoritmos de predicción como un objetivo estratégico primario.

En el mismo orden de ideas, y a través de diversas conversaciones con la gerencia de ventas, se ha identificado que muchas de las pérdidas en la gestión del equipo están relacionadas con la falta de información oportuna y actualizada para dar soporte a la toma de decisiones. En el presente contexto, por pérdidas nos referimos a acciones (o falta de acciones) que no resultan en aportes para la cadena de creación de valor. Algunos ejemplos incluyen, pero no se limitan a: la reacción oportuna a eventos que pueden afectar las finanzas (tales como el cambio frente a moneda extranjera o la creación de políticas por parte de estado), el entendimiento de costos de oportunidad frente a fechas claves de marketing, el desempeño individual de vendedores y su gestión de carteras con clientes importantes.

En el pasado, ambos objetivos estratégicos (estimación de ventas e inteligencia de negocio) han sido abordados haciendo uso de herramientas de ofimática como Excel y PowerPoint. En el caso de estimación, se usan los valores de ventas del año anterior para predecir la venta del año actual y se le agrega el valor de varianza del mes correspondiente del año anterior como prospección de crecimiento. En el caso de la inteligencia de negocio está consiste principalmente en la creación de gráficos de Excel y su divulgación está basada en presentaciones de PowerPoint.

La propuesta del presente proyecto busca mejorar el alcance y efectividad de los objetivos estratégicos planteados haciendo uso de la ciencia de datos y la automatización de procesos relacionados con la captura, transformación y carga de dichos datos. Se plantea, por lo tanto:

●	La creación de un algoritmo predictivo que saque provecho de datos externos que definen el mercado mientras se saca provecho del conocimiento interno de los clientes.
●	La creación de un primer tablero de inteligencia de negocio enfocado en presentar de manera práctica y útil la información pertinente a la gestión del equipo de ventas.

Si bien es cierto que los conceptos y tecnologías planteadas no son nuevas para muchas empresas alrededor del mundo, sí que resulta una propuesta innovadora para la organización en cuestión. La respuesta que se formule a la cuestión de la transformación digital, será vital para la supervivencia y competencia de la empresa en años futuros. Por lo tanto, resulta más que adecuado y oportuno el lanzamiento de este proyecto piloto.
El procedimiento seguido para lograr la solución planteada fue el siguiente:
1.	Obtener datos de fuentes principales: como base del proceso digital se encuentra la recolección oportuna de datos. Como fuente de datos interna se utilizó el CRM de la empresa. Y como fuente de datos externa se utilizó la página oficial del Banco Central de Chile de donde se tomaron datos de variables macroeconómicas.
2.	Proceso ETL: a fin de limpiar los datos de valores espurios se automatizó el proceso de lectura, tratamiento y guardado en un formato oportuno de las tablas extraídas directamente de las fuentes de información. El proceso ETL fue vertido en un cuaderno de Jupyter para facilitar la documentación y entendimiento a actores futuros.
3.	Análisis Exploratorio de Datos (EDA): en base a los datos previamente tratados se llevó a cabo una exploración más profunda de los datos desde un punto de vista estadístico. Y luego se procedió a buscar patrones útiles con la creación de gráficos e incluso algunos modelos estadísticos. Este paso igualmente quedó plasmado en un cuaderno de Jupyter.
4.	Ingeniería de Características y Modelos: utilizando conocimiento del dominio se procedió a seleccionar y validar las variables a partir de los datos originales, buscando mejorar de esta manera el rendimiento de los algoritmos a ser creados. Finalmente se crearon diversos modelos predictivos, comparando su rendimiento, para seleccionar el de mejor desempeño en el cuaderno de Jupyter. Este modelo será llevado a producción en etapas futuras de desarrollo.
5.	Preparación de Datos para Inteligencia de Negocio: debido a que en los tableros de visualización en necesario mostrar métricas específicas y personalizadas, se procedió a crear un cuaderno de Jupyter específicamente dirigida al pre-procesado de dichas métricas y KPIs de interés para el equipo de ventas.
6.	Creación de Tablero en Power BI: finalmente se creó un tablero siguiendo el esquema DAR (Dashboard - Analysis - Report) para facilitar la inspección y seguimiento de métricas para el equipo de ventas.


Las predicciones obtenidas con el algoritmo creado demostraron capacidad de tomar en cuenta variaciones significativas de ventas, incluso a frecuencia diaria. Esta información facilitará el establecimiento de metas objetivas en función de las condiciones del mercado. Igualmente, el tablero de Power BI para inteligencia de negocios referido al equipo de ventas ha facilitado el seguimiento por parte de la gerencia y se planea repetir el procedimiento para otros departamentos.

A continuación, se describe el estado del arte en el desarrollo de algoritmos predictivos, haciendo énfasis en el tratamiento de series temporales con el uso de Machine Learning. Con esto mente se establecerán los objetivos específicos de la presente investigación, la solución planteada, los criterios de evaluación establecidos como criterio de éxito y los resultados obtenidos. Finalmente, se ofrecen conclusiones y recomendaciones para desarrollos futuros.
 
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

