# survxai: how to explain predictions for survival models?

Author: Aleksandra Grudziaz (MIM UW)

# Descripition

Advanced machine learning models are used in more and more areas. Also in survival modeling. Survival random forest and other complex black-boxes supplant classical Cox Proportional-Hazard model. Although black-boxes are very effective, it is difficult to understand which factors drive their decisions. 
During this talk, I will introduce the survxai package which contains methods for the explanation and exploration of survival models.  This package allows to analyze the models at two levels: global concerning, among others, the behavior of the model when changing the value of the variable and local where we focus on the prediction for a specific observation. Explanations can be visualized by using survival curves. In my talk, I will present the functionality of the package on the example of several models of survival analysis: Cox Proportional-Hazards Model, Random Forest for Survival and Regression for a Parametric Survival Model.

References:

- Aleksandra Grudziaz, Alicja Gosiewska, and  Przemyslaw Biecek (2018). survxai: Visualization of the Local and Global Survival Model Explanations. R package version 0.2.0 
[https://mi2datalab.github.io/survxai/]
- Aleksandra Grudziaz, Alicja Gosiewska, and  Przemyslaw Biecek (2018). survxai: an R package for structure-agnostic explanations of survival models. Journal of Open Source Software, 3(31), 961, https://doi.org/10.21105/joss.00961
Przemyslaw Biecek (2018). DALEX: Descriptive mAchine Learning EXplanations. R package version 0.4 [https://pbiecek.github.io/DALEX/]
 

