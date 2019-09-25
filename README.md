# Heart-Dataset

This is an analysis of the 'heart' dataset from https://www.kaggle.com/ronitf/heart-disease-uci using machine learning. The aim is to predict whether a patient has heart disease using the available features.

We did not find any outliers in the dataset. We selected the top 5 features to use for classification using SelectKBest. So far we have used logistic regression, a support vector machine, a random forest, and a voting classifier to attempt to predict heart disease.
The classes were reasonably balanced, so we chose accuracy as the main model metric. We have achieved an acccuracy of 90.16% so far, but may be able to achieve higher accuracy - perhaps with better feature engineering, algorithms that are exceptionally good on small datasets, or better hyperparameters. 
