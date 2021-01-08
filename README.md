# mapbox-route-highlight

## [Route planner with toilets](https://captmomo.github.io/mapbox-route-highlight/toilet/index.html)  

No more shitting your pants! :) Finally, a route planner which highlights the toilets along the route!
Always wanted to make something like this, so decided to try it out! Double click to set a point, only works for Singapore though.

kudos to cerivitos for the geojson; https://github.com/cerivitos/INeedToilet

## [Optimized Route Planner - highlights Muis Halal Certified Eating Establishments along the route](https://captmomo.github.io/mapbox-route-highlight/muis-halal/index.html)  
  
Restaurant data liberated from the [MUIS HALAL CERTIFIED EATING ESTABLISHMENTS](https://www.muis.gov.sg/-/media/Files/Halal/Documents/EE-List-5-Dec-18-v2.pdf) using [tabula](https://github.com/tabulapdf/tabula)  
  
Data cleaned using pandas and then geocoded using arcgis geocoding api and this [site](https://geocode.localfocus.nl/)  
  
Double click to set a point, the first point will be the start and final point is the destination.
  
[Route generated using Mapbox Optimization API](https://docs.mapbox.com/help/tutorials/optimization-api/)

![screenshot](muis-halal/sample.png)
 
