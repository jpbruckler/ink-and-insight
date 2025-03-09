---
title: Night City
---


```leaflet 
id: NightCity

# the image is 2160x3723 
image: [[map_nightcity.png]] 

# bounds uses y,x (CRS.Simple) 
# bounds in miles (as per map scale: 100 mi = 85 px) 
bounds: [[0,0], [18.29,10.95]] 

# after this, southwest = 0,0; northeast = 1411.76, 1882.35 
height: 1000px 

# lat/long in percent doesn’t center 
# does ist not respect scale or bounds? 
# would be easier if this was a coordinate in "bounds" range, 
# as the "final" coordinates will be. 
lat: 9
long: 5
minZoom: 1 
maxZoom: 15
defaultZoom: 6
unit: miles
```


