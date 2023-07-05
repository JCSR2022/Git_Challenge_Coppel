<img src="data/Oferta-de-Trabajo-Coppel.png">


# Challenge Analítica Avanzada e Inteligencia Artificial
Centro de Investigación Coppel

## Problema UNO

El objetivo de este problema es desarrollar un modelo de contactabilidad que asocie una probabilidad de contacto a cada cliente en función de ciertos segmentos horarios. Para resolver este problema, se utilizará el archivo `20210513_Challenge_AA.csv`, que contiene información sociodemográfica y transaccional de los clientes.

# Estrategia para el Problema UNO

El objetivo del problema UNO es desarrollar un modelo de contactabilidad que asocie una probabilidad de contacto a cada cliente en función de ciertos segmentos horarios. Para abordar este desafío y cumplir con los puntos requeridos, se propone la siguiente estrategia utilizando las mejores prácticas de Machine Learning y Data Science:

## Carga y preparación de los datos:
1. Se cargan los datos del archivo "20210513_Challenge_AA.csv" utilizando las bibliotecas de manipulación de datos, como pandas, y se examina su estructura y contenido.
2. Se selecciona el horario de preferencia para trabajar en el modelo y se realiza el filtro adecuado para quedarse únicamente con los registros correspondientes a ese horario.
3. Se realiza una exploración inicial de los datos para comprender la dimensión del nuevo conjunto de datos, incluyendo el número de filas y columnas, los nombres de las variables y una descripción general de los datos.

## Análisis y preparación de los datos:
4. Se realiza un análisis detallado de los datos, incluyendo la identificación del número de observaciones, valores perdidos y valores NA en el conjunto de datos filtrado.
5. Se calculan y se presentan los detalles estadísticos básicos, como el promedio, los percentiles, las desviaciones estándar, los valores mínimos y máximos, y la mediana, con el fin de comprender la distribución y las características de las variables relevantes para el modelo.

## Análisis exploratorio de datos:
6. Se elabora un programa para crear un gráfico que proporcione una estadística general de los datos, visualizando diferentes características relevantes y patrones en el conjunto de datos.
7. Se elabora un programa para crear un gráfico de barras que muestre la frecuencia de las categorías de las variables continuas, lo que permite identificar posibles sesgos o desequilibrios en los datos.

## Análisis de correlaciones:
8. Se realiza un análisis de correlaciones entre las variables para identificar aquellas que sean linealmente dependientes. Se establece un criterio para determinar los niveles altos y bajos de correlación, lo que permite identificar las relaciones más fuertes y descartar variables redundantes.

## Determinación de factores influyentes:
9. Se utilizan diferentes criterios, como el Valor de Información (Information Value) y el Peso de la Evidencia (Weight of Evidence), para determinar los factores influyentes con respecto al objetivo. Se enumera y clasifica estos factores de mayor a menor según su nivel de influencia sobre la variable objetivo.

## Construcción de nuevas variables:
10. Con base en los resultados anteriores, se construyen al menos cinco nuevas variables que posean buen poder predictivo con respecto a la variable objetivo. Estas variables se crean utilizando técnicas como la combinación de variables existentes, la ingeniería de características y la transformación de variables para capturar información relevante.

## Preparación de conjuntos de entrenamiento y validación:
11. Se divide el conjunto de datos en conjuntos de entrenamiento y validación utilizando un porcentaje adecuado para cada conjunto. Se justifica el porcentaje utilizado en función del tamaño del conjunto de datos, el equilibrio de clases y las necesidades específicas del modelo.

## Propuestas de modelos de clasificación:
12. Se elaboran al menos

 tres propuestas de modelos de clasificación utilizando las variables seleccionadas y construidas previamente. Se justifican las propuestas basándose en la relevancia de las variables, la capacidad del modelo para capturar relaciones complejas y la interpretabilidad de los resultados.

## Evaluación de modelos y selección del ganador:
13. Se evalúan las métricas correspondientes en los conjuntos de entrenamiento y validación para cada propuesta de modelo. Se selecciona un modelo ganador en función del rendimiento y la adecuación a los objetivos del problema. Se justifica el uso de las métricas utilizadas y la elección del modelo preferido.

## Implementación del modelo ganador:
14. Se explica cómo se visualiza la implementación del modelo ganador en un entorno de producción. Esto implica considerar aspectos como la escalabilidad, la eficiencia y la facilidad de mantenimiento del modelo en producción.

## Informe ejecutivo:
15. El proyecto se elaborara en jupyter en preparacion como informe tecnico que detalle cada uno de los puntos de la estrategia, desde la carga de datos hasta la presentación de resultados y la implementación del modelo. El informe se entrega en formato PDF e incluye el código utilizado, los resultados obtenidos, las conclusiones y las recomendaciones para futuros desarrollos.

Con esta estrategia, se abordan todos los puntos del problema UNO, siguiendo las mejores prácticas de Machine Learning y Data Science. Se asegura la calidad de los datos, se exploran las relaciones y las características relevantes, se construyen variables predictivas, se entrenan modelos de clasificación y se selecciona el mejor modelo para su implementación. El informe ejecutivo proporciona una visión general de todo el proceso y los resultados obtenidos.
