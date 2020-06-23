# Loan-Default-Prediction-Python-

## Pupose
The aim of this project was to predict based on the information available on the loan application if the applicant will default on the loan or not

## Data
Data was downloaded from [Kaggle](https://www.kaggle.com/wordsforthewise/lending-club)
This dataset contains more than 2 million rows and around 150 features. After data cleaning and wrangling the size reduced to about one million rows and 21 features before one hot encoding the categorical variables.

## Model used
Initially decided to go with Logistic Regression, but the model did not perform well. Achieved better results with CatBoost Classifier implemented using PyCaret library.

## Result
Accuracy is not a good performance measure due to the imbalanced nature of the data hence used AUC score. 
Tuned CatBoost classifier achived:
### AUC: 0.724





