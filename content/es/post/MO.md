---
title: "Municipios con mas y menos contenido de materia orgánica del suelo según la base de datos abierta de Agrosavia."
author: Jose Luis Munera Echeverri
featured_image: "/images/mo.png"
output:
  html_document: 
    toc: yes
    toc_depth: 4
    toc_float: true
date: "2023-11-24"
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
<script src="/rmarkdown-libs/htmlwidgets/htmlwidgets.js"></script>
<link href="/rmarkdown-libs/datatables-css/datatables-crosstalk.css" rel="stylesheet" />
<script src="/rmarkdown-libs/datatables-binding/datatables.js"></script>
<script src="/rmarkdown-libs/jquery/jquery-3.6.0.min.js"></script>
<link href="/rmarkdown-libs/dt-core/css/jquery.dataTables.min.css" rel="stylesheet" />
<link href="/rmarkdown-libs/dt-core/css/jquery.dataTables.extra.css" rel="stylesheet" />
<script src="/rmarkdown-libs/dt-core/js/jquery.dataTables.min.js"></script>
<link href="/rmarkdown-libs/crosstalk/css/crosstalk.min.css" rel="stylesheet" />
<script src="/rmarkdown-libs/crosstalk/js/crosstalk.min.js"></script>

## Introducción

La materia orgánica del suelo es el reservorio de carbono mas grande de la superficie terrestre, despues de los oceanos. La materia orgánica del suelo tambien es un factor crucial que determina la calidad del suelo. La base de datos de análisis de suelos de Agrosavia es una importante fuente de informacion para conocer las propiedades del suelo a nivel nacional en Colombia. En esta publicacion se muestra la distribucion a nivel nacional de la materia orgánica del suelo por municipio, y dos tablas con los municipios que mas y menos registran materia organica en el suelo.

## Mapa de la materia orgánica del suelo por municipio

Agrosavia ha puesto a disposición los datos de los análisis de suelos hechos en su laboratorio de fertilidad de suelos ( https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Resultados-de-An-lisis-de-Laboratorio-Suelos-en-Co/ch4u-f3i5 ).
Estos datos provienen de las muestras que agricultores de todo el país han enviado a Agrosavia para análisis de fertilidad de suelos. La Última actualización de datos fue en 2020.

<div class="figure">

<img src="/es/post/MO_files/figure-html/unnamed-chunk-1-1.png" alt="Mapa del contenido de materia orgánica del suelo (%) por Municipio." width="672" />
<p class="caption">
<span id="fig:unnamed-chunk-1"></span>Figure 1: Mapa del contenido de materia orgánica del suelo (%) por Municipio.
</p>

</div>

## Municipios con menor contenido

En esta tabla se incluyen los municipios con menos de 1.5% de materia orgánica y que tienen mas de 20 analisis disponibles en la base de datos.

