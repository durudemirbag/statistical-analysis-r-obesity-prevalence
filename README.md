# Obesity Prevalence Analysis with Regularized Regression

This repository presents an analysis of obesity prevalence using multiple health indicators.
Ridge and Lasso regression methods are applied to address multicollinearity
while maintaining predictive performance.

## Project Context

This project was completed as part of an MSc Data Science programme
and is included here to showcase statistical modelling,
regularization techniques, and reproducible analysis using R.

## Methodology Overview

- Exploratory data analysis of health indicators
- Detection of multicollinearity among predictors
- Ridge and Lasso regression for regularization
- Model comparison based on predictive performance
- Interpretation of regularization effects on coefficients

## Files

- `obesity_regularized_regression.Rmd` : R Markdown file containing the full analysis  
- `obesity_regularized_regression.html` : Rendered report generated from the R Markdown file  
- `IntOrg_NCD_variables_2024_02_02.csv` : Dataset used in the analysis  

## Requirements

- R 
- tidyverse
- glmnet
- ggplot2
- dplyr
- tidyr
- car
- naniar
- corrplot
- ggcorrplot
- knitr
- rmarkdown

## How to Run

Open the `.Rmd` file in RStudio and click **Knit**
to reproduce the analysis and generate the HTML report.

## Note on Output

The rendered HTML and PDF outputs are not included in the repository.
The full analysis can be reproduced by knitting the provided `.Rmd` file.

