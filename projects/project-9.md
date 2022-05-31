---
layout: project
type: project
image: images/newplot.png
title: Creating a ranking considering soil variables in factor analysis
permalink: projects/machine-learning-R

# All dates must be YYYY-MM-DD format!
date: 2022-05-31
labels:
  - PCA
  - soil properties
  - factor analysis
  - rankings
  - R 
summary: Obtaining a ranking of values for each county in São Paulo State using soil variables in an unsupervised problem (factor analysis by principal component analysis (PCA)).
---

Hey there! In this project I tried to understand how principal component analysis (PCA) and factor analysis can be used to develop a ranking using soil properties. As you might know, PCA and factor analysis are unsupervised machine learning techniques that are used especially to find patterns in the data, for dimensionality reduction between highly correlated variables and to create new unobserved variables (also called latent or principal components). These new variables are orthogonal and are used to explain the variance/covariance between the observed variables.  

In this example, I used six soil properties: soil organic carbon (g/kg), clay and sand content (g/kg), nitrogen (cg/kg), cation exchange capacity (CEC, cmolc/kg), and ph (adimensional, which can vary between 0 and 14). These soil properties were retrieved from [soilgrids](https://soilgrids.org/), which is a platform where you can find soil maps for all  over the world, maintained by ISRIC from Wageningen University. These soil maps were downloaded from the Google Earth Engine platform, after average over six depths. The code canbe found [here](https://github.com/neli12/machine-learning-R/factor-analysis).  


I hope you enjoy learning about this!  


Check out this [youtube video](https://www.youtube.com/watch?v=WV_jcaDBZ2I) for an introduction to factor analysis.  

Code: <a href="https://github.com/neli12/machine-learning-R"><i class="large github icon"></i>machine-learning-R</a>

