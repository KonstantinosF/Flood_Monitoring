# Flood_Monitoring
This is an ongoing project which is about monitoring a certain area in Greece which gets flooded frequently, using different remote sensing sensors and methods.

<h5>If someone is interested to contribute please send me an email.</h5>

More specifically, I would like to use two different type of data. One dataset formed from an optical sensor and one from a SAR sensor. Ideally, the optical images would be downloaded from Visible Infrared Imaging Radiometer Suite VIIRS while Synthetic aperture radar images from Sentinel-1 program.

<i>The ultimate goal is to build a model which autimaticly maps the flooded area and then use it on a time series satellite images in order to create a time series data set and then study the frequency of the flooding events and maybe correlate it with other environmental parameters (ex. like global worming).</i>

## About the Sensors 

### VIIRS 
The Visible Infrared Imaging Radiometer Suite (VIIRS) is a sensor designed and manufactured by the Raytheon Company on board the Suomi National Polar-orbiting Partnership (Suomi NPP) and NOAA-20 weather satellites. VIIRS is one of five key instruments onboard Suomi NPP, launched on October 28, 2011. VIIRS is a whiskbroom scanning radiometer that collects imagery and radiometric measurements of the land, atmosphere, cryosphere, and oceans in the visible and infrared bands of the electromagnetic spectrum.[wikipedia](https://en.wikipedia.org/wiki/Visible_Infrared_Imaging_Radiometer_Suite)


I am planning to download VIIRS imagery channels from NOAA-CLASS website. The way I download and preprocess the VIIRS data is described on my blog: https://geospatialessays.wordpress.com/

### Sentinel -1

Sentinel-1 is the first of the Copernicus Programme satellite constellation conducted by the European Space Agency. This mission is composed of a constellation of two satellites, Sentinel-1A and Sentinel-1B, which share the same orbital plane. They carry a C-band synthetic-aperture radar instrument which provides a collection of data in all-weather, day or night. This instrument has a spatial resolution of down to 5m and a swath of up to 400 km. The constellation is on a sun synchronous, near-polar (98.18°) orbit. The orbit has a 12-day repeat cycle and completes 175 orbits per cycle. [wikipedia](https://en.wikipedia.org/wiki/Sentinel-1)