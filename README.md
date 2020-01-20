# Customer-Churn-Prediction-using-Spark
## Overview
In this project, I use the customer behavioral data of a fictitious music app company, Sparkify, to create a model that predicts customers who are most likely to leave the service (churn). For the project I opted to compare three different models: Logistic Regression, Decison Tree Classifer and Random Forest Classifier. I also chose to use F1 score as the evaluation metric, this is due to the imbalanced nature of the dataset. Using accuracy as the evaluation metric, will not give good performance, because the model will overfit to the 'no-churn' category.

## Results
This project makes use of 3 difference models to provide solution on the given data.

The Logistic Regression model gave an accuarcy of 0.8125 and F1 score of 0.766
The Decision Tree classifier model gave an accuracy of 0.75 and F1 score of 0.642
The Random Forest Classifier gave an accuracy of 0.87 and F1 score of 0.858 

## Conclusion
The Random Forest model achieved the best F1 score of 0.858. Subsequently the strongest feature turned out to be: Number of active days. This was something we expected from out exploratory data analysis and can be further seen in the associated blog post at the bottom of this README.

## Licensing, Authors, Acknowledgements
Must give credit to Udacity for the project. And instructions in the notebook are also well prepared by Udacity team.

## Files in the repo
1. Readme
2. Sparkify.ipynb

## Packages used
PySpark, Pandas, Matplotlib, Seaborn, Plotly

For blogpost related to this project, please visit : https://mikewortho.github.io/Mikewortho.github.io/welcome-to-jekyll/

