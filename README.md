# credit-risk-classification

#RESOURCES
1.) Balanced Accuracy Score
https://www.statology.org/balanced-accuracy-python-sklearn/

2.) Counter used to count values in resampled data
https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/

ANALYSIS:

Overview of Analysis:

The purpose of this analysis was to create supervised learning models to predict whether a loan would be labeled a healthy or high risk based on a variety of features. The style of model we focussed on in this analysis is a Logistic Regression model. By utilizing a dataset that already describes each loan as healthy or high risk, we are able to split the data into a training and test data set to test the accuracy of a logistic regression model, fitted to the training set of data, with the test set of data. These regression models yield an accuracy score defined by the average recall obtained on each class. The recall of each model describes out of how many loans were labeled healthy or high risk, the model was a certain percentage effective at making that prediction correctly.

Model 1: Logistic Regression Model with the Original Data


Accuracy: The first model had a balanced accuracy score, or the average of recall obtained on each class of 93.26% for the unbalanced original data. 
Recall: The recall score for this model was 90% which means out of all the loans that were rated as high risk, the model predicted 90% of those outcomes correctly.
Precision: The precision was 87%, meaning that out of all of the  loans that the model predicted as high risk, only 87% of them were actually high risk.


Model 1: Logistic Regression Model with the Resampled Data

Accuracy: The first model had a balanced accuracy score, or the average of recall obtained on each class of 93.29% for the unbalanced original data. 
Recall: The recall score for this model was 90% which means out of all the loans that were rated as high risk, the model predicted 90% of those outcomes correctly.
Precision: The precision was 87%, meaning that out of all of the  loans that the model predicted as high risk, only 87% of them were actually high risk.

The recall and precision scores for both models were the same based on my analysis. The accuracy score changed very slightly.

Summary: 

Both models were very accurate at predicting the outcome of a loan based on the features within the dataset. I would use the logistic regression model that was run on the original data as that model yielded the same or similar results to the model run on the resampled data. If less manipulation needs to occur to gather the same results, that is what I would go with in a business setting. A model that is able to predict 90% of the outcomes correctly is a model worth using in a business as the profit margins of a lending business would ride heavily on the underwriting and risk analysis of selling loans to customers. 
