<!DOCTYPE html>
<html>
	<p><b><font size = "7", color = "orange"><center>CHUPADEROS DEL JAGUILLO</font></b><br><font size = "5"color = "white">DONDE SE PONE A PIJA ESTE MAJE</font></br>
	<a href="mailto:iriasam@yahoo.com" title="enviar correo a Edwin Irias">Enviar mail</a>
	<p><b><font size = "6", color = "red"><center>SEMANA MORAZÁNICA, 2019</font>
<b><font size = "4", color = "white"><center>Cualquier consulta llameme al 00 (504) 3234-2679</font></b></p>
<font size = "4", color = "green"><center>E-mail "iriasam@yahoo.com" Alias Pocas Pulgas</font>
	<head>
		<meta charset="utf-8"/>
		<title>¡¡Quien dijo miedo¡¡</title>
	
		<!--Leaflet-->
		<link rel="stylesheet" href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css"
		integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
		crossorigin=""/>
  
		<script src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"
		integrity="sha512-GffPMF3RvMeYyc1LWMHtK8EbPv0iNZ8/oTtHPx9/cc2ILxQ+u905qIwdpULaqDkyBKgOaB57QTMg7ztg8Jm2Og=="
		crossorigin="">
  
		</script>
		
		<!--Plugins de Leaflet-->
		<!--MiniMap-->
		<link rel="stylesheet" href="Control.MiniMap.css" />
		<script src="Control.MiniMap.js" type= "text/javascript">
		</script>
	
		<!--Mouse Position-->
		<link rel="stylesheet" href="L.Control.MousePosition.css" />
		<script src="L.Control.MousePosition.js" type= "text/javascript">
		</script>
		
		<!--Full screen-->
		<link rel='stylesheet' href='leaflet.fullscreen.css'  />
		<script src='Leaflet.fullscreen.js'></script>
		
		<!--Map center-->
		<link rel="stylesheet" href="leaflet.viewcenter.css" />
		<script src="leaflet.viewcenter.js"></script>
	</head>
	
	<body>
		<div id="map" style="width: 1200px; height: 700px;"></div>
		<div class='space-bottom'></div>
        <div id='map' class='col12 row10'></div>
		
		<body background="Purples class 3" bgcolor="#000">
		
		<marquee scrolldelay= "25" direction = "down" collamount= "50" height = "150px"><center>
		<img src = "20130713_192418.jpg"/>
		<img src = "20131009_144111.jpg"/>
		<img src = "20131114_123217.jpg"/>
		<img src = "20131114_123229(0).jpg"/>
		<img src = "20150627_091911.jpg"/>
		<script>
	
		var osm = L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', 
		{attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors,<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>', 
		id: 'mapbox.streets', 
		accessToken:'pk.eyJ1IjoicGFibG9jZXNhciIsImEiOiJjazBweThxbmUwMDYyM2xvMjFrb2UwdG82In0.29K56YHY7YuBEHtr3VDdOA',
		maxZoom: 18,
		minZoom: 5,
		keyboard: true
		})
		
			
		var osm2 = L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', 
		{attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors,<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>', 
		id: 'mapbox.streets-satellite', 
		accessToken:'pk.eyJ1IjoicGFibG9jZXNhciIsImEiOiJjazBweThxbmUwMDYyM2xvMjFrb2UwdG82In0.29K56YHY7YuBEHtr3VDdOA',
		maxZoom: 15,
		minZoom: 5,
		keyboard: true
		
		});
		
		var mapa = L.map('map',{
		center: [13.934016, -87.294583],
		zoom:7.2,
		layers: osm,
		zoomControl: false,
		fullscreenControl: {pseudoFullscreen: false, position: 'topleft'
		},
		maxBounds: [[ 16.2461,-82.6817],[    9.7635, -89.834]]
		});
		
			
		
		var plazacentral = L.marker([ 14.0423, -86.5727]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Danli");
		
		var plazacentral = L.marker([  14.0752, -87.1715]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Mi casa");
		
		var sta = L.marker([ 15.7611, -86.8267]);
		mapa.addLayer(sta);
		sta.bindPopup("La Ceiba");
		
		var plazacentral = L.marker([  13.6227, -87.6579]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Casa Lenin Langue");
		
		var plazacentral = L.marker([   13.4739, -88.1729]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("San Miguel, El Salvador");
		
		var plazacentral = L.marker([    13.6265, -86.8771]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Santa Rosa de Lima, El Salvador");
		
		var plazacentral = L.marker([  12.4340, -86.5727]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("León, Nicaragua");
		
		var plazacentral = L.marker([   12.6296, -87.1317]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Chinandega, Nicaragua");
		
		var plazacentral = L.marker([    11.9300, -85.9516]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("La Calzada Granada, Nicaragua");
		
		var plazacentral = L.marker([     11.2555, -85.8716]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("San Juan del Sur, Nicaragua");
		
		var plazacentral = L.marker([   15.7747, -88.0379]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Omoa");
		
		var plazacentral = L.marker([    15.9584, -86.4833]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Cayos Cochinos");
		
		var plazacentral = L.marker([     13.2940, -87.6475]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Amapala");
		
		var plazacentral = L.marker([     15.9211, -85.9526]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Trujillo");
		
		var plazacentral = L.marker([    15.7745, -87.4669]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Tela");
		
		var plazacentral = L.marker([   14.8033, -87.9746]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Lago de Yojoa");
		
		var plazacentral = L.marker([    15.4971, -88.0150]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("San Pedro Sula");
		
		var plazacentral = L.marker([   14.4614, -87.6412]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Zona viva Comayagua");
		
		var plazacentral = L.marker([    14.3278, -87.6758]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("La Paz");
		
		var plazacentral = L.marker([     13.9992, -87.0987]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("Grupo 4X4 Tatumbla");
		
		var sta = L.marker([  13.5897, -87.3617]);
		mapa.addLayer(sta);
		sta.bindPopup("Territorio Jaguillo");
		
		var sta = L.marker([   13.6365, -87.6522]);
		mapa.addLayer(sta);
		sta.bindPopup("Finca el Huevón, Langue");
		
		var sta = L.marker([  14.0528, -87.1804]);
		mapa.addLayer(sta);
		sta.bindPopup("Gol de Oro");
		
		var sta = L.marker([   14.0836, -87.1713]);
		mapa.addLayer(sta);
		sta.bindPopup("Alitas Blvd. Suyapa");
		
		var sta = L.marker([    14.1016, -87.2114]);
		mapa.addLayer(sta);
		sta.bindPopup("El Chiverito");
		
		var sta = L.marker([    14.0510, -87.1886]);
		mapa.addLayer(sta);
		sta.bindPopup("Donde el Primo Lenin");
		
		var sta = L.marker([     14.0515, -87.1903]);
		mapa.addLayer(sta);
		sta.bindPopup("Donde el Maistro Julio");
		
		var sta = L.marker([   14.0756, -87.1497]);
		mapa.addLayer(sta);
		sta.bindPopup("Saucerro");
		
		var inl = L.marker([ 14.8390, -89.1572]);
		mapa.addLayer(inl);
		inl.bindPopup("Copan Ruinas");
		
				
		new L.Control.Zoom({ position: 'topright'}).addTo(mapa);
		
		var miniMap = new L.Control.MiniMap(osm2,{ toggleDisplay: true, position: 'bottomright' }).addTo(mapa);
		var MousePosition = new L.control.mousePosition(osm).addTo(mapa);
		var escala = L.control.scale().addTo(mapa);
		var viewCenter = new L.Control.ViewCenter(mapa);
			mapa.addControl(viewCenter);
		
	</script>
	
	</body>
	
</html>

