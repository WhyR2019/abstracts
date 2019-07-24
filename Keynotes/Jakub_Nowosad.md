# The landscape of spatial data analysis in R

Author: Jakub Nowosad (Adam Mickiewicz University, Poznan)

# Description

Spatial information surrounds us, from location data stored on your phone to national park borders and satellite images of the Earth. The ubiquity of geographic data and its importance for research explains R’s long history of supporting spatial data analysis and the growing ‘rspatial’ community.
Since R inception in the 1990s, hundreds of packages related directly or indirectly to spatial data analysis have been created, made by people from a range of disciplines including spatial statistics, cartography, remote sensing, soil science, geomorphometry, ecology, transportation, archeology, epidemiology, and econometrics. They often have different goals and sometimes use different words to explain the same concepts. Spatial data analysis packages also evolved together with the rest of the R packages with the use of pipes, tidyverse, or Rcpp. As a result, currently, there are many rspatial packages with different APIs, some more prominent than others.
Important steps in the history of rspatial were the creation of sp and raster packages, in 2005 and 2010, respectively. The sp package became the basis for hundreds of other packages, allowing spatial (vector) data to be included in a wide range of applied software. The raster package enabled working with large raster data sets. Recently, several new packages have appeared such as sf, the successor to sp. Much development is ongoing, including for terra (described as a successor to raster) and stars (the system for working with irregular spatial data sets). The aforementioned packages are often used as a cornerstone for many applied packages, including those used to retrieve spatial data (e.g., rnaturalearth, rgbif, tidycensus), spatial visualizations (e.g., mapview, ggplot2, cartography, tmap), transportation (e.g., osmr, stplanr), or ecology (e.g. ade4, landscapemetrics).
This talk will show several examples of how rspatial can be used to solve different problems. It will also give some hints on how not to get lost in the rspatial landscape and discuss some future directions or the rspatial developments.

# Bio

Jakub is an assistant professor in the Department of Geoinformation at the Adam Mickiewicz University in Poznan, Poland. His main research is focused on developing and applying spatial methods in order to broaden our understanding of processes and patterns in the environment. He has extensive teaching experience in the fields of spatial analysis, geostatistics, statistics, and machine learning. Jakub is also an active member of the #rspatial community and a co-author of the Geocomputation with R book
