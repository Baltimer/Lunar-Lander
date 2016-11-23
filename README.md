# Lunar-Lander
Proyecto del juego Lunar Lander, en la versión de Alejandro Suárez. Éste es un proyecto para la clase de Lenguaje de Marcas, en el cual se nos ha entregado un proyecto de otro compañero y hemos tenido que representarlo de la manera más fiel posible.

## Preview del proyecto entregado
En el proyecto entregado, la intención era que la aplicación tuviese el siguiente formato:

![Background Dado](https://github.com/Baltimer/Lunar-Lander/blob/master/img/Background-dado.png)
![Background Vertical](https://github.com/Baltimer/Lunar-Lander/blob/master/img/fondovertical-dado.jpg)

Se dieron los siguientes paneles, los cuales eran ilegibles y poco útiles, así que decidí cambiarlos por otros mucho más útiles y que se pudiesen implementar:

![Panel Dado](https://github.com/Baltimer/Lunar-Lander/blob/master/img/PanelALoRapido.png)

Ya no dieron más detalles, simplemente la colocación del panel o el estilo de la nave que la separaron de la imagen final y la incluyeron en el proyecto aparte, solo como un documento png.

## Primeros avances

Al empezar a colocar los elementos en la aplicación, ésta se veía bastante mal y con poca implementación:

- El background contenía un degradado en su totalidad.
- La Tierra estaba integrada en el background, lo que dificultaba su manipulación.
- Había una linea donde iba a ir colocada la luna, lo cual alteraba el background en sí.
- El panel no se podía implementar así como estaba.
- Los botones se encontraban en una misma imagen, en lugar de 1 imagen por cada botón.
- Las imágenes no tenían el formato correcto, no tenían transparencias o tenían un tamaño excesivo.

## Soluciones

Para poder arreglar los problemas del fondo, decidí implementar algunas mejoras a la aplicación:

- Crear una imagen que repetiría para el fondo.
- Dividir las imágenes de los botones y darles la tonalidad adecuada al fondo.
- Separar la Tierra del background para tratarla como un elemento aparte (idea de un compañero de clase, Marc Hernández).
- Crear un nuevo panel desde 0.
- Redimensionar y tratar las imágenes para la implementación de la aplicación.

Para distribuir los elementos de la aplicación, me basé en la siguiente estructura:

![Distribución elementos](https://github.com/Baltimer/Lunar-Lander/blob/master/img/Distribucion.png)

## Decisión de la visualización de la aplicación

A la hora de decidir cómo y de qué manera colocar los elementos, decidí usar dos estilos: uno para una versión estándar de ordenador o dispositivos grandes, y otra especialmente pensada para dispositivos móviles. Para ello creé un único documento __index.html__ y 2 documentos css para su tratamiento dependiendo del dispositivo en el que se reproduzca: __vertical.css__ y __horizontal.css__.

Añadí, además, otra página llamada __about.html__ donde sale información relacionada con el proyecto, la cual la trataba de la misma manera que la anterior, usando dos css llamados __about.css__ y __aboutVertical.css__.

## Tratamiento de la aplicación

La intención a la hora de hacer la aplicación era que fuese _responsive_, de manera que se mantuviese la distribución en cualquier caso.

Usando tantos por ciento en lugar de píxels para las medidas, he conseguido ese resultado. Gracias a eso, he podido, además, redimensionar las imágenes basandose en el tanto por ciento del navegador en el que se verá, y no dándole unos valores yo predefinidos.

## Optimización de la aplicación

Para evitar largos períodos de carga, he comprimido las imágenes lo máximo posible sin llegar a perder los colores. Además he utilizado la función indexados y reducido la paleta desde el programa GIMP.

## Conclusiones

El proyecto está siendo muy instructivo y me ha ayudado a comprender de manera eficaz los elementos básicos de los que se componen los lenguajes __HTML__ y __CSS__.

He tenido que dedicarle un tiempo proporcional al proyecto bastante grande para el tratamiento de las imágenes, ya que el proyecto que me facilitaron estaba bastante incompleto y contenía muchas imágenes inutilizables.

## Resultado

He obtenido 2 resultados, dependiendo del dispositivo en el cual reproduzcas la aplicación:

__DISPOSITIVO MÓVIL__  
![movil vertical](https://github.com/Baltimer/Lunar-Lander/blob/master/img/Vertical.png)
![movil vertical 2](https://github.com/Baltimer/Lunar-Lander/blob/master/img/Vertical%202.png)

__DISPOSITIVO ESTANDAR__
![estandar](https://github.com/Baltimer/Lunar-Lander/blob/master/img/Horizontal.png)
![estandar 2](https://github.com/Baltimer/Lunar-Lander/blob/master/img/Horizontal%202.png)

## Agradecimientos

Quiero agradecer a Alejandro Suárez por facilitarme su proyecto y permitirme llevarlo a cabo, así como a la clase por sus feedbacks sobre mi aplicación, los que me ayudaron a resolver _bugs_ menores del proyecto. En especial mención a __Marc Hernández__ por su idea de separar los planetas/lunas del fondo y el aporte a la hora de mostrar/ocultar paneles, y a __Guillermo Cirer__ por su ayuda a la hora de comprender algunas funcionalidades de _HTML_ y _CSS_

## Bibliografía

Recursos y programas utilizados en el proyecto:

- Para el tratamiento de las imágenes, he utilizado el programa __GIMP__.
- Para la comprensión de los lenguajes utilizados, he seguido las indicaciones del profesor Miguel Urbina y la página www.w3schools.com.
- El host www.hostinger.es, que me ha permitido subir mi página web y compartirla con mis compañeros para el feedback. (http://baltimer.esy.es).
