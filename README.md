# Pollutant-Mapping

## Project summary
Air quality data is collected using a sensors/s connected to a raspberry pi or micropython/arduino board. The system runs off a battery so the user can monitor pollutants throughout their day. Data is recoreded directly onto an SD card or posted to a remote server.

Current progress on this project is on hackster [here](https://www.hackster.io/OxygenLithium/particulater-air-quality-monitoring-for-everyone-3caef2)

#### Project Goals:
To be able to create an interactive map for visualising data produced by pollutant sensor/s.
This interactive map should be viewable in Home Assistant and show the air quality of an area using a colour scale. As the sensor will be moving and pollutant concentration changes with time of day, the map should also have a time slider.

The goal is to produce a map similar to those found at https://www.londonair.org.uk/LondonAir/nowcast.aspx by King's College London, [e.g](https://pasteboard.co/H99EfgT.png
).



## PMS5003 air quality sensor
PM1.0, PM2.5 and PM10.0 particulate matter per 0.1L air, categorized into 0.3um, 0.5um, 1.0um, 2.5um, 5.0um and 10um size bins.

* Manufacturer: http://www.plantower.com/en/content/?108.html
* Micropython driver:
* Raspberry pi driver:
* [LoPy 4 pycom board and PMS5003](https://kapusta.cc/2018/02/02/air-quality-monitor-revisited/)
* [ESP8266 write-up](https://ourairquality.org/index.php/build-an-air-quality-monitor/)
* [Some sensor specs from a NZ website](https://www.kiwi-electronics.nl/pm2-5-air-quality-sensor-breadboard-adapter-kit-pms5003?lang=en)
* [Amazon UK page](https://www.amazon.co.uk/iHaospace-PMS5003-Digital-Particle-Detection/dp/B071J5LL8V)



## Other Hardware
List of currently used and to-investigate hardware:
* [PiJuice](https://uk.pi-supply.com/products/pijuice-standard) battery hat


## Data Analytics:
### Plotting:
  - Ideally a heat map or cloropleth. Heat map must not increase heat by number of points and cloropleth must use a very fine grid that may need to be made using GeoJSON.

  - Folium: Python package with a lot of freedom for control of maps. Heatmaps increase heat when points are close together as well as by value. From my initial testing, they don't always work as expected. See Folium notebook.

  - ~~Basemap~~: Python package using MatPlotLib. Not suitable as cannot map at city/town level.

  - Leaflet JS: Very popular Javascript Library with lots of customisability. Used by King's College London as well as AQICN
               http://aqicn.org/city/united-kingdom/leicester-university/
               https://www.londonair.org.uk/LondonAir/nowcast.aspx
               AQICN shows some examples here: http://aqicn.org/faq/2015-09-18/map-web-service-real-time-air-quality-tile-api/

  - [Bokeh](https://bokeh.pydata.org/en/latest/): Interactive plots?

  ## Relevant links
  * Sniffy air quality monitoring Southampton https://www.solentairwatch.co.uk/
