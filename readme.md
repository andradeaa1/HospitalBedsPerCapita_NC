# Hospital Beds Per Capita Choropleth Map 
This HTML document document produces a choropleth map that shows the distriubiton of staffed general hospital beds across the counties in North Carolina. The data was taken from the State of North Carolina Department of Health and Human Services for the year 2024.
## Design
A choropleth map visualizes data tied to a geographic location, it allows for features to be easily compared and gives insight on data trends. This map used a blue color scale with grey representing the value 0. This was to ensure that counties with 0 beds were clearly marked. Counties with a high ratio of beds were a dark blue to also to contrast the light colors that represented low values.
## Data
The number of beds per captia was calculated by diving the total amounts of general beds in hospitals licensed by NC for each county. The total population for each county was divided by 1000. Then total beds were divded by the population per capita.
## Features
- Interactive Map
- Zoom to layer on click
- Hover over polygons to display information
- Legend to indicate color scale
## Libraries
- Leaflet
- Chroma.js
- jQuery
- leaflet-ajax
## Credit
Hospitals by County; <a href="https://info.ncdhhs.gov/dhsr/data/hllistco.pdf">State of North Carolina Department of Health and Human Services</a> Population by County; <a href="https://worldpopulationreview.com/states/north-carolina/counties"> World Population Review </a>
This map was made by Angela Andrade