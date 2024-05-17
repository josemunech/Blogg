---
title: "Café en Antioquia según los datos de la gobernación"
output: html_document
date: "2024-05-16"
featured_image: "/images/cafe.png"
---

<script src="/rmarkdown-libs/htmlwidgets/htmlwidgets.js"></script>
<link href="/rmarkdown-libs/datatables-css/datatables-crosstalk.css" rel="stylesheet" />
<script src="/rmarkdown-libs/datatables-binding/datatables.js"></script>
<script src="/rmarkdown-libs/jquery/jquery-3.6.0.min.js"></script>
<link href="/rmarkdown-libs/dt-core/css/jquery.dataTables.min.css" rel="stylesheet" />
<link href="/rmarkdown-libs/dt-core/css/jquery.dataTables.extra.css" rel="stylesheet" />
<script src="/rmarkdown-libs/dt-core/js/jquery.dataTables.min.js"></script>
<link href="/rmarkdown-libs/crosstalk/css/crosstalk.min.css" rel="stylesheet" />
<script src="/rmarkdown-libs/crosstalk/js/crosstalk.min.js"></script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

## Área sembrada:

Los datos que publica la gobernación de Antioquia muestran una disminución de áreas sembradas (total y en producción) en café desde los años 90.

<img src="/es/post/cafe_files/figure-html/unnamed-chunk-1-1.png" width="672" />

## Producción total:

Los mismos datos muestran una disminución fuerte de la producción desde principio de los noventas hasta el año 2000. Desde el 2000 hasta 2022 la producción del departamento de ha recuperado.

<img src="/es/post/cafe_files/figure-html/unnamed-chunk-2-1.png" width="576" />

## Productividad:

La productividad, definida como la producción total del departamento dividida entre el área sembrada, ha aumentado desde el 2000 hasta el 2022.

$$
Productividad\ neta = \frac{Producción}{Área\ en\ producción}
$$

$$
Productividad\ bruta = \frac{Producción}{Área\ total}
$$

<img src="/es/post/cafe_files/figure-html/unnamed-chunk-3-1.png" width="672" />

Estos datos muestran que el área de siembra en Antioquia ha disminuido desde hace tres décadas, pero hoy en día se produce más por hectárea.

## Área en café en 2022:

En esta tabla interactiva se muestran las áreas sembradas por municipio en el año 2022.

