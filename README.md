# Fraud-Detection-System
## Overview
This repository contains a Google Colab file that implements several ML algorithms for building a fraud detection system. It uses the credit card fraud detection dataset available at https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud .
### Task 1
Downloading and importing the dataset. Since the dataset was highly imbalanced with fraud class making up only 0.172% of the dataset , addressing class imbalance was an important task to prevent models from predicting only non-fraud class to minimise error in prediction. Handling class imbalance using SMOTE and using feature engineering techniques like Normalization and scaling the data so standard deviation becomes 1 to improve model performance.
### Task 2 
Implementing 
1. Logistic Regression
2. Random Forests
3. Neural Networks
4. Support Vector Machines(output not shown because SVMs take too long to train)
5. XGBoost
6. LightGBM
### Task 3
Evaluating different model performances on test data using appropriate metrics like precision-recall curve and ROC AUC score. We observe that most model overfits on the data which can be seen from poor performance on test set on class fraud. From the Confusion Matrices based on percentages, we conclude that the Logistic Regression model learns the general trend and performs best on each class with respect to the other models.
