# Credit_Risk_Analysis

## Overview of the analysis:
The purpose of this analysis was to build and evaluate several machine learning models to identify high-risk loans using historical lending data. The dataset contained information about loans and borrowers, including loan amount, interest rate, income, employment status, and other factors.

We used two types of machine learning algorithms - ensemble classifiers and resampling classifiers - to train and evaluate the models on the given dataset. We resampled the data using the RandomOverSampler and SMOTE algorithms, and used BalancedRandomForestClassifier, EasyEnsembleClassifier, LogisticRegression, RandomForestClassifier, AdaBoostClassifier, and GradientBoostingClassifier algorithms for the modeling.

## Results:

#### Logistic Regression with Random Oversampling
- Balanced accuracy score: 0.64
- Precision score for high risk loans: 0.01
- Recall score for high risk loans: 0.70


#### Logistic Regression with SMOTE Oversampling
- Balanced accuracy score: 0.66
- Precision score for high risk loans: 0.01
- Recall score for high risk loans: 0.63

#### Logistic Regression with Undersampling
- Balanced accuracy score: 0.54
- Precision score for high risk loans: 0.01
- Recall score for high risk loans: 0.69

#### Logistic Regression with Combination Sampling (SMOTEENN)
- Balanced accuracy score: 0.65
- Precision score for high risk loans: 0.01
- Recall score for high risk loans: 0.73

#### Balanced Random Forest Classifier
- Balanced accuracy score: 0.79
- Precision score for high risk loans: 0.03
- Recall score for high risk loans: 0.70


#### Easy Ensemble AdaBoost Classifier
- Balanced accuracy score: 0.93
- Precision score for high risk loans: 0.09
- Recall score for high risk loans: 0.92

# Summary:
The Easy Ensemble AdaBoost Classifier outperformed all other models with a balanced accuracy score of 0.93 and a high recall score of 0.92 for high risk loans. It seems to test the best in predicting high risk candidates.

The Balanced Random Forest Classifier also performed well with a balanced accuracy score of 0.79 and a recall score of 0.70 for high risk loans.
