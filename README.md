# Airbnb Buenos Aires

![Cover Image](cover.jpeg)
#### https://www.lavanguardia.com/magazine/viajes/20220901/8477587/buenos-aires-septiembre-tango.html#foto-2 (Buenos Aires, Argentina AdonisVillanueva / Terceros)

## Descripción

En este proyecto hemos analizado los datos relativos a la ciudad de Buenos Aires con respecto a Airbnb, los cuales hemos sacado de [la web Inside](http://insideairbnb.com/buenos-aires/) y que se encontraban actualizados a fecha 23/10/23.

## Objetivo

 El objetivo que buscábamos era analizar los alojamiento, precios, barrios y fechas de cara a un viaje para dos personas, viendo cuál sería el mejor barrio, la fechas más interesantes, la seguridad en sus zonas...

 ## Tratamiento

Importamos todas las librerías que vamos a emplear y con ello comenzamos.
Con los csv descargados hemos procedido a su lectura, elección de variables para analizar y posteriormente hemos unido todos los csv en un solo DataFrame con el que trabajar.
Se ha eliminado la columna que no vamos a usar debido a la cantidad de no nulos que tiene y no nos es útil para nuestro análisis en particular. Después de esto se han eliminado el barrio de Paternal, debido a que nos desvirtuaba los datos, y a transformar el precio de dólares argentinos a euros, ya que es lo que se necesitaba para este proyecto.

## Análisis

Una vez realizado todo lo anterior, comenzamos con el análisis de los vecindarios y donde encontramos mayor número de alojamientos y su ubicación, tipos de propiedades y habitaciones y por último el número de alojados.

Después de este análisis hemos querido buscar los potenciales hoteles ilegales y la influencia que pueden tener los posibles anfitriones profesionales en el precio y si se dan situaciones fuera de la normativa marcada por la plataforma.

Teniendo todo lo mencionado procedemos a hacer un analisis más en profundidad de cara al turismo con datos sobre el precio medio por vecindario, su seguridad, las valoraciones, disponibilidad de los alojamientos...

Todo lo anterior lo hemos acompañado de diferentes gráficas y mapras interactivos en los que poder visualizar de mejor manera lo extraído de los datos.

## Cierre de nuestro análisis

Hemos querido acabar con una minería de datos sobre las reseñas de los húespedes de manera que se pueda ver más fácil las palabras más repetidas.

## Aplicación interactiva

En éste proyecto también hemos querido aportar valor al trabajo desarrollado añadiendo una app interactiva realizada mediante Streamlit donde se pueden seleccionar diferentes parámetros y nos va facilitando datos con respecto a ellos.

https://airbnb2-buenos-aires.streamlit.app/
