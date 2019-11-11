# Spark Machine Learning Lab using the Diamonds Dataset

This was an assignment I had to complete for my Big Data course at the University of Toronto during the Fall of 2019. Using the Databricks Diamonds dataset, I had to compare the holdout results of using the basic linear regression vs the pipelined forest regressor.

In this assignment, I had to first clean the dataset by removing columns that could introduce errors and converting others from string values to ordinals so that the regressor could understand them. Then, using the remaining columns as features, I used both regressor methods to try and predict the dependent variable, the `price` of a diamond.

The holdout, or accuracy of the Linear Regression was just under `20%`, while for the Pipelined Forest Regressor using Hypertuning, the holdout value jumped up to a whopping `43%`! These values were obtained by predicting prices to within `+/- 250` of the actual values.

### Link to the databricks notebook

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/866295758796679/2210320901493471/7330054500351766/latest.html

### Screengrab

![Databricks Notebook Scrollthrough](ml.gif)