<div class="datatables html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-1" style="width:100%;height:auto;"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"filter":"none","vertical":false,"data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62","63","64","65","66","67","68","69","70","71","72","73","74","75","76","77","78","79","80","81","82","83","84","85","86","87","88","89","90","91"],["Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café","Café"],[2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022,2022],["Andes","Ciudad Bolívar","Salgar","Concordia","Betania","Betulia","Abejorral","Amalfi","Ituango","Jardín","Fredonia","Caicedo","Sonsón","Anzá","Cañasgordas","Ebéjico","Santa Fe de Antioquia","Santa Bárbara","Liborina","Dabeiba","Pueblorrico","Támesis","Sabanalarga","San Roque","Nariño","Jericó","Argelia","Peque","Yolombó","San Andrés de C.","Angostura","Hispania","Sopetrán","Buriticá","Urrao","Toledo","Santo Domingo","Barbosa","Tarso","Caramanta","Heliconia","Santa Rosa de Osos","San Carlos","San Jerónimo","Giraldo","San Rafael","Gómez Plata","Frontino","Venecia","Briceño","Alejandría","Amagá","Valparaiso","Armenia","Cocorná","Guadalupe","Titiribí","Uramita","Medellín","Olaya","Anorí","La Ceja","Vegachí","San Luis","Yarumal","Angelópolis","Granada","Yalí","Girardota","Campamento","El Retiro","San Francisco","Abriaquí","Don Matías","Bello","El Peñol","Concepción","El Carmen de Viboral","Caldas","Cisneros","Copacabana","Maceo","Valdivia","San Vicente","Sabaneta","La Estrella","Marinilla","Guatape","Envigado","Carolina","Caracolí"],[11040,9886,7841.6,6781,6502.18,5981,3039,2478.5,2464,2321,2309,2211,2186,2016,1995.66,1869.22,1866,1846,1720,1679,1651,1527,1404,1389.5,1325,1308,1282,1278,1240,1144,1131,1093.2,1063,1033,1024,999,975,967,897.95,896.4,807,804,761,702.7,682,645,633.84,631,612,582,555,551,523.5,507,467.2,462,461,458,456.6,417,413,410,372.58,300,285,277,256,246,213,200,183,182,181.2,177,162,142,135,129.99,120.2,107,94.5,90,49,39,35,34,27,10,7.7,7,2],[10540,8598,7304,5625,4388.18,4255,2837,2203.5,2191,1669,1912,2067,2019,1808,1918.81,1804.08,1584,1478,1355,1549,1437,1522,1112,1254.5,1151,1044,1179,1121,1240,1024,891,833.2,948,895,891,873,939,857,676.5,525.4,687,535,651,697,680,601,547.84,483.7,612,551,471,438,506.5,486,462.2,357,430,458,440.6,389,390,341,346.99,265,233,245,228,203,193.6,177,167,156,146.5,153,155,135,125,129.99,112.2,107,94.5,90,45,33,20,34,23,8,4.7,6,2],[21080,11177.4,15338.4,8437.5,7459.91,7659,3971.8,2005.18,4382,2670.4,2868,5167.5,3230.4,1808,3453.86,3608.16,2059.2,2596.85,2439,2478.4,3305.1,2473.25,1223.2,1254.5,2186.9,1566,1768.5,2017.8,2232,1024,2227.5,1666.4,1516.8,895,1069.2,1396.8,1690.2,1542.6,879.45,630.48,2748,674.1,1171.8,1394,748,781.3,602.62,1064.14,1224,551,612.3,657,557.15,874.8,739.52,571.2,860,458,321.64,466.8,351,409.2,253.3,530,372.8,367.5,319.2,101.5,300.08,212.4,267.2,358.8,454.15,275.4,155,310.5,125,259.98,100.98,149.8,80.33,144,81,66,20,51,29.9,15.2,5.64,6.6,0.8],[2,1.3,2.1,1.5,1.7,1.8,1.4,0.91,2,1.6,1.5,2.5,1.6,1,1.8,2,1.3,1.76,1.8,1.6,2.3,1.62,1.1,1,1.9,1.5,1.5,1.8,1.8,1,2.5,2,1.6,1,1.2,1.6,1.8,1.8,1.3,1.2,4,1.26,1.8,2,1.1,1.3,1.1,2.2,2,1,1.3,1.5,1.1,1.8,1.6,1.6,2,1,0.73,1.2,0.9,1.2,0.73,2,1.6,1.5,1.4,0.5,1.55,1.2,1.6,2.3,3.1,1.8,1,2.3,1,2,0.9,1.4,0.85,1.6,1.8,2,1,1.5,1.3,1.9,1.2,1.1,0.4],[1.91,1.13,1.96,1.24,1.15,1.28,1.31,0.8100000000000001,1.78,1.15,1.24,2.34,1.48,0.9,1.73,1.93,1.1,1.41,1.42,1.48,2,1.62,0.87,0.9,1.65,1.2,1.38,1.58,1.8,0.9,1.97,1.52,1.43,0.87,1.04,1.4,1.73,1.6,0.98,0.7,3.41,0.84,1.54,1.98,1.1,1.21,0.95,1.69,2,0.95,1.1,1.19,1.06,1.73,1.58,1.24,1.87,1,0.7,1.12,0.85,1,0.68,1.77,1.31,1.33,1.25,0.41,1.41,1.06,1.46,1.97,2.51,1.56,0.96,2.19,0.93,2,0.84,1.4,0.85,1.6,1.65,1.69,0.57,1.5,1.11,1.52,0.73,0.9399999999999999,0.4]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>Rubro<\/th>\n      <th>Año<\/th>\n      <th>Municipio<\/th>\n      <th>Área total (ha)<\/th>\n      <th>Área producción (ha)<\/th>\n      <th>Producción (ton)<\/th>\n      <th>Productividad neta (ton/ha)<\/th>\n      <th>Productividad bruta (ton/ha)<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[2,4,5,6,7,8]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>

## Mapa de áreas sembradas en 2022:

<img src="/es/post/cafe_files/figure-html/unnamed-chunk-5-1.png" width="672" />

## Referencias:

- Datos de obtenidos de https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Areas-cultivadas-y-produccion-agr-cola-en-Antioqui/t2ca-uae5/about_data .
