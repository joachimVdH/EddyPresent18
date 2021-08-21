---
title: Weeklessen
layout: page
---

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.4.0/dist/leaflet.css"
  integrity="sha512-puBpdR0798OZvTTbP4A8Ix/l+A4dHDD0DGqYW6RQ+9jxkRFclaxxQb/SJAWZfWAkuyeQUytO7+7N4QKrDh+drA=="
  crossorigin=""/>
<script src="https://unpkg.com/leaflet@1.4.0/dist/leaflet.js"
  integrity="sha512-QVftwZFqvtRNi0ZyCtsznlKSWOStnDORoefr1enyq5mVL4tmKB3S/EnC3rRJcxCPavG10IcrVGSmPh6Qw5lwrg=="
  crossorigin=""></script>

# Mechelen
<!-- [Download Agenda Mechelen 2020-21 - pdf - 46kb](/flyers/Mechelen_2020-21.pdf){:target="_blank"}   -->

[Basisschool "De Spreeuwen", Battelsesteenweg 259, Mechelen](https://maps.google.be/maps?q=51.030872,4.461348&hl=en&num=1&gl=BE&t=m&z=16){:target="_blank"}  

<table>
<thead>
<tr>
	<th>&nbsp;</th>
	<th>dinsdag</th>
	<th>donderdag</th>
</tr>
</thead>
<tbody>
<tr>
	<td>18:45-20:15</td>
	<td>Halfgevorderden <br>door Eddy Present &amp; Marc Hermans</td>
	<td>Gevorderden <br>door Eddy Present &amp; Marc Hermans</td>
</tr>
<tr>
	<td>20:30-22:00</td>
	<td>Beginners <br>door Eddy Present &amp; Marc Hermans &amp; Nancy Bevers</td>
	<td>Vergevorderd <br>door Eddy Present &amp; Marc Hermans</td>
</tr>
</tbody>
</table>



# Grimbergen
<!-- [Download Agenda Grimbergen 2020-21 - pdf - 46kb](/flyers/Grimbergen_2020-21.pdf){:target="_blank"}  

[Charleroyhoeve, Lierbaan, Grimbergen](https://goo.gl/maps/zuG3MTbFtg82){:target="_blank"}   -->


<table>
<thead>
<tr>
	<th>&nbsp;</th>
	<th>maandag</th>
	<th>woensdag</th>
	<th>vrijdag</th>
</tr>
</thead>
<tbody>
<tr>
	<td>13:30-15:00</td>
	<td>&nbsp;</td>
	<td>&nbsp;</td>
	<td>Vergevorderd <br>door Eddy Present &amp; Anne-Marie Van den Bossche</td>
</tr>
<tr>
	<td>15:15-16:30</td>
	<td>&nbsp;</td>
	<td>&nbsp;</td>
	<td>Beginners (1° deel)<br>door Anne-Marie Van den Bossche</td>
</tr> 
<tr>
	<td>18:45-20:15</td>
	<td>Vergevorderd  <br>door Anne-Marie Van den Bossche</td>
	<td>Vergevorderd <br>door Nancy Bevers</td>
	<td>Halfgevorderd (2° deel)<br>door Anne-Marie Van den Bossche</td>
</tr>
<tr>
	<td>20:30-22:00</td>
	<td>Gevorderden (3° deel)<br>door Anne-Marie Van den Bossche </td>
	<td>Beginners (1° deel)<br>door Nancy Bevers</td>
	<td>Vergevorderd <br>door Eddy Present &amp; Anne-Marie Van den Bossche</td>
</tr>
</tbody>
</table>


Gemakkelijke kledij en platte pantoffeltjes zijn aanbevolen. Iets om te drinken meebrengen is altijd verstandig.

## Lesgelden (BTW inbegrepen)
* per les van 1,5 uur = 15 &euro;
* per 10 beurtenkaart = 135 &euro; 
* 10 beurtenkaart word aangeschaft tijdens de les.


Deze kaart is één kalenderjaar geldig

Een factuur of een bewijs kan verkregen worden.  
Vraag informatie!


<div id="mapid" style="width: 100%; height: 400px;"></div>
<script>
	var mymap = L.map('mapid').setView([50.9889,4.3807], 11);

	L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', {
		attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
		maxZoom: 18,
		id: 'mapbox.streets',
		accessToken: 'pk.eyJ1Ijoiam9hY2hpbXZkaCIsImEiOiJjanR4MDh5b2oyNm5zNDRsbGF6cTM5bzh1In0.OpFnYagI-skcvKS3OxC65w'
	}).addTo(mymap);

	// var markerGrimbergen = L.marker([50.93568, 4.37484]).addTo(mymap);
	//markerGrimbergen.bindPopup("Charleroyhoeve, Lierbaan, Grimbergen").openPopup(); 

	var markerMechelen = L.marker([51.03067, 4.45947]).addTo(mymap);
	markerMechelen.bindPopup("Basisschool De Spreeuwen, Battelsesteenweg 259, Mechelen").openPopup();
</script>
