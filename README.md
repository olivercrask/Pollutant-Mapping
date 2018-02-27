# Pollutant-Mapping

## Data Source:

The data is being collected using a raspberry pi zero. Details of this project are on hackster here:
https://www.hackster.io/OxygenLithium/particulater-air-quality-monitoring-for-everyone-3caef2

Work is still needed to integrate this with a GPS module and then to send this data to Hologram.io.

## Goals:

To be able to create an interactive map for visualising data produced by my pollutant sensor. 
This interactive map should be viewable in Home Assistant and show the air quality of an area using a colour scale.
The data will be captured from a Home Assistant REST sensor and the map will update when new data arrives (or soon after).
As the sensor will be moving and pollutant concentration changes with time of day, the map should also have a time slider.

The goal is to produce a map similar to those found at https://www.londonair.org.uk/LondonAir/nowcast.aspx by King's College London.

https://pasteboard.co/H99EfgT.png

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
               
  - [Bokeh](https://bokeh.pydata.org/en/latest/): Interactive plots?
  
  ## Pydata presentation
  Present at Pydata London https://pydata.org/london2018/
  
  Blurb: The event brings together analysts, scientists, developers, engineers, architects and others from the data science community to discuss new techniques and tools for management, analytics and visualization of data. PyData welcomes presentations focusing on Python as well as other languages used in data science (e.g. R, Julia). Presentation content can be at a novice, intermediate or advanced level. Talks will run 30-40 min and hands-on tutorials will run 90-120 min.
  
#### Submission
* Title (proposed): An introduction to data science around the home and community with Home-assistant
* Brief Summary - Should be one paragraph, maximum 400 characters.
* Description - Detailed outline.

 
 


