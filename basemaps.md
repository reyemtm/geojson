admin boundaries


var OpenMapSurfer_AdminBounds = L.tileLayer('http://openmapsurfer.uni-hd.de/tiles/adminb/x={x}&y={y}&z={z}', {
	minZoom: 0,
	maxZoom: 19,
	attribution: 'Imagery from <a href="http://giscience.uni-hd.de/">GIScience Research Group @ University of Heidelberg</a> &mdash; Map data &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
});

grayscale::

var OpenStreetMap_BlackAndWhite = L.tileLayer('http://{s}.tiles.wmflabs.org/bw-mapnik/{z}/{x}/{y}.png', {
	attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
});

var Esri_WorldGrayCanvas = L.tileLayer('http://server.arcgisonline.com/ArcGIS/rest/services/Canvas/World_Light_Gray_Base/MapServer/tile/{z}/{y}/{x}', {
	attribution: 'Tiles &copy; Esri &mdash; Esri, DeLorme, NAVTEQ',
	maxZoom: 16
});

not quite so black and white:

var Thunderforest_Transport = L.tileLayer('http://{s}.tile.thunderforest.com/transport/{z}/{x}/{y}.png', {
	attribution: '&copy; <a href="http://www.opencyclemap.org">OpenCycleMap</a>, &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
});

var HERE_normalDayGrey = L.tileLayer('http://{s}.{base}.maps.cit.api.here.com/maptile/2.1/maptile/{mapID}/normal.day.grey/{z}/{x}/{y}/256/png8?app_id={app_id}&app_code={app_code}', {
	attribution: 'Map &copy; 1987-2014 <a href="http://developer.here.com">HERE</a>',
	subdomains: '1234',
	mapID: 'newest',
	app_id: '<insert your app_id here>',
	app_code: '<insert your app_code here>',
	base: 'base',
	minZoom: 0,
	maxZoom: 20
});

var HERE_normalDayGreyMobile = L.tileLayer('http://{s}.{base}.maps.cit.api.here.com/maptile/2.1/maptile/{mapID}/normal.day.grey.mobile/{z}/{x}/{y}/256/png8?app_id={app_id}&app_code={app_code}', {
	attribution: 'Map &copy; 1987-2014 <a href="http://developer.here.com">HERE</a>',
	subdomains: '1234',
	mapID: 'newest',
	app_id: '<insert your app_id here>',
	app_code: '<insert your app_code here>',
	base: 'base',
	minZoom: 0,
	maxZoom: 20
});

var HERE_normalDayTransitMobile = L.tileLayer('http://{s}.{base}.maps.cit.api.here.com/maptile/2.1/maptile/{mapID}/normal.day.transit.mobile/{z}/{x}/{y}/256/png8?app_id={app_id}&app_code={app_code}', {
	attribution: 'Map &copy; 1987-2014 <a href="http://developer.here.com">HERE</a>',
	subdomains: '1234',
	mapID: 'newest',
	app_id: '<insert your app_id here>',
	app_code: '<insert your app_code here>',
	base: 'base',
	minZoom: 0,
	maxZoom: 20
});

cool topo:

var Thunderforest_OpenCycleMap = L.tileLayer('http://{s}.tile.thunderforest.com/cycle/{z}/{x}/{y}.png', {
	attribution: '&copy; <a href="http://www.opencyclemap.org">OpenCycleMap</a>, &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
});

var Esri_WorldTopoMap = L.tileLayer('http://server.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer/tile/{z}/{y}/{x}', {
	attribution: 'Tiles &copy; Esri &mdash; Esri, DeLorme, NAVTEQ, TomTom, Intermap, iPC, USGS, FAO, NPS, NRCAN, GeoBase, Kadaster NL, Ordnance Survey, Esri Japan, METI, Esri China (Hong Kong), and the GIS User Community'
});

a good basemap with topo and road labels:

var Thunderforest_Landscape = L.tileLayer('http://{s}.tile.thunderforest.com/landscape/{z}/{x}/{y}.png', {
	attribution: '&copy; <a href="http://www.opencyclemap.org">OpenCycleMap</a>, &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
});


minimalist theme:

var Hydda_Full = L.tileLayer('http://{s}.tile.openstreetmap.se/hydda/full/{z}/{x}/{y}.png', {
	minZoom: 0,
	maxZoom: 18,
	attribution: 'Tiles courtesy of <a href="http://openstreetmap.se/" target="_blank">OpenStreetMap Sweden</a> &mdash; Map data &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
});

satelite:

var MapQuestOpen_Aerial = L.tileLayer('http://oatile{s}.mqcdn.com/tiles/1.0.0/sat/{z}/{x}/{y}.jpg', {
	attribution: 'Tiles Courtesy of <a href="http://www.mapquest.com/">MapQuest</a> &mdash; Portions Courtesy NASA/JPL-Caltech and U.S. Depart. of Agriculture, Farm Service Agency',
	subdomains: '1234'
});

var Esri_WorldImagery = L.tileLayer('http://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/tile/{z}/{y}/{x}', {
	attribution: 'Tiles &copy; Esri &mdash; Source: Esri, i-cubed, USDA, USGS, AEX, GeoEye, Getmapping, Aerogrid, IGN, IGP, UPR-EGP, and the GIS User Community'
});

w/labels

var HERE_hybridDay = L.tileLayer('http://{s}.{base}.maps.cit.api.here.com/maptile/2.1/maptile/{mapID}/hybrid.day/{z}/{x}/{y}/256/png8?app_id={app_id}&app_code={app_code}', {
	attribution: 'Map &copy; 1987-2014 <a href="http://developer.here.com">HERE</a>',
	subdomains: '1234',
	mapID: 'newest',
	app_id: '<insert your app_id here>',
	app_code: '<insert your app_code here>',
	base: 'aerial',
	minZoom: 0,
	maxZoom: 20
});

terrain:

var Stamen_Terrain = L.tileLayer('http://{s}.tile.stamen.com/terrain/{z}/{x}/{y}.png', {
	attribution: 'Map tiles by <a href="http://stamen.com">Stamen Design</a>, <a href="http://creativecommons.org/licenses/by/3.0">CC BY 3.0</a> &mdash; Map data &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>',
	subdomains: 'abcd',
	minZoom: 4,
	maxZoom: 18
});

var Esri_WorldTopoMap = L.tileLayer('http://server.arcgisonline.com/ArcGIS/rest/services/World_Topo_Map/MapServer/tile/{z}/{y}/{x}', {
	attribution: 'Tiles &copy; Esri &mdash; Esri, DeLorme, NAVTEQ, TomTom, Intermap, iPC, USGS, FAO, NPS, NRCAN, GeoBase, Kadaster NL, Ordnance Survey, Esri Japan, METI, Esri China (Hong Kong), and the GIS User Community'
});
