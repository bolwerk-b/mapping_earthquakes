# Mapping_Earthquakes

## Project Overview
The objective of this project is to gather earthquake GeoJSON data from the USGS API, create and explore interactive maps of earthquakes around the world.\
The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Resources
- Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Earthquakes above 4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), [Tectonic Plate GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0

## Results

### Create a Mapbox account, setup *config.js* and open *index.html*
To interact with the maps API the user have to visit [mapbox.com](https://www.mapbox.com/), create a Mapbox account and retrieve the access token.

### Link to Interactive Maps webpage
The deployed webpage is accessible at [https://bolwerk-b.github.io/Mapping_Earthquakes](https://bolwerk-b.github.io/Mapping_Earthquakes).

### Interactive Maps Views
![Deliverables1](D1.png)
![Deliverables2](D2.png)
![Satellite view](satellite.png)
![Dark](dark.png)