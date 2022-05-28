# Mapping_Earthquakes

## Overview

The purpose of this analysis was to create interactive maps using GeoJSON datamaps with different layers to show the differences between the magnitudes of earthquakes all over the world for the last seven days and the tectonic plates around the globe.

## Procedures

We used the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data from the USGS website. Then we used the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data. Since the information is linked to a real-time source, the map will update whenever the user accesses it. 
We added three types of map layers to display Tectonic plates, Earthquake magnitude and location information.  Then we added three overlays options for the users to toggle: Earthquakes, Tectonic Data, and Major Earthquakes in last 7 Days.  The code snippet is as follow:

![Screen Shot 2022-05-18 at 10 41 25 PM](https://user-images.githubusercontent.com/98566486/169192851-2e431f9d-67a2-47e5-8760-d56105703dba.png)

The results for our three map layers are shown below:

![Screen Shot 2022-05-18 at 10 43 08 PM](https://user-images.githubusercontent.com/98566486/169193058-e6bf0148-f7a2-4e00-86e9-e96af9099a4a.png)


![Screen Shot 2022-05-18 at 10 43 35 PM](https://user-images.githubusercontent.com/98566486/169193118-581ee546-49c7-41aa-958e-4dde55de82e7.png)


![Screen Shot 2022-05-18 at 10 44 00 PM](https://user-images.githubusercontent.com/98566486/169193158-ca2c90fe-8ab9-4f2c-bc56-64ffec2c8bf5.png)

## Summary

Tectonic plate data that was collected from a GeoJSON file contining the boundaries of tectonic plates around the world. By viewing this interactive map visualization, we can say that the majority of the major earthquakes in the last week have occurred near or on the tectonic plates. Smaller earthquakes had occured farther away, but the major earthquakes all fall on or right next to the tectonic plates.
