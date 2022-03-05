---
layout: project
type: project
image: images/mineral.jpeg
title: Estimating the abundance of soil minerals
permalink: projects/minerals

# All dates must be YYYY-MM-DD format!
date: 2022-03-05
labels:
  - digital soil mapping
  - machine learning
  - iron oxides
  - spectroscopy
  - R software
summary: Do you know that it is possible to estimate the abundance of specific soil minerals in the soil using soil spectroscopy?
---

Soil mineralogy is one of the soil properties that is poorly analyzed in soils. The main reasons for this are the need of time-consuming field sampling and expensive chemical reactants, which prevent their inclusion in traditional laboratory analysis. Fortunately, soil spectroscopy can help us with that.  
Generally speaking, which help us to know how much of a specific mineral we have in the soil is the absorption feature observed in spectral curves at specific wavelenghts. Take a look at the image shown below.  


<img class="ui image" src="../images/K-M.PNG"></div>


This is the second derivative of the Kubelka-Munk, which is used to enhance a specific absorption feature. This procedure helps to measure how big or small is the absorption feature, which is used to estimate the relative abundance of specific minerals. This tutorial was given to a group of students from Tel Aviv university. In the code source of my github you will found a detailed tutorial in PDF, the scripts and all datasets needed to estimate the relative abundances of minerals in the soil, in this case, hematite and goethita. 
And why we are interested in estimating these minerals in the soil? Because they play a key role in several processes that affect soil fertility, carbon sequestration, organic matter turnover, soil mineralogy, physical quality, etc. Knowing which minerals are present in the soil becomes important because it can help us in having a better understanding of how the soil might behave in these specific processes. 

I hope you enjoy learning about this!  

Code: <a href="https://github.com/neli12/minerals_by_spectra"><i class="large github icon"></i>minerals_by_spectra</a>
