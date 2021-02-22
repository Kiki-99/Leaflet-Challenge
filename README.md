# Leaflet Challenge: Visualizing Geographical Data #


![USGS Logo](/Images/1_Logo.png)


## Background ##


The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.


## Extraction of Dataset ##

![USGS Website](/Images/3_Data.png)

 The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

![JSON Pic](/Images/4_JSON.png)


## Earthquake Visualzation ##

![Geo Map](/Images/Map_Picture.JPG)

A map is created using Leaflet that plots all of the earthquakes from the data set that was selected based on their longitude and latitude.

  - Markers reflect the magnitude of the earthquakes both size and color (higher magnitude = bigger marker and darker color).

  - Popup of each earthquake contains information about place, time and magnitude.

  - Legend on the bottom-right of the map that will provide context for the map data.
