
# Supervised-Machine-Learning-Challenge
## Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
We will be using this data to create machine learning models to classify the risk level of given loans. Specifically, we will be comparing the Logistic Regression model and Random Forest Classifier.

## Retrieving the Data
The data is located in the Challenge Files Folder:

lending_data.csv

The data is imported using Pandas. The resulting dataframe is displayed to confirm the import was successful.

## Predicting Model Performance
We will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before we create, fit, and score the models, a prediction is made as to which model we think will perform better. We do not need to be correct!
Our prediction is written down in the designated cells in our Jupyter Notebook, and justification is provided for our educated guess.

## Splitting the Data into Training and Testing Sets
The features DataFrame, X, is created by removing the loan_status column. The labels set, y, is created by using the loan_status column. The data is split into training and testing datasets by using the train_test_split function.

## Creating, Fitting and Comparing Models
A Logistic Regression model is created, fitting it to the training data that we created in the previous step. Then,the model's score is determined by using the score function and the testing data from the previous step. The same is repeated for a Random Forest Classifier. We have used the 'balanced' class-weight hyperparameter. 
The scores of each model have been reviewed. 

## Result
Which model performed better? 
From the Traing and Test scores of both the Models we can see that Logistic Regression has better effeciency. 

How does that compare to your prediction? 
This has made our assumption incorrect as Logistic Regression Model can also be trained to improve the performance by eliminating the least performing features in our dataset and scaling the values to avoid overfitting.
