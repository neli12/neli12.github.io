---
layout: project
type: project
image: images/Capture.png
title: Temporal analysis of sugarcane yield
permalink: projects/geospatial_python

# All dates must be YYYY-MM-DD format!
date: 2022-03-18
labels:
  - geoprocessing
  - spatial analysis
  - yield
  - sugarcane
  - python
summary: Getting insights of the temporal variability of sugarcane over a period of five years by municipalities in the State of São Paulo
---

This project involve the first basic steps I am following to build the dataset I'll use in my TCC of the MBA in Data Science and Analytics from the University of São Paulo. These steps consist in downloading historical yield data from the CONAB website (this step will not be described here, as it doesn't involve coding), dowloading the environmental covariates (climate, soil, geology) and the processing to manage these datasets. Because we don't have sugarcane yield data at the pixel level but instead just by counties, I'll be working with municipalities, as shown in the figure below. The first steps consisted in gathering all the necessary data. Yield, productivity and planted area were retrieved from the SIDRA platform of IBGE (Instituto Brasileiro de Geografia e Estatística). Climatic and remote sensing variables were obtained and processed in the Google Earth Engine platform. TERRACLIMATE was used to obtain soil moisture, minimum and maximum temperature, precipitation and evapotranspiration. Land surface temperature (LST) and the Nomalized Difference Vegetation Index (NDVI) were obtained from MODIS (Moderate Resolution Imaging Spectroradiometer), which has daily data that were averaged for each year. The scripts used for gathering and pre-processing the data is described in pre-processing folder.


<img class="ui image" src="https://github.com/neli12/screenshots-figures/blob/main/Capture.PNG?raw=true" width="700"></div>


After analyzing some data, I came with the figure below, which displays the average and standard deviation of sugarcane yield over the years (20) years.

<img class="ui image" src= "https://github.com/neli12/time-series-productivity-sp/blob/main/plot_average_st_yield_ii.png?raw=true" width="700">
I hope you enjoy learning about this!  



Code: <a href="https://github.com/neli12/geospatial_python"><i class="large github icon"></i>geospatial_python</a>  
Code: <a href="https://github.com/neli12/time-series-productivity-sp"><i class="large github icon"></i>time-series-productivity-sp</a>


