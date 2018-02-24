# Pollutant-Mapping


## Goals:

To be able to create an interactive map for visualising data produced by my pollutant sensor. 
This interactive map should be viewable in Home Assistant and show the air quality of an area using a colour scale.
The data will be captured from a Home Assistant REST sensor and the map will update when new data arrives (or soon after).
As the sensor will be moving and pollutant concentration changes with time of day, the map should also have a time slider.

The goal is to produce a map similar to those found at https://www.londonair.org.uk/LondonAir/nowcast.aspx by King's College London.

![King's College London](https://pasteboard.co/H99EfgT.png "King's College London")


## Proposed Solutions:

### Map Types:
  - Ideally a heat map or cloropleth. Heat map must not increase heat by number of points and cloropleth must use a very fine grid that may need to be made using GeoJSON.

### Potential Packages:

  - Folium: Python package with a lot of freedom for control of maps. Heatmaps increase heat when points are close together as well as by value. From my initial testing, they don't always work as expected. See Folium notebook.

  - ~~Basemap~~: Python package using MatPlotLib. Not suitable as cannot map at city/town level.
 
  - Leaflet JS: Very popular Javascript Library with lots of customisability. Used by King's College London as well as AQICN
               http://aqicn.org/city/united-kingdom/leicester-university/
               https://www.londonair.org.uk/LondonAir/nowcast.aspx
               AQICN shows some examples here: http://aqicn.org/faq/2015-09-18/map-web-service-real-time-air-quality-tile-api/
 
 


