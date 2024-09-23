# Driveline Open Biomechanics Project

## Trey Chase

## Description

All data obtained in this report is from the Driveline Open Biomechanics project on Github. 

The purpose of this project is to predict fastball velocity from the bio-mechanical data provided, as well as determine the five most important predictors for coaches to emphasize. The model uses a step-wise regression algorithm to determine the most relevant predictors, and then I modified the model to satisfy the multi-collinearity condition as well as removing any variables with coefficients that are not statistically significant via t-test. I then used a 95% bootstrap confidence interval to validate the R-squared statistic of the model. To determine the five most important predictors, I extracted the variables with coefficients that have lowest p-value. An alternative approach would be to use principal component analysis. Leveraging predictive modeling with biomechanical data has potential to increase efficiency when developing pitchers and add a few ticks to their fastball at every level.
