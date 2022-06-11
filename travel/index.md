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
[
	{
		"id": "US-AR",
		"showAsSelected": true
	},
	{
		"id": "US-CA",
		"showAsSelected": true
	},
	{
		"id": "US-CO",
		"showAsSelected": true
	},
	{
		"id": "US-DC",
		"showAsSelected": true
	},
	{
		"id": "US-FL",
		"showAsSelected": true
	},
	{
		"id": "US-GA",
		"showAsSelected": true
	},
	{
		"id": "US-IA",
		"showAsSelected": true
	},
	{
		"id": "US-IL",
		"showAsSelected": true
	},
	{
		"id": "US-IN",
		"showAsSelected": true
	},
	{
		"id": "US-KY",
		"showAsSelected": true
	},
	{
		"id": "US-LA",
		"showAsSelected": true
	},
	{
		"id": "US-MA",
		"showAsSelected": true
	},
	{
		"id": "US-MD",
		"showAsSelected": true
	},
	{
		"id": "US-ME",
		"showAsSelected": true
	},
	{
		"id": "US-MI",
		"showAsSelected": true
	},
	{
		"id": "US-MN",
		"showAsSelected": true
	},
	{
		"id": "US-MO",
		"showAsSelected": true
	},
	{
		"id": "US-NC",
		"showAsSelected": true
	},
	{
		"id": "US-ND",
		"showAsSelected": true
	},
	{
		"id": "US-NH",
		"showAsSelected": true
	},
	{
		"id": "US-NJ",
		"showAsSelected": true
	},
	{
		"id": "US-NY",
		"showAsSelected": true
	},
	{
		"id": "US-OH",
		"showAsSelected": true
	},
	{
		"id": "US-OR",
		"showAsSelected": true
	},
	{
		"id": "US-PA",
		"showAsSelected": true
	},
	{
		"id": "US-SC",
		"showAsSelected": true
	},
	{
		"id": "US-TN",
		"showAsSelected": true
	},
	{
		"id": "US-TX",
		"showAsSelected": true
	},
	{
		"id": "US-UT",
		"showAsSelected": true
	},
	{
		"id": "US-VA",
		"showAsSelected": true
	},
	{
		"id": "US-WA",
		"showAsSelected": true
	},
	{
		"id": "US-WI",
		"showAsSelected": true
	}
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
</script>


&nbsp;

<h1>Visited Countries</h1>

&nbsp;

<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>

<div id="mapdiv2" style="width: 1000px; height: 450px;"></div>

<script type="text/javascript">
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
	{
		"id": "AR",
		"showAsSelected": true
	},
	{
		"id": "AT",
		"showAsSelected": true
	},
	{
		"id": "BE",
		"showAsSelected": true
	},
	{
		"id": "FR",
		"showAsSelected": true
	},
	{
		"id": "DE",
		"showAsSelected": true
	},
	{
		"id": "CL",
		"showAsSelected": true
	},
	{
		"id": "IS",
		"showAsSelected": true
	},
	{
		"id": "IE",
		"showAsSelected": true
	},
	{
		"id": "ES",
		"showAsSelected": true
	},
	{
		"id": "GB",
		"showAsSelected": true
	},
	{
		"id": "CA",
		"showAsSelected": true
	},
	{
		"id": "MX",
		"showAsSelected": true
	},
	{
		"id": "NI",
		"showAsSelected": true
	},
	{
		"id": "PA",
		"showAsSelected": true
	},
	{
		"id": "US",
		"showAsSelected": true
	},
	{
		"id": "PE",
		"showAsSelected": true
	}
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
</script>


<h1>Work Travel Mapped</h1>
<iframe src="https://www.google.com/maps/d/embed?mid=1CE8QEHcXoDB7x7xEa3sG6wUwEDU" width="640" height="480"></iframe>

