---
layout: page
section: Travel
title: Travel
---

<h1>Visited States</h1>
<script src="http://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script><script src="http://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="http://www.amcharts.com/lib/3/maps/js/usaHigh.js" type="text/javascript"></script>

<div id="mapdiv" style="width: 700px; height: 450px;"></div>

&nbsp;

<h1>Visited Countries</h1>

&nbsp;

<div id="mapdiv2" style="width: 700px; height: 450px;"></div>

<h1>Work Travel Mapped</h1>
<iframe src="https://www.google.com/maps/d/embed?mid=1CE8QEHcXoDB7x7xEa3sG6wUwEDU" width="640" height="480"></iframe>

<script type="text/javascript">// <![CDATA[
(function () { var map; AmCharts.ready(function() { map = new AmCharts.AmMap(); map.pathToImages = "http://www.amcharts.com/lib/3/images/"; map.panEventsEnabled = true; map.backgroundColor = "#666666"; map.backgroundAlpha = 1; map.zoomControl.panControlEnabled = true; map.zoomControl.zoomControlEnabled = true; var dataProvider = { mapVar : AmCharts.maps.usaHigh, getAreasFromMap : true, areas : [ { id: 'US-AR', showAsSelected: true }, { id: 'US-CA', showAsSelected: true }, { id: 'US-CO', showAsSelected: true }, { id: 'US-FL', showAsSelected: true }, { id: 'US-GA', showAsSelected: true }, { id: 'US-IL', showAsSelected: true }, { id: 'US-IN', showAsSelected: true }, { id: 'US-IA', showAsSelected: true }, { id: 'US-ME', showAsSelected: true }, { id: 'US-MA', showAsSelected: true }, { id: 'US-MI', showAsSelected: true }, { id: 'US-MN', showAsSelected: true }, { id: 'US-MO', showAsSelected: true }, { id: 'US-NH', showAsSelected: true }, { id: 'US-ND', showAsSelected: true }, { id: 'US-OH', showAsSelected: true }, { id: 'US-OR', showAsSelected: true }, { id: 'US-PA', showAsSelected: true }, { id: 'US-TX', showAsSelected: true }, { id: 'US-WA', showAsSelected: true }, { id: 'US-WI', showAsSelected: true } ] }; map.dataProvider = dataProvider; map.areasSettings = { autoZoom : true, color : "#CDCDCD", colorSolid : "#5EB7DE", selectedColor : "#5EB7DE", outlineColor : "#666666", rollOverColor : "#88CAE7", rollOverOutlineColor : "#FFFFFF" }; map.write("mapdiv"); }); }()); (function () { var map2; AmCharts.ready(function() { map2 = new AmCharts.AmMap(); map2.pathToImages = "http://www.amcharts.com/lib/3/images/"; map2.panEventsEnabled = true; map2.backgroundColor = "#666666"; map2.backgroundAlpha = 1; map2.zoomControl.panControlEnabled = true; map2.zoomControl.zoomControlEnabled = true; var dataProvider = { mapVar: AmCharts.maps.worldHigh, getAreasFromMap: true, areas: [ { id: 'AT', showAsSelected: true }, { id: 'CA', showAsSelected: true }, { id: 'DE', showAsSelected: true }, { id: 'ES', showAsSelected: true }, { id: 'FR', showAsSelected: true }, { id: 'IS', showAsSelected: true }, { id: 'MX', showAsSelected: true }, { id: 'NI', showAsSelected: true }, { id: 'PA', showAsSelected: true }, { id: 'US', showAsSelected: true } ] }; map2.dataProvider = dataProvider; map2.areasSettings = { autoZoom: true, color: "#CDCDCD", colorSolid: "#5EB7DE", selectedColor: "#5EB7DE", outlineColor: "#666666", rollOverColor: "#88CAE7", rollOverOutlineColor: "#FFFFFF" }; map2.write("mapdiv2"); }); }());
// ]]></script>