# INTRO TO RASTERS!

To run the notebook just click on the Binder link below, no need to install anything:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/carmengg/rasters_intro_SB_NAIP/main?labpath=full_raster_notebook.ipynb)

In this notebook we will learn to do a some basic raster manipulation:

1. Open rasters and look at some of their basic information
2. Open a GEOJSON file and look at some of its basic info
3. Clip rasters using the shapefile
4. Compute Normalized Difference Vegetation Index (NDVI)
5. Save our NDVI raster


## REFERENCES:

### Data
The images we will use today come from the US National Agriculture Imagery Program (NAIP). This program provides high-resolution aerial images with four spectral bands: Red, Green, Blue and Near-Infrared. To prepare the rasters for this workshop I accessed the [NAIP Dataset on Microsoft's Planetary Computer](https://planetarycomputer.microsoft.com/dataset/naip#overview), where I also did the data pre-processing. 

To learn more about how these images were collected, check out this short video: [Mapping the Invisible: Introduction to Spectral Remote Sensing - NEON Science](https://www.youtube.com/watch?v=3iaFzafWJQE&t=152s)

### Code
Some of the content in this project is based on the workshop *Introduction to Geospatial Raster and Vector Data with Python* from the [The Carpentries Incubator](https://carpentries-incubator.github.io/geospatial-python/). This is a great resource to go deeper into working with geospatial data with Python. 

### NDVI IN R
Some of the users attending this workshop might be more familiar with the R programming language. In this repo [Here](https://carmengg.github.io/my_coding_website/posts/2021-05-28-mexico-rasters/) you can see an example of doing a similar workflow in R. The repository for this project is available here https://github.com/carmengg/mexico_rasters.
