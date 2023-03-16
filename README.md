# Analisis-datos
Este repositorio contiene el código del proyecto de análisis descriptivo de los datos de multas de circulación.
* [Dataset](#dataset)
* [Exploración](#exploración)
* [Resultados](#resultados)

## Dataset
El conjunto de datos consiste en las multas de circulación que el Ayuntamiento de Madrid tramita cada mes. Se realizó la carga de los datasets correspondientes a los 12 meses del año 2021. Se incluye información sobre la infracción cometida, su gravedad o el lugar donde se denunció.
Las bases de datos abiertas se pueden encontrar en : https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/vgnextoid=fb9a498a6bdb9410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD

## Exploración
* Para la exploración se emplearon las librerías de Phyton: Pandas, Numpy.
* Para la representación gráfica se emplearon gráficos de frecuencias con la librería de matplotlib.

## Resultados

Se realizaron varios análisis que permitieron obtener conclusiones sobre:
* Las horas en las que se registraron mayor número de multas.
* Multas por agente público y calificación (grave,leve, muy grave).
* Denuncias que implicaron retirada de puntos.
* Filtrados para revisar los conductores que rebasaron mayores límites de velocidad.
