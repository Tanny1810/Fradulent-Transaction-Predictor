# Fradulent-Transaction-Predictor
It is a model that can predict Transaction made by fraudulent customers.
## DataSet
To download the dataset click [here](https://drive.google.com/uc?export=download&confirm=6gh6&id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV).
The dataset available is in CSV format having __6362620 rows__ and __10 columns__.

## Data Preprocessing
Performed data cleaning by removing the missing values, outliers and multi-collinearity from the data set.

## Data Split
The dataset was split into Training split __(90%)__ and Test split __(10%)__.

## Training
Used 4 Classifier models namely Logistic Regression, XGBoost Classifier, K Neighbors Classifier, and Decision Tree Classifier to train and test the dataset. The best accuracy out of all the models was recorded on the XGBoost classifier with an accuracy of __99.96%__.
