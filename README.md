# leaflet-betterscale
A better scalebar for leaflet maps that is more GIS-like with alternating black/white bars.

## Example
<a href="https://daniellsu.github.io/leaflet-betterscale/">https://daniellsu.github.io/leaflet-betterscale/</a>


All that is required is to include the CSS, the JS and the following line of code:

## Simple example

```javascript
var map = L.map('map').setView([30.182505,-93.318665], 12);        
L.tileLayer('http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {    
		maxZoom: 18,
		attribution:'&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
}).addTo(map);
L.control.betterscale().addTo(map);
```

## Options
- The options are the exact same as the leaflet built-in scale control, <a href="http://leafletjs.com/reference-1.0.0.html#control-scale">L.Control.Scale()</a>.
