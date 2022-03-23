# INTRO TO RASTERS!

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/carmengg/rasters_intro_SB_NAIP/main?labpath=full_raster_notebook.ipynb)

In this notebook we will learn to do a some basic raster manipulation:

1. Open rasters and look at some of their basic information
2. Open a GEOJSON file and look at some of its basic info
3. Clip rasters using the shapefile
4. Compute Normalized Difference Vegetation Index (NDVI)
5. Save our NDVI raster


## REFERENCES:

### Data
The images we will use today come from the US National Agriculture Imagery Program (NAIP). They are high-resolution aerial images with four spectral bands: Red, Green, Blue and Near-Infrared. To prepare the rasters for this workshop I accessed the [NAIP Dataset on Microsoft's Planetary Computer](https://planetarycomputer.microsoft.com/dataset/naip#overview), where I also did some pre-processing of the data. 

### Code
Some of the code and text in this notebook, and the information on the slides is based on the workshop *Introduction to Geospatial Raster and Vector Data with Python* from the [The Carpentries Incubator](https://carpentries-incubator.github.io/geospatial-python/). This is a great resource to go deeper into working with geospatial data with Python. 
