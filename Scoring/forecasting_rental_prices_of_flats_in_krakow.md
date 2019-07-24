# Forecasting rental prices of flats in Krakow

Author: Wolak Jacek (AGH University of Science and Technology)

Co-authors: Jalocha Mateusz

# Description

The aim of the study is to investigate the relationship between the location of the apartment and the rental price and to create - on the basis of geospatial variables and distances of apartments from selected objects - the most accurate possible heat map with forecast rental prices of apartments per m^2. Data for the study was extracted from websites with advertisements using the web-scraping method. Due to a small number of offers in some of the 18 districts of Kraków, only four delegations of Sródmiescie, Krowodrza, Podgórze, Nowa Huta were included. In addition, two methods of model construction will be compared, the first of which will be created on the basis of all data, while the second method of prediction will be done using models created for all delegations on the basis of data occurring only in this area. The study was conducted using the programming language R (in the RStudio environment). In order to forecast the prices of rented flats, methods such as multiple regression, bagging, random forest, GBM and XGBoost were used. On the other hand, when selecting the method with the lowest prediction error, the mean square error (RMSE) and absolute error (MAE) were used. As a result, heat maps with results for each method will be presented. 

