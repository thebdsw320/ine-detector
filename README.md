# Detector de tarjetas INE falsas

Este es un proyecto dedicado a poder detectar tarjetas INE falsas mediante métodos de similaridad estructural en las imagenes que le demos a la máquina a analizar. La máquina tiene una imagen de prueba, en base a ella esta analiza la imagen que le demos y encuentra similutudes. La imagen de prueba es la siguiente:

<img style="display: block; margin-left: auto; margin-right: auto; width: 50%" src="/steps/image.jpg" width="200" height="190">

El proyecto está hecho principalmente con **Flask y opencv**.

Para usarlo simplemente debemos subir la INE que queramos analizar y la página nos devolverá un porcentaje de similaridad que tiene con la INE base.

<img style="display: block; margin-left: auto; margin-right: auto; width: 50%" src="/steps/paso1.png">

Finalmente solo ponemos la imagen y esperamos a que arroje un resultado.

<img style="display: block; margin-left: auto; margin-right: auto; width: 50%" src="/steps/paso2.png">
