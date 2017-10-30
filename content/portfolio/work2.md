+++
date = "2016-11-05T19:41:01+05:30"
title = "Deep Learning para predicción estado de la vegetación en Chile "
draft = false
image = "img/portfolio/work2_img1.png"
showonlyimage = false
weight = 2
+++

Utilizando técnicas de análisis de datos (Deep Learning y regresión lineal) se logró la predicción de la condición de la vegetación utilizando distinta información extraida de imágenes satelitales, para el 90% del área cultivable de Chile a nivel de distrito censal.
<!--more-->

[Link a la aplicación](https://frzambra.shinyapps.io/drought_prediction/)

Se diseñó una plataforma web geo-espacial en donde se visualiza información a nivel de distrito censal acerca de:

1. Inicio de la temporada agrícola (Fecha).
2. Término de la temporada agrícola (Fecha).
3. Duración de la temporada agrícola (días).
4. Estado de la vegetación.
5. Predicción del estado de la vegetación al término de la temporada agrícola.

La aplicación permite seleccionar la región de la cual se desea visualizar la información (entre Coquimbo a Los Ríos). Luego, es posible seleccionar un parámetro de los cinco antes descritos.

![img1][1]

Se puede elegir entre una predicción realizada utilizado *Deep Learning* o *Regresión Lineal*. Para la selección de la serie temporal a visualizar es posible elegir, entre los valores multi-anuales, es decir los valores desde la temporada agrícola 2000-2001 hasta 2016-2017, o bien se puede visualizar cómo ha variado la condición de la vegetación dentro de alguna temporada agrícola.

![img2][2]
![img3][3]

En caso de haber seleccionado *multi anual* y luego de pinchar en el distrito censal seleccionado, en la parte inferior se muestra un gráfico de la sereie temporal desde la temporada 2000-2001 hasta el valor predicho de acuerdo al método seleccionada en la temporada 2016-2017.

![img4][4]

Si se eligió visualizar la variación dentro de alguna temporada agrícola el gráfico desplegará la visualización de la variación de la condición de la vegetación para dicha temporada.

![img5][5]

El mapa de la izquierda muestra el valor de la condición de la vegetación para los distritos censales de la región seleccionada. El valor mostrado podrá ser el *actual*, predicho con *Deep Learning* o predicho con *regresión lineal*. Estos valores se podran visualizar de forma interactiva sobre un mapa base

![img6][6]

También, se puede seleccionar un mapa de relieve

![img7][7]

O un mapa tipo visualización de satelite

![img8][8]

[1]: /img/portfolio/work2_img2.png
[2]: /img/portfolio/work2_img3.png
[3]: /img/portfolio/work2_img4.png
[4]: /img/portfolio/work2_img5.png
[5]: /img/portfolio/work2_img6.png
[6]: /img/portfolio/work2_img7.png
[7]: /img/portfolio/work2_img8.png
[8]: /img/portfolio/work2_img9.png