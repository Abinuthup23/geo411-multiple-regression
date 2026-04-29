# geo411-multiple-regression

Geography 411 | Homework #5

## Overview
This repository contains the R code and analysis for Homework #5. The assignment uses multiple regression to examine housing prices and improve a base regression model using transformations and diagnostics.

## Methods

- Multiple regression 
  Used to estimate the relationship between housing price and variables such as bedrooms, bathrooms, square footage, year built, HS, and SC.

- Diagnostic plots 
  Used to check model assumptions such as linearity, normality, heteroscedasticity, outliers, and leverage.

- VIF 
  Used to check for multicollinearity between the independent variables.

- Log transformation 
  Used in the improved model to reduce heteroscedasticity and improve model fit.

## Key Findings

- The base model had issues with heteroscedasticity, non-linearity, outliers, and non-normal residuals.
- The VIF values were all below 3, so multicollinearity was not a major problem.
- The improved model used log(price) and log(sqft_living).
- The improved model had an R² of 0.7709, meaning it explained about 77% of the variation in housing prices.
- The improved model performed better than the base model, although minor issues remained.

## Tools

- RStudio 
  Used to run regression models, create plots, and analyze results.

- GitHub 
  Used to store and organize the assignment files.

## Reflection
This assignment helped me better understand multiple regression, slope interpretation, model assumptions, VIF, and how transformations can improve a model.
