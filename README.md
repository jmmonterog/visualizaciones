## Visualizaciones de PEC2 Estudio de técnicas de visualización de datos

Repositorio que contiene las visualizaciones realizadas por el alumno Jesús Manuel Montero Garrido correspondientes a la PEC2, Estudio de técnicas de visualización de datos, de la asignatura Visualización de datos del master  Máster Universitario en Ciencia de Datos

## Descripción

El objetivo de este documento es describir la PEC2 “Estudio de técnicas de visualización de datos” de la asignatura Visualización de datos, asignatura del Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. 

La PEC consiste en la realización de tres visualizaciones utilizando estas tres técnicas:

*	**Diagrama de dispersión scatterplot** (https://datavizproject.com/data-type/scatter-plot/)
*	**Slope chart** (https://datavizproject.com/data-type/slope-chart/)
*	**Hyperbolic Trees** (https://datavizproject.com/data-type/hyperbolic-tree/)

## Diagrama de dispersión scatterplot

* **Descripción**

Un gráfico de dispersión es un tipo de diagrama matemático que utiliza coordenadas cartesianas para mostrar los valores de dos variables de un conjunto de datos. Los datos se muestran como una colección de puntos, cada uno de los cuales tiene el valor de una variable que determina la posición en el eje horizontal y el valor de la otra variable que determina la posición en el eje vertical.

* **Usos de esta técnica**

El diagrama de dispersión se usa comúnmente para mostrar cómo dos variables se relacionan entre sí. De este modo, permite estudiar las relaciones que existen entre dos factores, problemas o causas relacionadas con la calidad, o un problema de calidad y su posible causa.
![image](https://user-images.githubusercontent.com/103445965/204878816-c2d62f70-90a0-4e41-afcd-8a6012b2d325.png)

Los datos para esta técnica de visualización deben ser cuantitativos, o sea, valores numéricos. 

Las principales limitaciones consiste en el gran número de puntos que se pueden obtener al contener los datos de entrada muchos conjuntos.

* **Tipo de dato utilizado**

Los datos proceden de *Informe meteorológico Diario CARM. Año 2020* obtenidos del portal datos.gob.es. Información sobre los datos meteorológicos diarios por ejercicio natural. Se incluye la información por cada una de las estaciones meteorológicas de la red SIAM gestionada por el Instituto Murciano de Investigación y Desarrollo Agrario y Alimentario (IMIDA).

Dirección de acceso: https://datos.gob.es/es/catalogo/a14002961-informe-meteorologico-diario-carm-ano-2020

En particular, se han seleccionado las variables de temperatura media y evapotranspiración. La evapotranspiración se define como la pérdida de humedad de una superficie por evaporación directa junto con la pérdida de agua por transpiración de la vegetación. Se expresa en milímetros por unidad de tiempo. Ambas variables están correlacionadas. 

Para evitar que se tengan muchos datos, se ha incluido in filtro por estaciones.
 
* **Visualización realizada**

La visualización está publicada en el Perfil de Tableau del alumno, disponible.

En concreto, se encuentra en:

https://public.tableau.com/app/profile/jes.s.montero6813/viz/scatterplot_16697842612620/Scatterplot

![image](https://user-images.githubusercontent.com/103445965/204886441-81764fc5-5046-4361-88c4-eaa897899fc7.png)


## Slope Chart (gráficos de pendiente)

Es el hermano del gráfico de líneas. Los gráficos de líneas muestran tres o más puntos en el tiempo, mientras que los gráficos de pendientes muestran exactamente dos puntos en el tiempo.

Definido por Edward Tufte en su libro de 1983 The Visual Display of Quantitative Information, este tipo de gráfico es útil para ver 
•	la jerarquía de los países en dos años diferentes
•	las cifras específicas asociadas a cada país en cada uno de esos años 
•	cómo han cambiado las cifras de cada país a lo largo del tiempo 
•	cómo se compara la tasa de cambio de cada país con las tasas de cambio de los demás países 
•	cualquier desviación notable en la tendencia general 

Las principales limitaciones consiste en el gran número de líneas que se pueden obtener al contener los datos de entrada muchos conjuntos.

* **Tipo de dato utilizado**

Los datos proceden de *La estadística de nombres de los recién nacidos*, elaborada por el Instituto Nacional de Estadística (https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736177009&menu=resultados&idp=1254734710990#!tabs-1254736195498). Representa los 100 nombres de niños y los 100 nombres de niñas asignados cada año. Para esta visualización se ha seleccionado el año 2002 y el año 2022. Los datos de entrada para esta visualización están disponibles en la carpeta slopechart.

* **Visualización realizada**

La visualización está publicada en el Perfil de Tableau del alumno, disponible.

En concreto, se encuentra en:

https://public.tableau.com/app/profile/jes.s.montero6813/viz/nombres_bebes/nombres_bebes

![image](https://user-images.githubusercontent.com/103445965/204886329-a89127f1-03e9-41a6-a966-52e4930152d9.png)


