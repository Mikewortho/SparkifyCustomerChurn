# Customer-Churn-Prediction-using-Spark
## Overview
In this project, I use the customer behavioral data of a fictitious music app company, Sparkify, to create a model that predicts customers who are most likely to churn.I used three different models : Logistic Regression Model, Decison Tree Classifer and Random Forest Model. Using F1 score as an evaluation metric, Random Forest Classifier performed the best. The reason for using F1 score was, because our dataset was imbalanced.Using accuracy as evaluation metric, will not give a good performance, because any model predicting "no-churn" will always have good accuracy .The Random Forest model achieved a best F1 score of 0.858. Most useful feature turned out to be : Number of active days.

## Files in the repo
1. Readme
2. Sparkify.ipynb

## Packages used
PySpark, Pandas, Matplotlib, Seaborn, Plotly

For blogpost related to this project, please visit : https://mikewortho.github.io/Mikewortho.github.io/welcome-to-jekyll/