<div class="datatables html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-1" style="width:100%;height:auto;"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"filter":"none","vertical":false,"data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28"],["CICUCO","SAN BENITO","CHIRIGUANÁ","SAN BERNARDO DEL VIENTO","GUAMAL","RIOHACHA","MAGANGUÉ","VILLANUEVA","MONTERREY","CARTAGENA DEL CHAIRÁ","GUAMO","TIBÚ","CURUMANÍ","TAURAMENA","SANTA MARTA","CAMPO DE LA CRUZ","CANDELARIA","TAME","PURIFICACIÓN","TENERIFE","TIERRALTA","PUERTO ESCONDIDO","SARAVENA","CURITÍ","AGUAZUL","DIBULLA","PIEDRAS","SAN SEBASTIÁN DE BUENAVISTA"],["BOLÍVAR","SUCRE","CESAR","CÓRDOBA","MAGDALENA","LA GUAJIRA","BOLÍVAR","SANTANDER","CASANARE","CAQUETÁ","TOLIMA","NORTE DE SANTANDER","CESAR","CASANARE","MAGDALENA","ATLÁNTICO","ATLÁNTICO","ARAUCA","TOLIMA","MAGDALENA","CÓRDOBA","CÓRDOBA","ARAUCA","SANTANDER","CASANARE","LA GUAJIRA","TOLIMA","MAGDALENA"],[0.9285765789801149,0.9294928992959149,1.076567632497502,1.159223058810889,1.199215708523533,1.20547860723586,1.212861059463274,1.23317222645948,1.246443198933877,1.271968243969937,1.28771817411716,1.327856241519348,1.329647149976234,1.341847532730044,1.351120055533657,1.354161900411756,1.374129679343718,1.389614036419552,1.413280065111909,1.426601472968987,1.429956204884226,1.458,1.464038817605409,1.477503037869773,1.478901614069481,1.479071122263269,1.490185463741335,1.491497132330823],[0.8673665985839391,0.4135220870219231,0.648791650863116,0.635899592002095,0.5157291226367885,0.5817504880327262,0.6345307266320377,0.2651975349096768,0.6150954901611475,0.4857269209631451,0.737408511786273,0.5733997690105012,0.9091430251879558,0.55395639926871,0.6530614783103118,0.5492286849450084,0.5010509077112889,0.65913145829194,0.4615944163462757,0.549192529570366,0.6648900824478738,0.7065135379526317,0.6855334888074412,1.093073955254561,0.7145675392507914,0.9599840700089159,0.4281038888530219,0.7406355636359249],[100,23,56,30,34,28,165,39,74,25,22,30,46,42,40,38,114,49,28,33,243,30,59,44,108,43,38,34]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>MPIO_CNMBR<\/th>\n      <th>Departamento<\/th>\n      <th>Mat.Org<\/th>\n      <th>ds_MO<\/th>\n      <th>n<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[3,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>

## Municipios con mayor contenido

En esta tabla se incluyen los municipios con mas de 10% de materia orgánica y que tienen mas de 20 analisis disponibles en la base de datos.

<div class="datatables html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-2" style="width:100%;height:auto;"></div>
<script type="application/json" data-for="htmlwidget-2">{"x":{"filter":"none","vertical":false,"data":[["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23","24","25","26","27","28","29","30","31","32","33","34","35","36","37","38","39","40","41","42","43","44","45","46","47","48","49","50","51","52","53","54","55","56","57","58","59","60","61","62"],["SAN MIGUEL DE SEMA","SUBACHOQUE","TAUSA","SIBATÉ","SAN PEDRO","GRANADA","RIONEGRO","VENTAQUEMADA","CAJIBÍO","SAN FRANCISCO","EL PEÑOL","PIENDAMÓ","SANTIAGO","ZIPAQUIRÁ","CABRERA","ABEJORRAL","NARIÑO","EL TAMBO","SABOYÁ","TENJO","ISNOS","LA UNIÓN","GUACHUCAL","LA CEJA","CARMEN DE CARUPA","POPAYÁN","GUATAVITA","FACATATIVÁ","TIMBÍO","SESQUILÉ","UBAQUE","CUMBAL","ARCABUCO","MORALES","SAN VICENTE FERRER","RAMIRIQUÍ","CALDAS","RETIRO","SUSA","CIÉNEGA","JARDÍN","ENTRERRÍOS","TANGUA","LA CALERA","FUNZA","DONMATÍAS","BOJACÁ","VENECIA","TUTAZÁ","VILLAPINZÓN","COLÓN","FRESNO","COGUA","GUASCA","TABIO","EL ÁGUILA","CHOCONTÁ","TUNJA","SAN PEDRO DE LOS MILAGROS","SAN FRANCISCO","CHIQUINQUIRÁ","SIBUNDOY"],["BOYACÁ","CUNDINAMARCA","CUNDINAMARCA","CUNDINAMARCA","ANTIOQUIA","CUNDINAMARCA","ANTIOQUIA","BOYACÁ","CAUCA","PUTUMAYO","ANTIOQUIA","CAUCA","PUTUMAYO","CUNDINAMARCA","CUNDINAMARCA","ANTIOQUIA","NARIÑO","CAUCA","BOYACÁ","CUNDINAMARCA","HUILA","ANTIOQUIA","NARIÑO","ANTIOQUIA","CUNDINAMARCA","CAUCA","CUNDINAMARCA","CUNDINAMARCA","CAUCA","CUNDINAMARCA","CUNDINAMARCA","NARIÑO","BOYACÁ","CAUCA","ANTIOQUIA","BOYACÁ","BOYACÁ","ANTIOQUIA","CUNDINAMARCA","BOYACÁ","ANTIOQUIA","ANTIOQUIA","NARIÑO","CUNDINAMARCA","CUNDINAMARCA","ANTIOQUIA","CUNDINAMARCA","CUNDINAMARCA","BOYACÁ","CUNDINAMARCA","PUTUMAYO","TOLIMA","CUNDINAMARCA","CUNDINAMARCA","CUNDINAMARCA","VALLE DEL CAUCA","CUNDINAMARCA","BOYACÁ","ANTIOQUIA","CUNDINAMARCA","BOYACÁ","PUTUMAYO"],[21.14714321707221,20.61481605183359,19.01419135505489,17.59112756987914,17.51699632111171,17.11186667132916,15.65972089271831,15.45589790901783,15.2234239961708,14.80239902575316,14.77818934917612,14.49174466094886,14.48913994990935,14.07447960312501,13.76504747061573,13.7493294295764,13.57496852149617,13.55762820214193,13.47528438809,13.34616246019664,13.31240589364857,13.3057213161496,13.2969119473922,13.10721570450377,12.99288051904613,12.93135986171856,12.8988744160778,12.89750858909671,12.76707139968122,12.68889168895918,12.65435817609674,12.53624893961855,12.3423836090198,12.29445028562933,12.28580085308768,12.23315624316118,12.20306112926882,12.12586194943994,12.07876062783786,11.82629798114482,11.76493028058984,11.73715227051525,11.7148206572046,11.70677785549691,11.6706884100025,11.53021075652143,11.13794712505084,11.09132042063,10.96626002586463,10.94829634175908,10.85204801764637,10.80938661786577,10.7661783858253,10.55252830291909,10.50998023800409,10.43236089327426,10.27906208306717,10.27070414182414,10.23045708153321,10.19258449134657,10.13978178744425,10.05126817804952],[17.61358465552193,7.71292651353033,6.495202381801123,7.000593273505172,6.922428401777029,4.517904715514889,8.828054753477714,6.130749636176392,5.43535286426327,8.554161624680505,6.066561373725893,5.895698023647476,12.23085345650061,7.794465535785571,7.829229666373597,4.579093285061297,6.908352920511949,5.469327073348183,5.844113449344479,5.744666777564502,6.948233899984179,5.279706189809269,6.126383913752343,2.896430328325837,7.927477031126857,6.780003384806284,8.46659613192141,7.320023807959633,4.380404185320955,5.900962838046927,7.005002754514101,5.542755414583358,5.44862320232426,4.958304123266305,4.316380754068094,5.4343683594883,5.348397310622993,5.268213613576543,7.009872536527262,3.748951441816545,4.144936814954435,4.78691622579639,7.756058346914109,5.605349332938103,5.90453773839142,4.366994101703346,6.026289849702309,5.923726644022251,4.010858780235504,6.042553112560726,8.122861622229431,3.780298918912657,6.33299688808537,7.950591432544235,6.069096017053257,4.549584258743406,6.345308440354427,6.096755293127122,5.832011476579241,5.562910395496057,6.742508930150816,6.007466657782797],[71,55,94,109,43,76,545,67,47,56,59,37,39,22,38,44,39,73,60,27,27,51,109,23,128,46,106,72,42,49,28,50,56,69,45,42,66,52,65,33,43,54,23,84,51,59,65,95,31,36,38,102,35,144,22,146,156,24,72,49,106,49]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>MPIO_CNMBR<\/th>\n      <th>Departamento<\/th>\n      <th>Mat.Org<\/th>\n      <th>ds_MO<\/th>\n      <th>n<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[3,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>

## Referencias:

- Agrosavia ( https://www.agrosavia.co/ ).
- Datos de análisis de suelos utilizados en el proyecto ( https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/Resultados-de-An-lisis-de-Laboratorio-Suelos-en-Co/ch4u-f3i5 ).
