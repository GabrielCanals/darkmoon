```leaflet  
id: GolarionMap ### Must be unique with no spaces  
image: [[golarion_map.jpg]] ### Link to the map image file  
bounds: [[0,0], [15945, 9686]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 1500px ### Size of the leaflet embed in px on your screen  
width: 1300px ### Size of the leaflet embed in your note  
lat: 7000 ### To center the map, make this half of the map height.  
long: 5000 ### To center the map, make this half of the map width.  
minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 2 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -2 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.258 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```

