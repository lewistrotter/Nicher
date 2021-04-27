# Nicher

## Introduction
Nicher is a python module that predicts the distribution of a plant species across geographic time and space using machine learning, individual plant presence point locations, and digital elevation model-derived topographic variables (e.g. slope, topographic wetness index, aspect, raw elevation). This process is typically known as Species Distribution Modelling (SDM) or Ecological Niche Modelling (ENM).

## Details
Nicher relies on observed locations of plant species (usually recorded from field surveys via a GPS) and topographic variables derived from a DEM raster of any resolution (e.g. high-resolution LiDAR-derived data or low-resolution SRTM data). It uses this data to generate species occurrence probability maps using highly-customisable machine learning sklearn methods (ExtraTrees and RandomForest). 

Note: Nicher does not generate topographic derivatives from DEMs (yet). Users must generate their own before using VegNicher. We recommend the SAGA software for generating topographic derivatves from DEM data (http://www.saga-gis.org/).

## Diagram
Todo

## Key Technologies
- Python
- Xarray, Numpy
- OpenDataCube (or Rasterio)
- Sklearn ExtraTrees or RandomForest classifiers and Fit Optimisation

## Sources
Todo
