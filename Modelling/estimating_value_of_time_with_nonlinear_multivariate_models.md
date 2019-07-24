# Estimating Value of Time with Nonlinear Multivariate Models

Author: Simona Jokubauskaite (BOKU)

Co-authors: Friedrich Leisch, Reinhard Hössinger

# Description

Package nmm (under development) offers a convenient way to estimate (a subset of) nonlinear multivariate models (NMM). It extends the already existing family of packages, which estimate systems of nonlinear regressions and logit models. nmm uniquely allows for correlations between the error terms from nonlinear regressions and the choice probabilities from logit models. It also enables a very flexible design of logit: different utilities can be specified to each alternative.
The package was used to estimate Austrian value of: leisure, time assigned to work, time assigned to travel, and travel time savings.  By taking these indicators into account the valuation of transport infrastructure projects can be improved.
The estimation is based on maxLik with an option to use global optimization via the differential evolution algorithm (DEoptim). Instead of using the numerical approximations of gradient and the Hessian, nmm produces their analytical versions. The summary() method of nmm object returns normal, robust or clustered standard errors. Also, a wide range of goodness-of-fit statistics is included. The flexible design of logit and system of nonlinear regressions, relaxation of linearity assumption, correlation between continuous and discrete equations allows to use nmm in various settings to estimate a wide range of models. 
 

