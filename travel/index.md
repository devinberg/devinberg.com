---
layout: page
section: Travel
title: Travel
---

<h1>Visited States</h1>
<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/usaHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/light.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 1000px; height: 450px;"></div>
<div style="width: 1000px; font-size: 70%; padding: 5px 0; text-align: center; background-color: #535364; margin-top: 1px; color: #B4B4B7;"><a href="https://www.amcharts.com/visited_states/" style="color: #B4B4B7;">Create your own visited states map</a> or check out the <a href="https://www.amcharts.com/" style="color: #B4B4B7;">JavaScript Charts</a>.</div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "light",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "usaHigh",
getAreasFromMap : true,
areas :
[]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>


&nbsp;

<h1>Visited Countries</h1>

&nbsp;

<div id="mapdiv2" style="width: 700px; height: 450px;"></div>

<h1>Work Travel Mapped</h1>
<iframe src="https://www.google.com/maps/d/embed?mid=1CE8QEHcXoDB7x7xEa3sG6wUwEDU" width="640" height="480"></iframe>



<!--<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv2",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
{ id: 'AT', showAsSelected: true }, { id: 'CA', showAsSelected: true }, { id: 'DE', showAsSelected: true }, { id: 'ES', showAsSelected: true }, { id: 'FR', showAsSelected: true }, { id: 'IE', showAsSelected: true }, { id: 'IS', showAsSelected: true }, { id: 'GB', showAsSelected: true }, { id: 'MX', showAsSelected: true }, { id: 'NI', showAsSelected: true }, { id: 'PA', showAsSelected: true }, { id: 'PE', showAsSelected: true }, { id: 'US', showAsSelected: true }
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>-->