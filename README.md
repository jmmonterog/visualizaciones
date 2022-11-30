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

Las principales limitaciones consiste en el gran número de puntos que se pueden obtener al contener los datos de entrada muchos datos.

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

* **Usos de esta técnica**

Definido por Edward Tufte en su libro de 1983 The Visual Display of Quantitative Information, este tipo de gráfico es útil para ver 
•	la jerarquía de los países en dos años diferentes
•	las cifras específicas asociadas a cada país en cada uno de esos años 
•	cómo han cambiado las cifras de cada país a lo largo del tiempo 
•	cómo se compara la tasa de cambio de cada país con las tasas de cambio de los demás países 
•	cualquier desviación notable en la tendencia general 

Las principales limitaciones consiste en el gran número de líneas que se pueden obtener al contener los datos de entrada muchos datos.


* **Tipo de dato utilizado**

Los datos proceden de *La estadística de nombres de los recién nacidos*, elaborada por el Instituto Nacional de Estadística (https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736177009&menu=resultados&idp=1254734710990#!tabs-1254736195498). Representa los 100 nombres de niños y los 100 nombres de niñas asignados cada año. Para esta visualización se ha seleccionado el año 2002 y el año 2022. Los datos de entrada para esta visualización están disponibles en la carpeta slopechart.

* **Visualización realizada**

La visualización está publicada en el Perfil de Tableau del alumno, disponible.

En concreto, se encuentra en:

https://public.tableau.com/app/profile/jes.s.montero6813/viz/nombres_bebes/nombres_bebes

![image](https://user-images.githubusercontent.com/103445965/204886329-a89127f1-03e9-41a6-a966-52e4930152d9.png)

## Hyperbolic Tree  (árboles hiperbólicos)

Un árbol hiperbólico define un método de dibujo de gráficos inspirado en la geometría hiperbólica.


La visualización de datos jerárquicos en forma de árbol sufre de desorden visual, ya que el número de nodos por nivel puede crecer exponencialmente. Para un árbol binario simple, el número máximo de nodos en un nivel n es de 2 exp(n), mientras que el número de nodos para árboles más grandes crece mucho más rápidamente.

Por lo tanto, dibujar el árbol como un diagrama de enlaces de nodos requiere cantidades exponenciales de espacio para su visualización.

Los árboles hiperbólicos emplean el espacio hiperbólico, que intrínsecamente tiene "más espacio" que el espacio euclidiano. Por ejemplo, el aumento lineal del radio de un círculo en el espacio euclidiano incrementa su circunferencia de forma lineal, mientras que el mismo círculo en el espacio hiperbólico aumentaría su circunferencia de forma exponencial. La explotación de esta propiedad permite distribuir el árbol en el espacio hiperbólico de una manera sencilla: si se coloca un nodo lo suficientemente lejos de su padre, éste dispondrá de casi la misma cantidad de espacio que su padre para distribuir sus propios hijos.

![image](https://user-images.githubusercontent.com/103445965/204887790-7387c549-25c6-44d8-98c4-ea1cc5bd68fa.png)


* **Usos de esta técnica**

Se utiliza para representar datos jerarquizados a varios niveles y nos interesa representar esa jerarquía y pueden ser cualitativos y cuantitativos. Si lo representamos en forma de árbol no se obtiene un resultado adecuado pues se desperdicia mucho espacio.

Las principales limitaciones consiste en el gran número de líneas que se pueden obtener al contener los datos de entrada muchos datos.

* **Tipo de dato utilizado**

Los datos proceden del dataset *Hidrantes de protección contra incendios en espacios públicos* correspondiente al año 2020, elaborado por el Cuerpo de Bomberos del Ayuntamiento de Madrid y disponible en el portal datos.gob.es (https://datos.gob.es/es/catalogo/l01280796-hidrantes-de-proteccion-contra-incendios-en-espacios-publicos1). Los hidrantes de protección contra incendios (comúnmente “de bomberos”) son elementos hidráulicos que proporcionan agua directamente de las redes de distribución para abastecer de a los camiones del Servicio de Incendios. En ningún caso estos elementos pueden ser manipulados por personas que no pertenezcan al Servicio de Extinción de Incendios o a personal de conservación de dichos elementos. Estos elementos no pueden proporcionar agua para obras, riego de jardines, eventos o cualquier otro uso particular. Los datos que se proporcionan son de los hidrantes de conservación municipal ubicados en los espacios públicos. Para esta visualización se ha seleccionado el año 2020. Los datos de entrada para esta visualización están disponibles en la carpeta hypertree.

A este conjunto de datos sí que se le ha aplicado una transformación para obtener una estructura d3.hierarchy. La visualización se ha elaborado con la herramienta D3.js y se encuentra disponible en:

http://sectores.aemet.es/hypertree/inline.html

Una captura de pantalla es la siguiente:

![image](https://user-images.githubusercontent.com/103445965/204889819-94c8af8b-ed9a-467a-b3c7-9039e99e0b89.png)




