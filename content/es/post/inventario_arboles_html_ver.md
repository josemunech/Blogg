---
title: "Como hacer un inventario detallado de árboles de aguacate con un GPS y un celular."
author: "Ecofresca SAS"
date: "2023-07-29"
output: html_document
---

  








Para una gestión adecuada de una plantación de aguacates es necesario saber la cantidad de árboles y el estado fitosanitario y productivo de cada árbol.

En Ecofresca desarrollamos y ponemos a disposición una metodología y un código para generar un inventario de árboles como el que se muestra al final de esta página.


Para hacer este inventario solo necesitamos un GPS para georreferenciar cada árbol y un celular para anotar el estado de cada árbol en un archivo de texto. En Ecofresca hacemos el inventario con dos personas: una para tomar los puntos del GPS y otra para hacer las anotaciones en el celular.

Materiales:

GPS: En Ecofresca utilizamos un GPS marca Garmin. Mientras más preciso sea, mejor. Se puede utilizar otro tipo de GPS, pero lo importante es que el dispositivo permita tener un archivo GPX con la información de cada punto. Es importante vaciar el contenido antiguo del GPS para tener espacio libre para los nuevos puntos. A nuestro GPS en Ecofresca le caben 2000 puntos, lo cual es suficiente para hacer el inventario de nuestra finca.

Celular: los datos sobre el estado de cada árbol se almacenan en una nota en el celular. Esta genera un archivo .txt. El formato del archivo es el siguiente:


{{< figure src="/images/tabla.png" title="Así luce el formato de los datos en una nota del celular " >}}

El formato tiene 6 principales columnas separadas por un espacio (solo un espacio).

1. Punto_GPS: Corresponde al código que el GPS asigna a cada punto. En el ejemplo podemos ver que el primer árbol tiene el número 440 y el último el 448. Es importante anotar correctamente el número que asigna el GPS y ponerlo en la misma línea del árbol que se está describiendo.

2. prod_impr: Esta columna es para calificar si el árbol es productivo o improductivo. Si es productivo, se marca 'p'; si no es productivo, 'np'.

3. tamaño: las categorías son 'mg' para muy (demasiado) grande, 'g' para grande, 'm' para mediano, 'p' para pequeño, y 'v' si se trata de un espacio vacío (sin árbol).

4. detalle: es una descripción sobre el estado del árbol. Las categorías son: 'ok' para árboles en buen estado, 'am' para árboles con amarillamientos, 'er' para espacios de resiembra (sitios vacíos), 'mue' para árboles muertos. Para los  árboles resembrados usamos la letra ‘r’ junto a la edad del  árbol resembrado.  ‘r1’ para resiembra de un año o menos, ‘r1.5’ para resiembras de año y medio, y ‘r2’ para resiembras de dos años.Para las zocas usamos la letra 'z' junto a la edad de la zoca: 'z2' zoca de 2 años, 'z1' zoca de un año, y 'z0.5' para zoca de medio año.

5. color: es una escala de 0 a 3 para describir el color. '0' para árboles sin follaje, '1' para árboles con un amarillamiento muy avanzado, '2' para árboles con comienzo de amarillamiento, y '3' para árboles de color verde normal.

6. lote: número del lote según la denominación propia de cada finca.

# Este es el inventario

## Total sitios


|item                | Cantidad|
|:-------------------|--------:|
|Total sitios        |     1123|
|Total árboles       |     1021|
|Total sitios vacíos |      102|


<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-2-1.png" width="672" />


## Total árboles


|item          | Cantidad|
|:-------------|--------:|
|grande        |      380|
|mediano       |      422|
|pequeño       |      219|
|Total árboles |     1021|

## Sitios y árboles por lote


|lote | sitios| Total_árboles| Grandes| Medianos| Pequeños| Vacíos|
|:----|------:|-------------:|-------:|--------:|--------:|------:|
|1    |    212|           210|     167|       32|       11|      2|
|2    |     28|            28|      17|        7|        4|     NA|
|3    |    321|           291|      62|      158|       71|     30|
|4    |    152|           142|      66|       64|       12|     10|
|5    |    410|           350|      68|      161|      121|     60|

### Distribución espacial de tamaños

<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-5-1.png" width="672" />

## Total de sitios productivos y no productivos


|Producción    | sitios|
|:-------------|------:|
|No productivo |    406|
|Productivo    |    717|

### Distribución espacial de árboles productivos

<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-7-1.png" width="672" />

### Productividad por tamaños


|tamaño  |Producción    | sitios|
|:-------|:-------------|------:|
|grande  |No productivo |     15|
|grande  |Productivo    |    365|
|mediano |No productivo |    113|
|mediano |Productivo    |    309|
|pequeño |No productivo |    176|
|pequeño |Productivo    |     43|
|vacío   |No productivo |    102|

## Descripción de los árboles


|Descripción            | sitios|
|:----------------------|------:|
|Espacio de Resiembra   |    101|
|Resiembra              |     70|
|Zoca                   |    111|
|Árboles amarillos      |    260|
|Árboles en buen estado |    577|
|Árboles muertos        |      2|
|NA                     |      2|


<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-10-1.png" width="672" />

<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-11-1.png" width="672" />

## Amarillamientos 


|Follage                      | sitios|
|:----------------------------|------:|
|1. Amarillamiento avanzado   |      9|
|2.Comienzo de amarillamiento |    250|
|3. Verde                     |      1|

<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-13-1.png" width="672" />



## Zocas 


|Zocas            | sitios|
|:----------------|------:|
|1 año            |     69|
|2 años           |     19|
|Menos de 6 meses |     22|
|Zoca criollo     |      1|

<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-15-1.png" width="672" />



## Resiembras 


|Resiembras | sitios|
|:----------|------:|
|1 año      |     21|
|1.5 años   |     31|
|2 años     |     18|



<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-17-1.png" width="672" />


<img src="/es/post/inventario_arboles_html_ver_files/figure-html/unnamed-chunk-18-1.png" width="672" />



