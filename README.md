This project aims at identifying the most important features that help diagnose breast cancer.

Starting with 32 features, different feature selection techniques including eliminating the features of low variance (less than 1%) and delete the correlated features, we end up having 5 features only that were used in
training and testing the ML model. 

Three ML models were build decision tree classifier, random forest classifier and adaboost classifier and based on the classification metrics accuracy, precision, recall, f1 score, and ROC AUC score, we chose the adaboost 
classifier as it provides excellent outcomes without showing signs of overfitting just like the two other models. One of the reasons of Overfitting is the small size of the datasets (569 records). 
