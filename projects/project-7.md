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
summary: 
---

In this repository you'll find processing techniques used for working with spatial data. I am focusing on basic techniques such as merging, clipping, extracting centrodis, etc.  
This project involve the first basic steps I am following to build the dataset I'll use in my TCC of the MBA in Data Science and Analytics from the University of São Paulo. These steps consist in downloading historical yield data from the CONAB website (this step will not be described here, as it doesn't involve coding), dowloading the environmental covariates (climate, soil, geology) and the processing to manage these datasets. The first preprocessing explained here are the merging of dataframes with shapefile (see the figure below), clipping of large raster stacks and extracting centroids to work with point data.  

Because we don't have sugarcane yield data at the pixel level but instead just by counties, I'll be working with municipalities, as shown in the figure below. This is the product of using the "merge" coding, described in this repository.


<img class="ui image" src="https://github.com/neli12/screenshots-figures/blob/main/Capture.PNG?raw=true" width="700"></div>


This is an ongoing projects, therefore weekly updates will come.


I hope you enjoy learning about this!  



Code: <a href="https://github.com/neli12/geospatial_python"><i class="large github icon"></i>geospatial_python</a>


