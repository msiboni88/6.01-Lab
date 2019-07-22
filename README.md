# Supervised Learning Model Comparison

This lab looks at [data](http://fmwww.bc.edu/ec-p/data/wooldridge2k/401KSUBS.DES) to predict an individual's income and eligibility for a 401k.

#### Regression Models to Predict Income

Model Type | Train RSME | Test RSME
--|--|--
Linear Regression | 0.24 | 0.24
K Nearest Neighbors | 0.19 | 0.20
Decision Tree | 0.19 | 0.20
Bagged Decision Trees | 0.08 | 0.22
Random Forest | 0.19 | 0.19
Adaboost | 0.20 | 0.21
SVR | 0.21 | 0.21

#### Classification Models to Predict 401k Eligibility

Model Type | Train F1 Score | Test F1 Score
--|--|--
Logistic Regression | 82% | 83%
K Nearest Neighbors | 83% | 82%
Decision Tree | 80% | 80%
Bagged Decision Trees | 82% | 82%
Random Forest | 83% | 83%
Adaboost | 83% | 83%
SVC | 83% | 83%
