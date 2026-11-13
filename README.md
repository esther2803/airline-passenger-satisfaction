# **<u>README</u>** 

## **1.** **<u>TÍTULO DEL PROYECTO</u>** 

✈️� Airline Passenger Satisfaction 

Análisis de datos sobre la satisfacción de los pasajeros de una aerolínea. 

## **2.** **<u>DESCRIPCIÓN DEL PROYECTO</u>** 

Este proyecto tiene por objetivo analizar los datos relacionados con la satisfacción de los pasajeros de una aerolínea, con el fin de identificar los principales factores que influyen en su experiencia del cliente. 

Para ello, se ha utilizado una base de datos obtenida de Kaggle denominada Airline Passenger Satisfaction (https://www.kaggle.com/datasets/mysarahmadbhat/airline-passenger-satisfaction). Dicha base de datos contiene información de 129.880 pasajeros y 24 variables relacionadas con características personales, el tipo de viaje, los retrasos de los vuelos, las valoraciones de los servicios ofrecidos y el nivel de satisfacción de los pasajeros. 

El análisis se ha realizado usando Microsoft Excel, utilizando datos estadísticos, tablas dinámicas y gráficos para explorar los datos e identificar posibles patrones y áreas de mejora. 

## **3.** **<u>ESTRUCTURA DEL PROYECTO</u>** 

El proyecto está organizado en los siguientes archivos: 

- Airline Passenger Satisfaction.xlsx: archivo Excel que contiene el conjunto de datos original, los datos una vez procesados, el análisis exploratorio de datos y el Dashboard. 

- DatosOriginales_AirlinePassengerSatisfaction.xlsx: donde se encuentran los datos originales de la base de datos. 

- README.md: archivo que presenta el proyecto, describe su estructura y resume sus principales aspectos. 

## **4.** **<u>INSTALACIÓN Y REQUISITOS</u>** 

Para consultar y trabajar con los datos del proyecto, es necesario disponer de: 

- Microsoft Excel: para abrir el conjunto de datos, consultar las tablas dinámicas y explorar el dashboard. 

- - Microsoft Word o programa compatible: para visualizar los documentos del análisis descriptivo y del informe explicativo. 

- Un editor de texto: para abrir y consultar el archivo README. 

## **5.** **<u>RESULTADOS Y CONCLUSIONES</u>** 

El análisis realizado ha permitido identificar varios aspectos relevantes sobre la satisfacción de los pasajeros: 

- El 56,55% de los pasajeros se consideran neutrales o insatisfechos, frente al 43,45% que está satisfecho. 

- Los servicios mejor valorados son el servicio a bordo y la gestión del equipaje, mientras que el wifi a bordo y la facilidad de reserva online obtienen las puntuaciones más bajas. 

- Se observan mayores niveles de satisfacción entre los pasajeros que viajan en clase Business, por motivos de trabajo y entre los clientes recurrentes. 

- Las valoraciones de los servicios son, en general, superiores entre los pasajeros satisfechos, especialmente en aspectos como el embarque online, el entretenimiento y la comodidad de los asientos. 

Estos resultados permiten identificar oportunidades de mejora para la aerolínea, especialmente en los servicios con valoraciones más bajas y en la experiencia de los pasajeros que viajan por primera vez. 

## **6.** 

## **<u>PRÓXIMOS PASOS</u>** 

A partir de los resultados obtenidos, se planten las posibles líneas de mejora y análisis de futuro: 

- Investigar posibles soluciones para mejorar la calidad del wifi a bordo y la facilidad de reserva online. 

- Analizar los motivos por los que la categoría Economy Plus presenta una demanda inferior a las otras clases. 

- Investigar las causas de los menores niveles de satisfacción entre los pasajeros que viajan por primera vez con la aerolínea. 

- Realizar un seguimiento de las valoraciones de los servicios para comprobar si las medidas de mejora tienen un impacto positivo en la satisfacción de los pasajeros. 

## **7.** **<u>CONTRIBUCIONES</u>** 

Este proyecto se ha realizado con fines académicos por lo que, no se contemplan contribuciones externas en su elaboración. 

## **8.** **<u>AUTORES Y AGRADECIMIENTOS</u>** 

Autora: Esther Fernández López 

Proyecto desarrollado en el marco del programa formativo ThePowerMBA, dentro del área de Big Data e Inteligencia Artificial. 

Se agradece a Kaggle la colaboración del conjunto de datos utilizado para la realización de este análisis. 

# **<u>INFORME DEL ANÁLISIS</u>** 

Proyecto: Airline Passenger Satisfaction 

## **1.** **<u>INTRODUCCIÓN</u>** 

El análisis descriptivo presentado tiene como objetivo analizar los datos de satisfacción de los pasajeros de una aerolínea con el fin de identificar qué factores pueden estar relacionados con su experiencia de viaje y su nivel de satisfacción. 

A través de este análisis, se pretende conocer el perfil de los pasajeros, las características de sus respectivos viajes, las valoraciones que realizan a los diferentes servicios de la compañía y el nivel de satisfacción general. 

Adicionalmente, se pretende identificar patrones y relaciones entre las distintas variables, detectar aquellos aspectos que están sido mejor valorados para así, obtener conclusiones que puedan ayudar a la aerolínea a conocer mejor las necesidades de sus clientes e identificar posibles áreas de mejora. 

## **2.** **<u>DESCRIPCIÓN DEL CONJUNTO DE DATOS</u>** 

Para la realización de este proyecto, se ha utilizado un conjunto de datos obtenido de la plataforma Kaggle, denominado Airline Passenger Satisfaction. En el Excel complementario, DatosOriginales_AirlinePassengerSatisfaction, podréis observar los datos originales antes del análisis, limpieza y transformación. 

Dicho conjunto de datos contiene 129.880 registros correspondientes a pasajeros de una aerolínea y 24 variables. Cada registro dispone de un identificador único (ID) y la variable de trabajo principal objeto de nuestro análisis es la satisfacción. 

Cada registro representa a un pasajero e incluye información acerca de sus características personales, tipo de viaje realizado, la clase en la que ha viajado, la distancia del vuelo, los posibles retrasos y las valoraciones que hacen cada uno de ellos a los distintos servicios de la compañía. Adicionalmente, incorpora una variable de satisfacción general que nos permite clasificar a los pasajeros entre satisfechos y neutrales o insatisfechos. 

Las 24 variables, pueden organizarse de la siguiente manera: 

- Identificación: ID 

- Características del pasajero: Gender, Age, Customer Type 

- Características del viaje: Type of Travel, Class, Flight Distance 

- Retrasos: Departure Delay, Arrival Delay 

- Valoración de servicios: 14 variables de valoración 

- Satisfacción General: Satisfaction 

## **3.** 

## **<u>CLASIFICACIÓN DE LAS VARIABLES</u>** 

- Cualitativas nominales: Gender, Customer Type, Type of Travel, Class, Satisfaction 

- Cuantitativas discretas: Age, Flight Distance, Departure Delay, Arrival Delay 

- Cuantitativas ordinales: las 14 variables de valoración de los servicios (su valoración va de 1 a 5 significando menor o mayor satisfacción). 

## **4.** **<u>PREPARACIÓN, LIMPIEZA Y TRANSFORMACIÓN DE LOS DATOS</u>** 

En primer lugar, se descargó el conjunto de datos desde la plataforma Kaggle en formato CSV y se importó a Microsoft Excel como tabla para poder trabajar con la información. 

Antes de iniciar el análisis, se revisó el diccionario de datos (Data Dictionary) incluido junto al conjunto de datos, con el objetivo de comprender el significado de cada una de las variables, identificar el tipo de dato que representan y comprobar que estuvieran presentadas en el formato adecuado. 

Para mantener los datos originales y evitar modificarlos directamente, se realizaron, en el Excel complementario Airline Passenger Satisfaction, los trabajos en una copia de la hoja denominada «Processed Data». 

Se comprobó la existencia de un identificador único para cada registro mediante el formato condicional, verificando que no hubiera valores duplicados. A su vez, se revisó la existencia de valores nulos o vacíos en cada una de las variables para evaluar la calidad del conjunto de datos y determinar si era necesario aplicar algún tratamiento previo al análisis. 

Se detectaron 393 registros vacíos en la variable Arrival Delay y, para poder trabajar con el conjunto de datos completo, se decidió sustituirlos por 0 minutos, utilizando la moda como criterio de imputación, ya que era el valor más frecuente de la variable. Esta decisión permitió completar los registros, aunque debe tenerse en cuenta que los valores imputados no representan necesariamente vuelos que llegaran sin retraso. 

Por otro lado, se tuvo en cuenta que, en las variables correspondientes a las valoraciones de los servicios, el valor 0 indica que el servicio no era aplicable al pasajero. Por este motivo, estos registros no se consideraron en el cálculo de las medias de valoración, evitando así que influyeran en los resultados obtenidos. 

Finalmente, se crearon columnas adicionales para agrupar los retrasos de salida y llegada en intervalos de minutos. También se utilizaron agrupaciones de edad y distancia para facilitar la comparación de los resultados y su representación mediante tablas dinámicas y gráficos. 

## **5.** **<u>METOLOGÍA DE ANÁLISIS EN EXCEL</u>** 

Una vez tratados los datos, se comenzó el análisis utilizando las herramientas de Microsoft Excel. 

En primer lugar, se realizaron cálculos estadísticos descriptivos para conocer las características principales de las variables cuantitativas, obteniendo medidas como la media, la mediana, la moda, los valores mínimos y máximos y la desviación estándar. 

Para analizar las variables cualitativas y comparar los diferentes grupos de pasajeros, se utilizaron tablas dinámicas, que permitieron obtener recuentos, porcentajes y distribuciones de las distintas categorías. 

Asimismo, se elaboraron gráficos de barras, columnas y sectores para facilitar la interpretación y visualización de los resultados. Estos gráficos permitieron identificar patrones y comparar los niveles de satisfacción según las diferentes características de los pasajeros y de sus vuelos. 

Finalmente, se creó un dashboard interactivo que reúne los principales indicadores y gráficos del análisis. Para facilitar la exploración de la información, se incorporaron segmentaciones de datos, que permiten filtrar los resultados y visualizar las diferencias entre distintos grupos de pasajeros. 

## **6.** **<u>ANÁLISIS DE LAS CARACTERÍSTICAS DE LOS PASAJEROS</u>** 

## **6.1.** **<u>DISTRIBUCIÓN POR GÉNERO</u>** 

Los resultados obtenidos son los siguientes: 

|**Género**|**N.º  Pasajeros**|**%**|
|---|---|---|
|Female|65.899|50,74%|
|Male|63.981|49,26%|
|**Total**||**100,00**|
|**general**|**129.880**|**%**|





<!-- Start of picture text -->
Ma<br>Género de los pasajeros<br>le<br>49<br>Fe<br>%<br>ma<br>le<br>51<br>%<br><!-- End of picture text -->

Podemos observar que la distribución por género es muy equilibrada, con una ligera mayoría de mujeres que representan, tal y como observamos en la tabla dinámica el 50,74% respecto al 49,26% que representan los hombres. 

Esto refleja una distribución muy equilibrada entre ambos géneros. 

## **6.2.** **<u>DISTRIBUCIÓN POR EDAD</u>** 

En cuanto a las principales medidas: 

|**Medida**|**Resultado**|
|---|---|
|**Media**|39,43 años|
|**Mediana**|40,00 años|
|**Moda**|39,00 años|
|**Mínimo**|7,00 años|
|**Máximo**|85,00 años|
|**Desv. Estand**|15,12 años|



Podemos observar que la edad media de los pasajeros es de 39,43 años mientras que la mediana es de 40 años. Ambos valores son muy próximos, lo que indica que la distribución se encuentra bastante centrada alrededor de los 40 años. 

En cuanto a la distribución por rango de edad, es la siguiente: 

|**Rango de Edad **|**N.º Pasajeros**|**%**|||||||||
|---|---|---|---|---|---|---|---|---|---|---|
|||||||**Dist**|**ribu**|**ción**|**por edad**||
|0-9|2.341|1,80%|35,000||||||||
|10-19|9.839|7,58%|30,000||||||||
|20-29|26.179|20,16%|20,000<br>25,000|||||||Nº Pasajeros|
|30-39|25.704|19,79%|15,000||||||||
||||10,000||||||||
|40-49|29.636|22,82%|5,000||||||||
|50-59|23.966|18,45%|0|0-9 10-|20-|30-|40-|50-|60-<br>70-<br>80-||
|6069|10485|807%||19|29|39|49|59|69<br>79<br>89||
|-|.|,|||||||||
|70-79|1.595|1,23%|||||||||
|80-89|135|0,10%|||||||||
|**Total general**|**129.880 **|**100,00%**|||||||||



El intervalo con mayor representación es el de 40-49 años, que concentra el 22,82%, seguido del intervalo de 20-29 años con un 20,16%. Podemos observar que la mayor concentración está entre ellos 20 y los 49 años y que a partir de los 70 años, tienen una representación mucho menor. 

## **6.3.** **<u>DISTRIBUCIÓN POR TIPO DE CLIENTE</u>** 

Aquí distinguimos entre pasajeros que ya habían viajado anteriormente con la aerolínea y viajeros para los que era su primera vez. 

|**Tipo de cliente**|**N.º Pasajeros**|**%**||**Tipo de Cliente**|First<br>-|
|---|---|---|---|---|---|
|First-time|23.780|18,31%|Ret||time<br>18%|
|Returning|106.100|81,69%|urni<br>ng|||
|**Total general**|**129.880 **|**100,00%**|82%|||



Viendo el gráfico, podemos observar que la mayoría de los pasajeros son clientes recurrentes representando un 81,69% frente al 18,31% que viaja por primera vez. 

Esta distribución muestra que existe un claro predominio de los pasajeros que ya habían utilizado anteriormente los servicios de la aerolínea. 

## **7.** **<u>ANÁLISIS DE LAS CARACTERÍSTICAS DEL VIAJE</u>** 

## **7.1.** **<u>DISTRIBUCIÓN POR MOTIVO DEL VIAJE</u>** 

En este apartado analizamos si los pasajeros viajan por motivos de negocios o por motivos personales. 

||||P|B|
|---|---|---|---|---|
||||e|u|
|**Motivo del**<br>**viaje**|**N.º Pasajeros**|**%**|r<br>s<br>o<br>**Motivo del viaje**|s<br>i<br>n|
||||n|e|
|Business|89.693|69,06%|a|s|
|Personal|40.187|30,94%|l<br>3|s<br>6|
||||1|9|
|**Total general**|**129.880 **|**100,00%**|%|%|



Podemos observar que la mayoría de los pasajeros viajan por motivos laborales en un 69,06% frente a un 30,94% que lo hacen por motivos personales, lo que refleja un predominio en los viajes laborales. 

## **7.2.** **<u>DISTRIBUCIÓN POR CLASE</u>** 

En este apartado analizaremos cómo se distribuyen los pasajeros según la clase en la que han viajado. 

||||E<br>c||
|---|---|---|---|---|
||**N.º**||o<br>n|B<br>E<br>**Clase del viaje**|
|**Clase**|**Pasajeros**|**%**|o<br>m|u<br>si<br>c<br>o|
|Business|62.160|47,86%|y<br>P|n<br>e<br>n<br>o|
|Economy|58.309|44,89%|l<br>u|s<br>s<br>m<br>y|
||||s|4<br>4|
|Economy Plus|9.411|7,25%|7|8<br>5|
||||%|%<br>%|
|**Total general**|**129.880 **|**100,00%**|||



Podemos observar que la clase Business es la que presenta mayor representación con un 47,86% de los pasajeros, seguida muy de cerca de la clase Economy, que representa el 44,89%. 

Por tanto, podemos determinar que la mayoría de los pasajeros se concentra en la clase Business y Economy ya que conjuntamente, representan el 92,75%. 

## **7.3.** **<u>DISTRIBUCIÓN POR DISTANCIA DEL VUELO</u>** 

En este apartado analizamos las distancias recorridas por los pasajeros, utilizando intervalos de 500 millas. 

|**Medida**|**Resultado**|
|---|---|
|**Media**|1.190,32 millas|
|**Mediana**|844,00 millas|
|**Moda**|337,00 millas|
|**Mínimo**|31,00 millas|



|**Máximo**|4.983,00 millas|
|---|---|
|**Desv. Estand**|997,45 millas|



Podemos observar que la distancia media de los vuelos es de 1.190,32 millas, mientras que la mediana es de 844 millas. La diferencia entre ambos valores indica que existen vuelos de distancias considerablemente superiores que elevan la media. 

En cuanto a la distribución por rango de millas, es la siguiente: 

|**Rango de Millas **|**N.º Pasajeros**|**%**|
|---|---|---|
|31-530|42.647|32,84%|
|531-1030|34.380|26,47%|
|1031-1530|14.480|11,15%|
|1531-2030|11.836|9,11%|
|2031-2530|9.701|7,47%|
|2531-3030|6.801|5,24%|
|3031-3530|5.065|3,90%|
|3531-4030|4.892|3,77%|
|4031-4530|37|0,03%|
|4531-5030|41|0,03%|
|**Total general**|**129.880 **|**100,00%**|



El intervalo con mayor concentración de pasajeros es el de 31 a 530 millas, que representa el 32,84% del total, seguido del intervalo de 531 a 1.030 millas representando el 26,47%. 

En conjunto, el 59,31% de los pasajeros se concentra en vuelos de hasta 1.300 millas, lo que muestra un predominio de los vuelos de más corta distancia. 

## **8.** **<u>ANÁLISIS DE LOS RETRASOS DE LOS VUELOS</u>** 

## **8.1.** **<u>RETRASOS EN LA SALIDA</u>** 

En este apartado, vamos a analizar la variable “Departure Delay” que recoge el retraso de salida de cada vuelo expresado en minutos. 

## **Registros con retraso de salida** 



<!-- Start of picture text -->
Sí<br>No  43,5<br>56,4 2%<br>8%<br><!-- End of picture text -->

En el gráfico vemos que el 56,48% de los vuelos no registraron retrasos en la salida frente a el 43,52% que sí. 

|**Medida**|**Resultado**|
|---|---|
|**Media**|14,71 minutos|



|**Mediana**|0,00 minutos|
|---|---|
|**Moda**|0,00 minutos|
|**Mínimo**|0,00 minutos|
|**Máximo**|1.592,00<br>minutos|
|**Desv. Estand**|38,07 minutos|



En la tabla anterior podemos observar que la media de retraso es de 14,71 minutos, mientras que la mediana y la moda son de 0 minutos. Esto indica que al menos la mitad de los vuelos no registraron retrasos en su salida. 

La diferencia entre la media y la mediana puede explicarse por la existencia de algunos retrasos de larga duración, que elevan el valor medio. 

En cuanto a la distribución por rango de minutos de retraso, es la siguiente: 

|**Intervalo de Retraso en salida **|**N.º Vuelos**|**%**|
|---|---|---|
|0-99|125.505|96,63%|
|100-199|3.406|2,62%|
|200-299|664|0,51%|
|300-399|201|0,15%|
|400-499|61|0,05%|
|500-599|18|0,01%|
|600-699|6|0,00%|
|700-799|7|0,01%|
|800-899|3|0,00%|
|900-999|5|0,00%|
|1000-1099|1|0,00%|
|1100-1199|1|0,00%|
|1300-1399|1|0,00%|
|1500-1599|1|0,00%|
|**Total general**|**129.880**|**100,00%**|



En la tabla anterior vemos que la mayoría de los vuelos se concentran en el intervalo de 0 a 99 minutos de retraso (intervalo que incluye tanto los vuelos sin retraso como aquellos con retrasos inferiores a 100 minutos). 



<!-- Start of picture text -->
140,000<br>120,000<br>100,000<br>80,000<br>60,000<br>40,000<br>20,000<br>0<br><!-- End of picture text -->

Aunque en la mayoría de los vuelos, el retraso en la salida no superó los 99 minutos, se observan algunos casos excepcionales que alcanzaron los 1.592 minutos. 

## **8.2.** **<u>RETRASOS EN LA LLEGADA</u>** 

En este apartado, vamos a analizar la variable “Arrival Delay” que recoge el retraso en la llegada de cada vuelo expresado en minutos. 

## **Registros con retraso de entrada** 



En el gráfico observamos que el 43,68% de los vuelos sí han sufrido retrasos en la llegada frente al 56,32% que no los han sufrido. 

En la fase de limpieza y transformación de datos, se detectó que 393 registros tenían el dato en blanco para esta variable. Se decidió sustituir estos valores vacíos por la moda que en este caso era 0. 

|**Medida**|**Resultado**|
|---|---|
|**Media**|15,05 minutos|
|**Mediana**|0,00 minutos|
|**Moda**|0,00 minutos|
|**Mínimo**|0,00 minutos|
|**Máximo**|1.584,00<br>minutos|
|**Desv. Estand**|38,42 minutos|



En la tabla anterior podemos observar que la media de retraso es de 15,05 minutos, mientras que la mediana y la moda son de 0 minutos. Esto indica que al menos la mitad de los vuelos no registraron retrasos en su llegada. 

La diferencia entre la media y la mediana puede explicarse por la existencia de algunos retrasos de larga duración, que elevan el valor medio. 

|**Intervalo de Retraso en**<br>**Llegada**|**N.º Vuelos**|**%**|
|---|---|---|
|0-99|125.393|96,55%|
|100-199|3.486|2,68%|
|200-299|688|0,53%|
|300-399|199|0,15%|
|400-499|72|0,06%|
|500-599|16|0,01%|
|600-699|7|0,01%|
|700-799|7|0,01%|
|800-899|3|0,00%|
|900-999|5|0,00%|
|1000-1099|1|0,00%|
|1100-1199|1|0,00%|
|1200-1299|1|0,00%|
|1500-1599|1|0,00%|
|**Total general**|**129.880 **|**100,00%**|



En la tabla anterior vemos que la mayoría de los vuelos se concentran en el intervalo de 0 a 99 minutos de retraso (intervalo que incluye tanto los vuelos sin retraso como aquellos con retrasos inferiores a 100 minutos). 

Podemos observar que a medida que va incrementando el tiempo de retraso va reduciéndose el número de vuelos. 

Aunque estos casos son poco frecuentes, se registraron retrasos de hasta 1.584 minutos, lo que refleja la existencia de situaciones excepcionales. 

## **8.3.** **<u>COMPARACIÓN ENTRE LOS RETRASOS DE SALIDA Y DE LLEGADA</u>** 

Con los datos que ya habíamos presentado anteriormente, podemos comparar los resultados de ambas variables: 

|**Medida**|**Resultados**<br>**Retrasos**<br>**Salidas**|**Resultados**<br>**Retrasos**<br>**Llegadas**|
|---|---|---|
|**Media**|14,71 minutos|15,05 minutos|
|**Mediana**|0,00 minutos|0,00 minutos|
|**Moda**|0,00 minutos|0,00 minutos|
|**Máximo**|1.592,00|1.584,00|



||minutos|minutos|
|---|---|---|
|**Desv. Estand**|38,07 minutos|38,42 minutos|
|**% de valores**<br>**iguales a 0**|56,48%|56,32%|



La primera conclusión que podemos sacar es que las distribuciones son muy similares, la medio de retrasos en las llegadas es ligeramente superior al retraso de las salidas. La moda y la mediana son iguales para ambas variables (0 minutos), mientras que la dispersión es prácticamente idéntica. 

También podemos observar que el % de registros sin retraso es muy similar para las dos variables, sin embargo, hay que tener en cuenta los 393 registros que en la variable de retrasos en la llegada estaban en blanco y que han sido sustituidos en la fase de limpieza por 0. 

## **9.** **<u>ANÁLISIS DE LAS VALORACIONES DE LOS SERVICIOS</u>** 

## **9.1.** **<u>VALORACIÓN GENERAL DE LOS SERVICIOS</u>** 

En este apartado se analizarán las valoraciones que los pasajeros han realizado sobre los diferentes servicios ofrecidos por la aerolínea. Para ello, se estudiarán las puntuaciones de las 14 variables relacionadas con la experiencia del pasajero. Las puntuaciones originales van de 1 a 5, donde 1 representa una valoración baja y 5 una valoración alta. Los valores 0 indican que el servicio no era aplicable al pasajero, por lo que, se han excluido del cálculo de las medias, medianas y modas. 

|**Servicio**|**Media **|**Mediana **|**Moda **|**Recuento "0"**|
|---|---|---|---|---|
|In-flight Wifi Service|2,81|3|2|3.916|
|Ease of Online Booking|2,88|3|3|5.682|
|Gate Location|2,98|3|3|1|
|Food and Drink|3,21|3|4|132|
|Departure and Arrival Time Convenience|3,22|3|4|6.681|
|Cleanliness|3,29|3|4|14|
|Check-in Service|3,31|3|4|1|
|Online Boarding|3,33|4|4|3.080|
|In-flight Entertainment|3,36|4|4|18|
|Leg Room Service|3,37|4|4|598|
|On-board Service|3,38|4|4|5|
|Seat Comfort|3,44|4|4|1|
|Baggage Handling|3,63|4|4|0|
|In-flight Service|3,64|4|4|5|



Viendo los resultados en la tabla, podemos destacar que el servicio abordo presenta la media más alta con 3,64 puntos, seguido muy de cerca por la gestión de equipaje con 3,63 puntos. 

Por otra parte, las valoraciones más bajas, vemos que corresponden al servicio de wifi abordo con 2,81 puntos y la facilidad de reserva online con 2,88 puntos. 

La mayoría de los servicios tienen una moda de 4, lo que indica que esta es la puntación que más se repite en buena parte de las variables. 

También hemos comprobado los valores 0 los diferentes servicios y destacan 6.681 en la comodidad de horarios, seguidos de los 5.682 registros de facilidad de reserva online y 3.916 del servicio de Wifi a bordo. Esto refuerza la importancia de excluirlos de las medias. 

## **9.2.** **<u>VALORACIÓN DE LOS SERVICIOS SEGÚN EL NIVEL DE SATISFACCIÓN</u>** 

Aquí vamos a analizar si los pasajeros satisfechos valoran los servicios de forma diferentes a los pasajeros neutrales o insatisfechos. 

|**Servicio**|**Neutral/Dissatisfied **|**Satisfied**|
|---|---|---|
|In-flight Wifi Service|2,40|3,16|
|Ease of Online Booking|2,55|3,03|
|Gate Location|2,98|2,97|
|Food and Drink|2,96|3,53|
|Departure and Arrival Time Convenience|3,13|2,96|
|Cleanliness|2,93|3,75|
|Check-in Service|3,04|3,65|
|Online Boarding|2,66|4,03|
|In-flight Entertainment|2,89|3,96|
|Leg Room Service|2,99|3,82|
|On-board Service|3,02|2,97|
|Seat Comfort|3,04|3,97|
|Baggage Handling|3,37|3,97|
|In-flight Service|3,39|3,97|



En el gráfico podemos observar que, en términos generales los pasajeros satisfechos otorgan puntuaciones más altas a la mayoría de los servicios que los pasajeros neutrales o insatisfechos. 

Las diferencias más destacadas se encuentran en el embarque online, el entretenimiento a bordo, la comodidad del asiento, la limpieza y el espacio para las piernas. En estos servicios, las valoraciones del grupo de pasajeros satisfechos son considerablemente mejores. 

Por otro lado, encontramos servicios cuyas puntuaciones son bastante similares entre ambos grupos, como la ubicación de la puerta de embarque y el servicio a bordo. También destaca la comodidad de horarios, cuya valoración es ligeramente superior entre los pasajeros neutrales o insatisfechos. 

Estos resultados sugieren que determinados aspectos de la experiencia durante el vuelo, especialmente el embarque, el entretenimiento y la comodidad, están asociados a una mayor satisfacción del pasajero. 



<!-- Start of picture text -->
Comparativa de valoraciones en función de la satisfacción<br>In-flight Service<br>Baggage Handling<br>Seat Comfort<br>On-board Service<br>Leg Room Service<br>In-flight Entertainment<br>Online Boarding<br>Check-in Service<br>Cleanliness<br>Departure and Arrival Time Convenience<br>Food and Drink<br>Gate Location<br>Ease of Online Booking<br>In-flight Wifi Service<br>0.00 0.50 1.00 1.50 2.00 2.50 3.00 3.50 4.00 4.50 5.00<br>Satisfied Neutral/Dissatisfied<br><!-- End of picture text -->

## **10.** **<u>ANÁLISIS DE LA SATISFACCIÓN DE LOS PASAJEROS</u>** 

## **10.1. ANÁLISIS DE LA SATISFACCIÓN DE LOS PASAJEROS** 

En este apartado queremos conocer cómo se distribuye la satisfacción entre los pasajeros de la aerolínea. 



<!-- Start of picture text -->
N<br>e<br>u<br>tr<br>a<br>l<br>o<br>r<br>D<br>S is<br>a s<br>ti a<br>% de Satisfacción d fi4es sftid5ei<br>3 6<br>4, 5,<br>5 5<br>% %<br><!-- End of picture text -->

En el gráfico podemos observar que el 43,45% de los pasajeros están satisfechos en términos generales frente al 56,55% que son neutrales o insatisfechos. 

## **10.2. ANÁLISIS DE AL SATISFACCIÓN SEGÚN LAS CARACTERÍSTICAS DEL PASAJERO Y DEL** 

## **<u>VIAJE</u>** 

## **10.2.1.** **<u>SATISFACCIÓN SEGÚN EL TIPO DE BILLETE</u>** 

En este apartado, vamos a comparar la satisfacción de los pasajeros en función del tipo del billete. 



<!-- Start of picture text -->
Satisfacción según el tipo de billete<br>Economy Plus 75.36% 24.64%<br>Economy 81.23% 18.77%<br>Business 30.56% 69.44%<br>0.00% 20.00% 40.00% 60.00% 80.00% 100.00%<br>Neutral or Dissatisfied Satisfied<br><!-- End of picture text -->

En el gráfico anterior podemos ver la satisfacción de los clientes en función del tipo de billete. A simple vista podemos observar un nivel de satisfacción desigual entre los distintos grupos. Los pasajeros que viajan en clase Business presentan un mayor grado de satisfacción (69,44%) que aquellos que viajan tanto en Economy (18,77%) como en Economy Plus (24,64%). 

Viendo únicamente el gráfico, no podemos determinar que el hecho de viajar en Business sea por sí solo el motivo de una mayor satisfacción. 

## **10.2.2.** **<u>SATISFACCIÓN SEGÚN EL TIPO DE CLIENTE</u>** 

En este punto, compararemos los pasajeros que vuelan por primera vez con aquellas que ya han viajado anteriormente con la aerolínea. 



<!-- Start of picture text -->
Satisfacción según el tipo de cliente<br>Returning 52.19% 47.81%<br>First-time 76.03% 23.97%<br>0.00% 20.00% 40.00% 60.00% 80.00% 100.00%<br>Neutral or Dissatisfied Satisfied<br><!-- End of picture text -->

En el gráfico vemos un nivel de satisfacción desigual entre aquellos pasajeros que ya han viajado anteriormente con la aerolínea (satisfacción de un 47,81% frente a un 52,19%) y aquellos que viajan por primera vez (satisfacción de un 23,97% frente a un 76,03%). Por lo que, podemos concluir que los viajeros recurrentes están más satisfechos que aquellos que han viajado por primera vez con la compañía. 

## **10.2.3.** **<u>SATISFACCIÓN SEGÚN EL MOTIVO DEL VIAJE</u>** 

En este apartado, vamos a comparar el nivel de satisfacción de los pasajeros en función del motivo del viaje. 



<!-- Start of picture text -->
Satisfacción según el motivo del viaje<br>Personal 89.87% 10.13%<br>Business 41.63% 58.37%<br>0.00% 20.00% 40.00% 60.00% 80.00% 100.00%<br>En el  Neutral or Dissatisfied Satisfied gráfico<br>anterior, podemos observar que aquellos pasajeros que viajen por motivos laborales tienen un % de satisfacción<br>mayor (58,37%) que aquellos que viajan por motivos personales (10,13%).<br><!-- End of picture text -->

## **10.2.4.** **<u>SATISFACCIÓN SEGÚN LA EDAD DE LOS PASAJEROS</u>** 

En esta apartado vamos a analizar si existen diferencias en el nivel de satisfacción dependiendo de la edad de los pasajeros. 

## Satisfacción según rango de edad 



<!-- Start of picture text -->
0-9 88.42% 11.58%<br>10-19 79.99% 20.01%<br>20-29 64.30% 35.70%<br>30-39 58.71% 41.29%<br>40-49 41.97% 58.03%<br>50-59 42.74% 57.26%<br>60-69 72.13% 27.87%<br>70-79 78.24% 21.76%<br>80-89 72.59% 27.41%<br>0.00% 10.00% 20.00% 30.00% 40.00% 50.00% 60.00% 70.00% 80.00% 90.00% 100.00%<br>Neutral or Dissatisfied Satisfied<br><!-- End of picture text -->

Al analizar la satisfacción según la edad de los pasajeros, observamos que existen diferencias entre los distintos grupos. Los pasajeros de entre 30 y 59 años presentan los porcentajes de satisfacción más elevados, alcanzando el 57,26% en el grupo de entre 50 y 59 años. Por el contrario, los grupos más jóvenes y los de mayor edad, son los que presentan los porcentajes de satisfacción más bajos con un 11,58% en el grupo de 0 a 9 años. 

Debemos tener en cuenta, que justo los grupos de mayor edad y el de 0 a 9 años, son los grupos con menor número de pasajeros. 

## **10.2.5.** **<u>SATISFACCIÓN SEGÚN LA DISTANCIA DEL VUELO</u>** 

En este apartado, vamos a analizar si la distancia del vuelo está relacionada con el nivel de satisfacción de los pasajeros. 



<!-- Start of picture text -->
Satisfacción según distancia del vuelo<br>31-530 66.42% 33.58%<br>531-1030 67.58% 32.42%<br>1031-1530 61.95% 38.05%<br>1531-2030 41.20% 58.80%<br>2031-2530 37.56% 62.44%<br>2531-3030 31.33% 68.67%<br>3031-3530 22.47% 77.53%<br>3531-4030 22.42% 77.58%<br>4031-4530 48.65% 51.35%<br>4531-5030 41.46% 58.54%<br>0.00% 10.00% 20.00% 30.00% 40.00% 50.00% 60.00% 70.00% 80.00% 90.00% 100.00%<br><!-- End of picture text -->

Neutral or Dissatisfied Satisfied 

En el gráfico podemos observar que, a mayor distancia del vuelo, mayor % de satisfacción de los pasajeros. Vemos que hay diferencias entre los distintos grupos y que hasta los vuelos de 1.530 millas predominaban los pasajeros neutrales o insatisfechos y que a partir de esa distancia, pasan a predominar los pasajeros satisfechos. 

Adicionalmente, vemos que en los dos últimos grupos, la diferencia entre pasajeros satisfechos e insatisfechos se ha reducido, aunque también hay que destacar que son grupos con menor nº de pasajeros. 

## **10.3. CONCLUSIONES DEL ANÁLISIS DE SATISFACCIÓN** 

Después de observar los distintos gráficos, podemos determinar que predominan los pasajeros neutrales o insatisfechos (56,55 %) frente a los satisfechos (43,45 %). 

Los pasajeros que viajan en Business y aquellos que lo hacen por motivos laborales presentan un mayor porcentaje de satisfacción. Asimismo, los pasajeros recurrentes muestran una mayor satisfacción que aquellos que viajan por primera vez con la aerolínea. 

En función de la edad, se observan diferencias entre los distintos grupos, destacando los pasajeros de entre 37 y 56 años por presentar mayores niveles de satisfacción. Por otro lado, los pasajeros que realizan vuelos de mayor distancia muestran porcentajes de satisfacción superiores a los que realizan vuelos más cortos. 

En cuanto a los servicios, los pasajeros que están satisfechos con la aerolínea tienden a valorar mejor los servicios prestados por la misma, especialmente el embarque online, el entretenimiento a bordo y la comodidad del asiento. 

## **11.** **<u>CONCLUSIONES GENERALES DEL ANÁLISIS DESCRIPTIVO</u>** 

En cuanto a las conclusiones generales, podemos determinar que la muestra está bastante equilibrada en cuanto al género y que predominan los viajeros recurrentes (81,69 %) y los viajes por motivos laborales (69,06 %). 

El tipo de billete que predomina es Business o Economy, con una representación bastante similar (47,86 % y 44,89 %, respectivamente). En cuanto a la distancia, la mayoría de los vuelos se concentran en trayectos inferiores a las 1.030 millas. 

Respecto a los retrasos, observamos que tanto en la salida como en la llegada, la mayoría de los vuelos registra retrasos inferiores a 100 minutos o no presenta retraso. Sin embargo, cabe destacar que, en los retrasos de llegada, había 393 registros en blanco que fueron sustituidos por 0 minutos, utilizando la moda como criterio de imputación. 

Los servicios mejor valorados son el servicio a bordo (3,64) y la gestión del equipaje (3,63), mientras que el servicio de wifi a bordo (2,81) y la facilidad de reserva online (2,88) obtienen las valoraciones más bajas. 

En general, predominan los pasajeros neutrales o insatisfechos (56,55 %) frente a los satisfechos, aunque se observan diferencias importantes según la clase, el motivo del viaje, el tipo de cliente y la distancia. 

A partir de los resultados obtenidos, se pueden identificar diferentes áreas en las que la aerolínea podría centrar sus esfuerzos para mejorar la experiencia y satisfacción de sus pasajeros. 

En primer lugar, sería recomendable revisar y mejorar aquellos servicios que han obtenido las valoraciones más bajas, especialmente el wifi a bordo y la facilidad de reserva online, con el objetivo de ofrecer una experiencia más satisfactoria desde el proceso de compra hasta el propio vuelo. 

Por otro lado, sería interesante analizar por qué la categoría Economy Plus presenta una demanda considerablemente inferior a las otras dos categorías. Para ello, se podrían estudiar aspectos como el precio, los servicios incluidos y la percepción de valor que tienen los pasajeros respecto a esta opción intermedia. 

Por último, sería conveniente investigar por qué los pasajeros que viajan por primera vez con la aerolínea presentan menores niveles de satisfacción que los clientes recurrentes. Identificar qué aspectos de su experiencia no cumplen sus expectativas podría ayudar a la compañía a mejorar la atención a nuevos clientes y favorecer su fidelización. 

En definitiva, este análisis permite identificar aspectos que podrían ser objeto de mejora y servir como punto de partida para futuras investigaciones y decisiones orientadas a incrementar la satisfacción de los pasajeros. 

