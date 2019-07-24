# Detection of solar panels based on aerial images using deep learning

Author: Michel Voss (UEP)

Co-authors: Maciej Beresewicz

# Description

The main goal of the article is to present the results of a study on the use of deep learning networks to detect solar panels based on aerial images of Poznan. In addition, the main motivation is to obtain more detailed information about the use of solar energy in Poland drawing on big data sources, which until now have not been used for this purpose.

The data was acquired from the Management Board of Geodesy and Municipal Cadastre GEOPOZ in Poznan and included orthophotomaps for 2016 and the layer of buildings and plots of lands. We extracted buildings from the images using R statistical software and the sf package. To detect solar panels we used the Turi Create library written in Python which re-implements the YOLO (You Only Look Once) library. 

The object recognition algorithm was trained on a sample of images that included  annotations (bounding boxes) about the exact location of solar panels. The results indicate a very high recognition efficiency at the level of 96-99% on the test sample. Based on this procedure we found that around 2% of residential buildings in Poznan in 2016 had solar panels mounted on roofs. 

As far as we know, this is the first use of deep learning to detect solar panels in Poland. Currently, similar studies are being carried out by for instance Statistics Netherlands as part of the DeepSolaris project. The study exemplifies a trend involving the use of aerial and satellite images for statistical purposes thanks to advanced machine learning algorithms and open source software. 
 

