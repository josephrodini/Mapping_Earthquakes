# Mapping_Earthquakes

Earthquake map visualization with JavaScript and APIs

## Overview

This project helps the fictitious Disaster Reporting Network visualize data on worldwide earthquakes. The goal is to create an interactive map demonstrating earthquakes in which each earthquake is identified by location when clicked on and is shown with a diameter and color relative to its size. In addition, tectonic plate information was overlayed, especially large earthquakes (of magnitude 4.5 or higher) were featured, and a third map was added.

## Resources

- Data Sources: https://earthquake.usgs.gov/
- Technology: JavaScript, Leaflet library, D3 library, GeoJSON, mapbox

## Deliverable One

Using JavaScript, Leaflet.js, and geoJSON data, an additional layer was added to the earthquakes map showing the location of tectonic plates. See a screenshot of the tectonic plates [with](https://github.com/josephrodini/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/platesWith.PNG) and [without](https://github.com/josephrodini/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/platesWithout.PNG) the earthquake information.

## Deliverable Two

Using JavaScript, Leaflet.js, and geoJSON data, major earthquake data was added to the map using d3.json(). A color and diameter for the circle marker for each earthquake was added in proportion to the magnitude of that earthquake, and a popup marker was added for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer. See [the large earthquakes](https://github.com/josephrodini/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/majorEqs.PNG).

## Deliverable Three

Using JavaScript and Leaflet.js, a third map style was added to the earthquake map. See [light style with the above deliverables also present](https://github.com/josephrodini/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/lightMap.PNG).

## Summary

The Disaster Reporting Network should be quite satisfied with the interactive earthquake map. It can use the map to disseminate information to the masses in order to raise awareness of natural disasters.
