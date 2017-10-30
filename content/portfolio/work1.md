+++
draft = false
image = "img/portfolio/work1_app_sequia_biobio.png"
date = "2016-11-05T18:25:22+05:30"
title = "Sequía Agrícola Región del Bío-Bío"
showonlyimage = false
weight = 1
+++

Plataforma web geo-espacial que muestra la variación espacial y temporal de la sequía agrícola por medio de un índice vegetacional y uno de déficit de precipitación entre el año 2000 al 2015. Corresponde a los resultados de un trabajo de investigación en que se estudió la variación espacial y temporal en la respuesta de la vegetación a los cambios en el clima. 
<!--more-->

[Link a la aplicación](https://frzambra.shinyapps.io/sequiabiobio/)

Los resultados fueron publicados en el artículo [Sixteen years of agricultural drought assessment of the BioBío Region in Chile using a 250 m resolution Vegetation Condition Index (VCI)](http://www.mdpi.com/2072-4292/8/6/530). Se dearrolló una aplicación web en la cual es posible observar los resultados en forma dinámica y visualmente atractiva. A continuación una breve descripción de lo que permite visualizar la aplicación.

## Respuesta espacio-temporal de la vegetación

Se puede visualizar el valor promedio para cada comuna de la región del Bío-Bío en cuanto al índice de sequía VCI para periodos de 16-dias entre febrero del año 2000 a marzo del 2015.

![VCI][1]

El cuadro de la parte superior derecha presenta un `slider` que permite seleccionar la fecha de interes (periodos de 16 dias). El cuadro de mas abajo se muestra que es posible selecionar entre `Intensity` que corresponde a la intensidad del índice VCI, y también se puede `Surface (%)` con lo que se puede ver el porcentaje de superficie en cada comuna que, para la fecha seleccionada, fue afectada por algun nivel de sequía.

## Respuesta temporal del déficit de precipitación

Se utilizó un índice de deficit de precipitación (SPI) para analizar la variación temporal de la lluvia caida para 27 estaciones meteorológicas en la región. Este índice permite conocer el défcit de precipitacion acumulado ya sea de un solo mes, tres, o mucho meses, en este caso llegando hasta treinta y seis. 
![SPI][2]

En la parte inferior del cuadro de la derecha se puede seleccionar la cantidad de meses `SPI time-scales`, luego al pinchar en el mapa en alguna de las estaciones, en la parte inferior derecha se despliega un gráfico de la serie temporal correspondiente a la estación y el acumulado de la cantidad de meses seleccionados

[1]: /img/portfolio/work1_img2.png
[2]: /img/portfolio/work1_img3.png