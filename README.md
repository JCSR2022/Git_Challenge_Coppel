# Challenge Analítica Avanzada e Inteligencia Artificial
Centro de Investigación Coppel

## Problema UNO

El objetivo de este problema es desarrollar un modelo de contactabilidad que asocie una probabilidad de contacto a cada cliente en función de ciertos segmentos horarios. Para resolver este problema, se utilizará el archivo `20210513_Challenge_AA.csv`, que contiene información sociodemográfica y transaccional de los clientes.

A continuación, se presenta una rutina para abordar este desafío:

1-2. **Carga de los datos del archivo .csv/ Selección del horario de preferenci:** Inicialmente, se debe cargar el archivo "20210513_Challenge_AA.csv" para obtener los datos necesarios. Sin embargo, debido al tamaño del archivo, es necesario dividirlo en sub-archivos más pequeños para llevar a cabo el proceso ETL en cada uno de ellos. Además, se puede aprovechar la necesidad de seleccionar el horario de interés para trabajar con él en el modelo y dividir el archivo en sub-archivos correspondientes a sus respectivos horarios. Esto implica realizar un filtro adecuado para quedarse únicamente con los registros que pertenecen a ese horario.

También se puede considerar el uso de una solución de Big Data como Hadoop Hive si las velocidades de consulta y modificación son un problema. Hadoop Hive ofrece capacidades de procesamiento distribuido y escalabilidad para manejar grandes volúmenes de datos.

Posteriormente, se realizarán los pasos comunes de un proceso ETL estándar, que incluyen la detección de valores nulos, la detección de registros duplicados y la detección de valores atípicos (outliers). Estos pasos implican registrar los cambios realizados en un archivo llamado "registro_cambios.csv", donde se indicarán los valores modificados y se describirá el cambio realizado.

Es importante tener en cuenta que estos pasos forman parte de un proceso ETL estándar, pero la implementación exacta puede variar según el contexto y los requisitos específicos de los datos.

3-15. **Indica la dimensión del nuevo fichero, número de filas y columnas, nombres de las
variables y descripción de los datos, Obtén el número de observaciones, valores perdidos, valores NA, Expresa los detalles estadísticos básicos: promedio..**

