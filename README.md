# Visual-A
datasets VA
##README

Tarea2: Insights
Autores: 
	Carlos Moreno Ibargúen 
	Angela Sofía García Vega 

La visualización se encuentra disponible en Observable en el siguiente enlace:
https://beta.observablehq.com/@cuntaquinte/tarea-2-insigths

Requisitos
-https://d3js.org/d3.v5.min.js


md`# Tarea 2. Insigths. Aves de los Parques Ecológicos Distritales Humedales Bogotá, D.C. 
El grupo de monitoreo en biodiversidad de la Secretaría Distrital de Ambiente –SDA, adscrito a la Subdirección de Ecosistemas y Ruralidad, presenta un consolidado de los registros biológicos de aves, producto del monitoreo de biodiversidad realizado a los Parques Ecológicos Distritales de Humedal (PEDH) durante el período de tiempo comprendido entre el 2 de julio de 2015 hasta el 19 de octubre de 2017. En este se incluye información del grupo biológico, localizados en los 15 Parques Ecológicos Distritales de Humedales (PEDH) declarados en el Distrito Capital. Dentro de los resultados obtenidos se tiene para el grupo de aves un total de 15.205 registros, para 119 especies en todos los PEDH del Distrito.

Datos libres disponibles en: http://datos.biodiversidad.co/dataset/4b04f487-712e-4ade-80fb-14e45f32e5f4`

# Objetivos del proyecto:
El proyecto se enmarca pensando en un cliente imaginario de una empresa de Ecoturismo para la ciudad de Bogotá que busca incrementar las visitas a los PEDH y disfrutar de atracciones naturales como lo es la observación de aves. De los diferentes PEDH de la ciudad de Bogotá el más grande y biodiverso es el humedal de La Conejera, por lo que es de interés para nuestro cliente explorar las diferentes especies de aves reportadas en el parque para promocionar su observación como parte de la propaganda ecoturística

# Insigth_1 - Buscar las especies de aves más abundantes en el PEDH La Conejera
##  Explorar las especies de aves observables en el PEDH La Conejera. 
Partimos de un cliente imaginario que tiene una empresa de ecoturismo y pretende fomentar las visitas al Humedal la Conejera mostrando las aves que se pueden observar dentro del parque haciendo uso de observaciones anteriores. Ya que entre las aves algunas son más fáciles o dificiles de observar debido a las diferencias en el número de individuos observables (abundancia) se debe tener en cuenta para la visualización
## What?
Los datos recolectados se encuentran en un dataset estático en forma de tabla con sus correspondientes Items y Atributos. Para la visualización se usaron el atributo especie de tipo categórico no ordenado y el atributo cuantitativo del número de individuos observados (abundancia absoluta).
## Why?
Se pretende analizar la información disponible para descubrir dentro del humedal La Conejera cuales son las especies que fueron observadas un mayor número de veces durante el periodo de recolección de datos. Por lo tanto el target son las especies de aves - Search/Browse.
## How?
Con un gráfico de barras alineado para mostrar el número de individuos observados para cada una de las especies reportadas (147). El gráfico permite seleccionar cada especie para describir en detalle la información del número de individuos reportados


# Insigth_2 - Buscar los géneros de aves más abundantes en el PEDH La Conejera
##  Explorar los géneros de aves observables en el PEDH La Conejera y algunas condiciones para encontrarlas. 
Ya que el interés de nuestro cliente es el de atraer personas para visitar el parque es importante rescatar información adicional para cada una de las especies reportadas. Ya que el número de especies de aves reportadas en La Conejera es de 147 y en la visualización del insight_1 es evidente la complejidad para reportar la totalidad de las especies; y adicionalmente pretendemos informar datos de interés para su búsqueda como lo son datos climáticos o de la metodología de muestreo, la visualización debe ser modificada. Para ello aprovechando la clasificación taxonómica de las diferentes aves se pueden agrupar por géneros taxonómicos definidos por características morfológicas similares 

## What?
Los datos recolectados se encuentran en un dataset estático en forma de tabla con sus correspondientes Items y Atributos. Para la visualización se usó el atributo cualitativo de Género taxonómico y se creó a partir del mismo un atributo cuantitativo de los conteos de las especies de aves reportadas para cada género.
## Why?
La visualización busca analizar los datos disponibles para los diferentes géneros de aves realizando una búsqueda de los datos del humedal La Conejera donde sea posible identificar las diferentes especies asociadas a las características climáticas y de muestreo con que fueron observadas. Para ello el target son las distribuciones del número de especies reportadas por género taxonómico. Analize-Discover Search/Browse Query-Identify.
## How?
Con un gráfico de barras alineado para mostrar el número de especies observados para cada uno de los géneros taxonómicos reportados. El gráfico permite seleccionar cada especie para describir en detalle la información del número de individuos reportados y muestra patrones de clima como soleado o nublado y técnicas de muestreo como transecto (caminar para buscar el ave) o punto de observación (quedarse quieto en un punto donde se puede observar el ave)

# Insight_1 - Visualización 2.  
Cómo el gráfico de barras fue insuficiente para poder visualizar la información suficiente para determinar las aves que fueron observadas en mayor número en La Conejera, se usó un diagrama de burbujas para poder identificar por tamaño las más abundantes.
## Puedes jugar con el gráfico!!!.
Al PASAR el mousse sobre las burbujas de las diferentes especies puedes observar información adicional de su taxonomía y ubicación.
Al hacer CLICK sobre la burbuja observarás datos adicionales sobre el clima en el que fueron observadas.


