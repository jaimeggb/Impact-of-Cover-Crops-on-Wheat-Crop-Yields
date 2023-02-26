# Impact-of-Cover-Crops-on-Wheat-Crop-Yields

## Description: 
As the global population continues to increase, scientists and policymakers are looking for ways to improve our agricultural systems so that we can feed more people.

The data used in this project is adapted from the 2017 Census of Agriculture performed by the U.S. Department of Agriculture (USDA). This survey is a complete count and characterization of U.S. farms and agricultural producers. The data include various information about agricultural land area and use, farming practices, and crop yields at the county level.

There are several farming strategies that promote the long-term health of agricultural land:

Agricultural land easements: contracts between the government and farmers where the government pays landowners to leave areas of the land untouched.
Conservation tillage: a method that helps protect the soil surface and reduce erosion from wind and water between crop harvest and planting.
Cover crops: plants used to slow erosion, return nutrients to the soil, and help smother weeds and control pests.
In this project, we’ll use inverse probability of treatment weighting (IPTW) to determine whether the use of cover crops causes an increase in crop yields.

## How to use: 
View rendered notebook file here: [rendered notebook.nb.html](https://jaimeggb.github.io/Impact-of-Cover-Crops-on-Wheat-Crop-Yields/notebook.nb.html)

## Technologies: 
- R: main language
- R notebooks: main computing platform
- cobalt: A package that provides a set of tools for assessing the balance of covariates in observational studies, particularly those that use propensity score methods.
- WeightIt: A package that provides functions for weighting and balancing covariates in observational studies, including propensity score weighting, inverse probability of treatment weighting, and entropy balancing.
- lmtest: A package that provides a set of diagnostic tests for linear regression models, including tests for heteroskedasticity, autocorrelation, and non-normality of errors.
- sandwich: A package that provides robust standard errors and covariance matrix estimators for linear regression models, particularly those with clustered or heteroskedastic data.
