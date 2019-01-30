# Fraud-Detection
A classification problem consisting of an imbalanced data set to predict if a transaction through a given credit card is fraudulent.
About 0.2 % of the training set data was fraudulent making it a a clearly biased data set.
Normalized two variables, Time and Amount of transaction as they were quite different in vlaue from the other variables.
Resampled the data using two methods, one being random undersampling and the other being SMOTE.
Applied logistic regression, decision trees and random forests models on the resampled data.
Checked accuracy on resampled testing data with accuracy metric recall_score(sensitivity) as the most important task is to identify fraudulent cases.
Also used ROC curve to visualize the change of False Positives as the true predictions increase and checkd area under curve(AUC).
Used recall_score, AUC to check predictability of model on the original data as well.

