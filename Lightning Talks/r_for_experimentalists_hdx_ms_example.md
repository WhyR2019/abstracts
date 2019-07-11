# R for experimentalists: HDX-MS example

Author: Weronika Puchala (Institute of Biochemistry and Biophysics Polish Academy of Sciences)

Co-authors: Michal Burdukiewicz, Michal Kistowski, Katarzyna A. Dabrowska, Aleksandra E. Badaczewska-Dawid, Dominik Cysewski, Michal Dadlez

# Descripition

Complex and precise experiments like Mass Spectrometry generate an enormous amount of complicated data. Such datasets require manual pre-processing, which due to their size, is tedious, time-consuming and error-prone. To automatize these steps and also provide a whole analytic workflow, we present HaDeX, an R package for analysis and visualization of Hydrogen/Deuterium Exchange Mass Spectrometry (HDX-MS) data. It facilitates complete data analysis, including quality control, Bayesian framework for differential analysis and  ISO-based uncertainty. The sheer volume of data requires highly efficient data processing which is ensured by the data.table package. Our tool also provides a collection of data visualizations that comprehensively summarize HDX-MS results. The package is available on CRAN: https://CRAN.R-project.org/package=HaDeX.

The main audience for HaDeX is HDX-MS practitioners whose area of expertise doesn’t include programming and advanced data analysis skills. To help them with their work, HaDeX is also available as a Shiny web server with a wide range of clickable customizable options. For users operating on sensitive data standalone application is available. To ensure publication-quality figures all the plots are fully editable by the user and processed data is easily downloadable in every step. The reproducibility of the analysis perfomed in GUI is ensured with advanced reporting functions. It is important to us that our analytic methodology is transparent and understandable for the users so it is consulted with international experts and discussed in-depth in the package vignette. 
 

