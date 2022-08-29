---
title: "Mercado de Valores en Uruguay"
subtitle: "Análisis de la última década"
excerpt: "Con el resurgimiento de la Comisión de Promoción del Mercado de Valores, se ha vuelto a poner en la mesa la importancia para el país de tener un mercado de valores fuerte y dinámico, que permita a los distintos agentes de la economía, financiarse por medio de la emisión de títulos. El objetivo del presente artículo es analizar el comportamiento del mercado de valores en la última década, haciendo un análisis de algunas variables que nos permitan generar algunos insights relevantes sobre lo que ha sucedido la pasada década."
date: 2021-07-27
author: "Diego Rijos"
draft: false
# layout options: single, single-sidebar
layout: single
categories:
- R
- Finanzas
- Mercado de Valores
---

<script src="{{< blogdown/postref >}}index_files/htmlwidgets/htmlwidgets.js"></script>
<script src="{{< blogdown/postref >}}index_files/jquery/jquery.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/dygraphs/dygraph.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/dygraphs/dygraph-combined.js"></script>
<script src="{{< blogdown/postref >}}index_files/dygraphs/shapes.js"></script>
<script src="{{< blogdown/postref >}}index_files/moment/moment.js"></script>
<script src="{{< blogdown/postref >}}index_files/moment-timezone/moment-timezone-with-data.js"></script>
<script src="{{< blogdown/postref >}}index_files/moment-fquarter/moment-fquarter.min.js"></script>
<script src="{{< blogdown/postref >}}index_files/dygraphs-binding/dygraphs.js"></script>

## 1. Breve introducción

Con el resurgimiento de la Comisión de Promoción del Mercado de Valores, se ha vuelto a poner en la mesa la importancia para el país de tener un mercado de valores fuerte y dinámico, que permita a los distintos agentes de la economía, financiarse por medio de la emisión de títulos. El objetivo del presente artículo es analizar el comportamiento del mercado de valores en la última década, haciendo un análisis de algunas variables que nos permitan generar algunos insights relevantes sobre lo que ha sucedido la pasada década. Para ello, haremos un pequeño repaso de variables macrofinancieras relevantes en la última década, como forma de poner en contexto la operativa del mercado de valores. Luego de esto se analizará el mercado bursátil en Uruguay, y como ha evolucionado en la última década. Finalmente, como forma de darle un cierre al análisis se presentarán las perspectivas futuras y las líneas de trabajo que están llevando adelante la CPMV en conjunto con actores relevantes del sector.

## 2. Uruguay: Los últimos 10 años

### 2.1 Perspectiva General

La economía uruguaya en los últimos 10 años ha enfrentado ciertas dificultades en el crecimiento de su economía. Si bien, las tasas de crecimiento han sido positivas en gran parte del período, vemos como el dinamismo de la economía ha ido menguando desde 2010 a la fecha. Un entorno menos favorable para la canasta de exportación de Uruguay en conjunto con menos inversión por parte de los agentes económicos, han tenido como consecuencia un menor dinamismo. 2020 es el primer año del período analizado para el que se observa una tasa de crecimiento de la economía negativa. Este mal desempeño de la economía uruguaya se debe a la crisis económica que ha generado la aparición del COVID-19. Si bien Uruguay no entró en una cuarentena obligatoria, la reducción de la movilidad y de la actividad económica, impactó fuertemente en la economía. Si vemos las previsiones que existen a la fecha por parte del Fondo Monetario Internacional, éstas prevén una recuperación de la economía en 2021, estabilizándose la tasa de crecimiento en el orden del 3%. La [encuesta de expectativas económicas de julio de 2021](https://www.bcu.gub.uy/Estadisticas-e-Indicadores/Encuesta%20de%20Expectativas%20Econmicas/iees06i0721.pdf), muestra un comportamiento similar, por lo que los analistas locales estan esperando un crecimiento muy cercano al previsto por el IMF. De todas maneras, el último [informe trimestral en 2021](https://www.bcu.gub.uy/Estadisticas-e-Indicadores/Cuentas%20Nacionales/Informe%20de%20Cuentas%20Nacionales%20Trimestrales_2021_01.pdf) , ha mostrado signos que la economía no se estaría recuperando tan vigorosamente como se preveía.

<div id="htmlwidget-1" style="width:768px;height:240px;" class="dygraphs html-widget"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"attrs":{"title":"Tasa de Crecimiento PIB 2010-2024","xlabel":"Año","ylabel":"Tasa de Crecimiento","labels":["Year","Tasa de crecimiento PIB","Forecast IMF","Forecast BCU","Forecast Itaú BBA"],"retainDateWindow":false,"axes":{"x":{"pixelsPerLabel":60,"drawAxis":true},"y":{"drawAxis":true}},"stackedGraph":false,"fillGraph":false,"fillAlpha":0.15,"stepPlot":false,"drawPoints":false,"pointSize":1,"drawGapEdgePoints":false,"connectSeparatedPoints":false,"strokeWidth":1,"strokeBorderColor":"white","colorValue":0.5,"colorSaturation":1,"includeZero":false,"drawAxesAtZero":false,"logscale":false,"axisTickSize":3,"axisLineColor":"black","axisLineWidth":0.3,"axisLabelColor":"black","axisLabelFontSize":14,"axisLabelWidth":60,"drawGrid":false,"gridLineWidth":0.3,"rightGap":5,"digitsAfterDecimal":2,"labelsKMB":false,"labelsKMG2":false,"labelsUTC":false,"maxNumberWidth":6,"animatedZooms":false,"mobileDisableYTouch":true,"disableZoom":false,"legend":"auto","labelsDivWidth":700,"labelsShowZeroValues":true,"labelsSeparateLines":false,"hideOverlayOnMouseOut":true},"annotations":[],"shadings":[],"events":[],"format":"numeric","data":[[2010,2011,2012,2013,2014,2015,2016,2017,2018,2019,2020,2021,2022,2023,2024,2025],[7.80340965525524,5.1621330218269,3.5381787224,4.63753862983948,3.2387912285196,0.37074125634264,1.68979816160051,2.59133869196167,1.62008362892945,0.222121727878545,-5.9,null,null,null,null,null],[null,null,null,null,null,null,null,null,null,null,-5.9,3,3.1,2.7,2.6,2.3],[null,null,null,null,null,null,null,null,null,null,-5.9,2.55,3.15,2.82,null,null],[null,null,null,null,null,null,null,null,null,null,-5.9,3,2.5,null,null,null]],"fixedtz":false,"tzone":""},"evals":[],"jsHooks":[]}</script>

Elaboración propia en base a Banco Mundial, IMF, BCU, Itaú BBA

Si analizamos la composición del PIB por sectores, se puede observar como uno de los sectores de mayor peso en la economía han sido los servicios, seguido por la industria y el comercio.
