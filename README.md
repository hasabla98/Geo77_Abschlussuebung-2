# Geo77_Abschlussuebung-2
 
 <!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
   integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
   crossorigin=""/>
	<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
   integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
   crossorigin=""></script>
	<script src="HH.js"></script>
</head>
<body>
<h1>Windkraft im Regierungsbezirk Tübingen</h1>
<p>Veränderung der Potentialflächen <a href="https://hasabla98.github.io/Geo77_Abschlussuebung-2/">hasabla</a>.</p>
<div id="mapid" style="width: 600px; height: 400px; position: relative;"></div>
<script>
 var mymap = L.map('mapid').setView([48.2, 9.5]).setZoom(9);
 L.tileLayer('https://{s}.tile.openstreetmap.de/tiles/osmde/{z}/{x}/{y}.png').addTo(mymap);
 var overlay_abstand_hamburg = L.geoJSON(abstand_hamburg).addTo(mymap);
 var OpenStreetMap_DE = L.tileLayer('https://{s}.tile.openstreetmap.de/tiles/osmde/{z}/{x}/{y}.png', {
 attribution: '<a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
});
</script>
<script src="C:\Users\Christoph\Documents\Uni Tübingen\Master\1. Semester\Geo77\Abschlussübung\Potenzialanalyse Windkraftanlage\Geo77_Abschlussuebung-2"></script>
</body>
</html>
