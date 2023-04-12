# Mapping_Earthquakes_Ch14
Create a map using the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of earthquakes from GeoJSON data utilizing the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

# Challenge 14 - Mapping Earthquakes
This project aims to visualize earthquake data in relation to the tectonic plates’ location on the earth. The requirements are to plot all earthquakes with a magnitude greater than 4.5 on a third map.

## Data Source
The earthquake data is obtained from the USGS GeoJSON Feed and the tectonic plates data is obtained from fraxen Github repository.

## Technologies Used
The following technologies were used for this project:

HTML
Javascript
JSON
CSS
VS Code
MapBox
Leaflet

## Methodology
The following steps were taken to complete this project:

## Data Retrieval: 
Earthquake, tectonic-plate, and major-earthquake data were retrieved from their respective sources using the geoJSON data resource of the USGS.
Data Wrangling: The data was processed as received and presumed accurate.
Data Visualization: The earthquake data was visualized on a map using MapBox and Leaflet.
Tectonic Plates Overlay: The tectonic plates' location data was added as an overlay to the existing earthquake map.
Magnitude Filter: The earthquakes with magnitude greater than 4.5 were imported as a separately curated geoJSON.

## Files
The following files were used in this project:

README.md: provides an overview of the project and its contents.

## Results
The final output of this project is a map with three different layers displayable on three different base map types:

A base map layer, which shows the world map in "Streets" view, "Satellite" view, or "Dark" view.
An earthquake layer, which shows the location and magnitude of all earthquakes.
A tectonic plates layer, which shows the location of the tectonic plates on the earth.
In addition, a new map was created to visualize only the earthquakes with magnitude greater than 4.5.

## Conclusion
This project demonstrates how to visualize earthquake data in relation to the tectonic plates' location on the earth. It is an example of the power and flexibility of MapBox and Leaflet in processing geoJSON data.
Clearly, it has many applications beyond earthquake representation.
