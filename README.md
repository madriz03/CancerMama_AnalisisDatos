###  Analizando datos del programa SEER DEL NCI sobre el Cáncer de Mama

Autor: Javier Madriz  
Fecha: 20 de Junio de 2023

### Proposito
El objetivo principal de este proyecto es realizar un análisis exhaustivo de los datos relacionados con el cáncer de mama, con el fin de identificar posibles relaciones entre las variables y determinar si existe una influencia directa de una variable sobre otra. Este análisis es crucial para comprender mejor los factores que pueden tener un impacto significativo en el desarrollo y tratamiento del cáncer de mama, y proporcionar información valiosa para futuros estudios y esfuerzos de prevención.

Además, buscamos descubrir conocimientos e insights esperanzadores a través del análisis de los datos. Queremos explorar patrones y tendencias que puedan revelar casos de éxito en la lucha contra el cáncer de mama. Es importante destacar que, aunque esta enfermedad ha cobrado muchas vidas, también existen numerosos casos de pacientes que han vencido la enfermedad. Nuestro objetivo es determinar cuál de los dos estatus (sobrevivientes o fallecidos) prevalece y analizar los factores asociados que pueden influir en estos resultados.


A lo largo de este proyecto, realizaremos un análisis detallado de los datos disponibles, aplicaremos diversas técnicas de visualización y modelado de datos, y extraeremos conclusiones significativas que podrán utilizarse para futuros estudios y esfuerzos en la lucha contra el cáncer de mama."

Esta versión de la descripción resalta el propósito de analizar las relaciones entre las variables, enfoca la búsqueda de insights esperanzadores y destaca la importancia de comprender tanto las pérdidas como las victorias en la batalla contra el cáncer de mama

### Estructura de archivos
- Data original en el archivo "cancer-de-mama.csv".
- Directorio "df_resultantes" que almacena los archivos exportados como resultado de cada uno de los descubrimientos y que nos parecían relevantes para mostrar en visualizaciones.
- Notebook "data_pacientes_cancer.ipynb", donde se encuentra el análisis exploratorio y las respuestas a las diferentes interrogantes, junto con las gráficas y visualizaciones preliminares.
- El libro de tableau "Visualizaciones" que contiene todas las visualizaciones realizadas con los archivos resultantes. Si no tienes Tableau Desktop, podrás ver los dashboards en Tableau Public.

### Herramientas y tecnologias usadas
- Python
- Pandas
- Matplotlib
- Tableau

### Sobre el dataset
El conjunto de datos se centra en mujeres diagnosticadas con cáncer de mama invasivo entre los años 2000 y 2017. Contiene una amplia gama de información, incluyendo edad, raza, origen étnico, etapa del cáncer, tamaño del tumor, grado y tratamiento del paciente. Estos datos son de gran importancia para la investigación y la toma de decisiones en el ámbito de la salud.

### Preguntas que responde el analisis de datos
* ¿Cuál es la distribución de edades de los pacientes en el conjunto de datos?
* ¿Cuántos pacientes se encuentran en cada grupo de edad?
* ¿Existe alguna correlación entre el tamaño del tumor y el número de ganglios examinados?
* ¿Cuál es la tasa de supervivencia promedio en meses para los pacientes?
* ¿Hay diferencias en la tasa de supervivencia entre pacientes de diferentes razas?
* ¿Existe alguna relación entre el tamaño del tumor y el estado de metástasis?
* ¿Cuántas personas mueren según la edad en nuestro conjunto de datos?
* Hay diferencias significativas en la proporción de supervivientes y fallecidos en diferentes grupos de edad?
* Extiste una relacion o asociacion entre el rango de edad de los pacientes y el status "sobrevivientes y fallecidos"?

Cada una de estas preguntas podran verlas respondidas en el notebook, donde podran observar de que manera se obtuvo la respuesta y la conclusion sobre la misma.

### Visualizaciones
Use Tableau para graficar los insights mas relevantes como resultado obtuvimos 2 dashboards, dentro del notebook tambien se encuentran algunas graficas que hicimos con matplolib para obtener algunas respuestas preeliminares.
- [Dashboard de tendencias y relaciones](http://https://public.tableau.com/views/Visualizaciones_16884777576460/tendencias_ralaciones?:language=es-ES&:display_count=n&:origin=viz_share_link "Dashboard de tendencias y relaciones")
- [Dashboard de la esperanza](hthttps://public.tableau.com/views/Visualizaciones-data-cancer-mama/esperanza_vida?:language=es-ES&:display_count=n&:origin=viz_share_linktp:// "Dashboard de la esperanza")

### Conclusiones
En resumen, se han respondido satisfactoriamente las preguntas y objetivos planteados en el análisis de datos de pacientes con cáncer de mama. Este proceso ha permitido utilizar conocimientos técnicos para abordar un tema relevante en el ámbito de la salud. Es importante destacar que estos resultados son específicos para el conjunto de datos analizado y no representan cifras absolutas a nivel mundial.

Se ha demostrado la existencia de relaciones significativas entre variables como la edad, el tamaño del tumor, el estado de metástasis y el estado vital de los pacientes. Sin embargo, es importante tener en cuenta que existen múltiples variables y preguntas adicionales que podrían abordarse con estos datos, lo que abre la puerta a futuras investigaciones.

En definitiva, este análisis proporciona un punto de referencia valioso para comprender y explorar aspectos relevantes del cáncer de mama. Debe ser considerado como una contribución inicial en un campo amplio y en constante evolución, lo que resalta la importancia de continuar investigando y ampliando nuestro conocimiento en este ámbito de vital importancia para la salud pública.

[![Dashboard de la esperanza](https://public.tableau.com/views/Visualizaciones-data-cancer-mama/esperanza_vida?:language=es-ES&:display_count=n&:origin=viz_share_link "Dashboard de la esperanza")](http://https://public.tableau.com/views/Visualizaciones-data-cancer-mama/esperanza_vida?:language=es-ES&:display_count=n&:origin=viz_share_link "Dashboard de la esperanza")

[![Dasboard tendencias y relaciones](https://public.tableau.com/views/Visualizaciones_16884777576460/tendencias_ralaciones?:language=es-ES&:display_count=n&:origin=viz_share_link "Dasboard tendencias y relaciones")](http://https://public.tableau.com/views/Visualizaciones_16884777576460/tendencias_ralaciones?:language=es-ES&:display_count=n&:origin=viz_share_link "Dasboard tendencias y relaciones")

### Licencias
Es importante destacar que estos datos se comparten bajo la licencia internacional Creative Commons Attribution 4.0, lo que permite su uso y distribución siempre y cuando se cite correctamente la fuente original. En este caso, se cita el conjunto de datos de la siguiente manera:

**Cita:**
JING TENG, 18 de enero de 2019, "Datos de cáncer de mama SEER", puerto de datos IEEE, doi: [https://dx.doi.org/10.21227/a9qy-ph35](https://dx.doi.org/10.21227/a9qy-ph35).