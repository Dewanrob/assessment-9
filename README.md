# General Overview

Lasso and Ridge Regression are algorithms that are similar to Linear Regression but includes a hyperparameter that reduces the likelihood of overfitting the model to the train dataset. Each algorithm attempts to minimize a different penalty term that is dependent on the coefficient of each variable, or the corresponding slopes. This allow the models to handle outliers quite well.

# Details about Our Files:

Lasso Ridge Sample California SAT.ipynb

The code within this file uses the “SAT Score Results Over the Years (California)” dataset found at: https://www.kaggle.com/datasets/thedevastator/unlocking-achievement-understanding-california-s. This dataset collects the average SAT reading, writing and math scores across high school in California for the school year 2015-2016. It also records how many students were enrolled in Grade 12 and how many SAT test takers. An attempt was made to create a model of the overall SAT scores (the sum of all three sections) based on the enrollment and the number of test takers using Lasso Regression, Ridge Regression and Linear Regression. This sample is really meant to demonstrate the data processing prior to using the algorithm.


Lasso Ridge Regression.pdf

This file is a a set of PowerPoint slides that describes what Lasso and Ridge regressions are and how it is different from Linear Regression. It covers the advantages and disadvantages of each algorithm, as well as the essential data preparation step.
