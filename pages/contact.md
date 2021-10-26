---
permalink: "/contact/"

layout: page-fullwidth
title: "Información de contacto"
meta_title: "Contactar"
subheadline: "Contactar"
teaser: ""

header:
    image_fullwidth: park-lake.jpg
    caption: Algun comentario relevante.
---

<div class="row">

<div class="small-12 large-4 columns">

<h4>E-mail:</h4>
<a href="mailto: restaura@urv.cat?subject=RESTAURA" title="restaura@urv.cat">restaura@urv.cat</a>

<h4>Dirección postal:</h4>
<a href="https://www.geografia.urv.cat/ca/">Departament de Geografia</a><br>
<a href="https://www.urv.cat/">Universitat Rovira i Virgili</a><br>
C/ Joanot Martorell, 15 <br>
43480 - Vila-seca (Tarragona) <br>
España

</div>

<div class="small-12 large-8 columns">


<html>
<head>
	
	<title>Quick Start - Leaflet</title>

	<meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	
	<link rel="shortcut icon" type="image/x-icon" href="docs/images/favicon.ico" />

    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A==" crossorigin=""/>
    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>


	
</head>
<body>
<div id="mapid" style="width: 100%; height: 400px;"></div>
<script>

       var mymap = L.map('mapid', {
            zoomControl:true, maxZoom:28, minZoom:1
        }).fitBounds([[41.10188530474122,1.146026661908157],[41.103289521850144,1.149400214972932]]);


	L.tileLayer('http://{s}.google.com/vt/lyrs=s,h&x={x}&y={y}&z={z}', {
        maxZoom: 18,
        minZoom: 2,
        subdomains: ['mt0', 'mt1', 'mt2', 'mt3'],
    }).addTo(mymap);

	L.marker([41.10248, 1.14790]).addTo(mymap)
		.bindPopup("<b>Facultat de Turismo y Geografía</b><br />Universitat Rovira i Virgili").openPopup();

	var popup = L.popup();

</script>

</body>
</html>


</div>

