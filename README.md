# Credit Card Fraud Detection : Project Overview
* Handle imbalanced dataset by applying SMOTE and Random Under-Sampling, plus removing the extreme outliers
* Compare which technique fits best to handle the imbalanced datasaet
* Optimized Logistic, K-Nearest Neighbor, Support Vector Machine, and Random Forest Regressors using GridsearchCV to reach the best model.

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, matplotlib, seaborn, numpy, sklearn, imblearn

## Dataset
* **Source** : Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud
* The datasets contains transactions made by credit cards in September 2013 by european cardholders that occurred in two days.
* It contains only numerical input variables which are the result of a PCA transformation. The only features which have not been transformed with PCA are 'Time' and 'Amount'. 

## Project Detail
**Handle Imbalanced Dataset:**
For this project I will compare these technique to handle imbalanced dataset and determine which one fits the best :
* Random Under-Sampling Technique
* SMOTE (Synthetic Minority Over-sampling Technique)
* SMOTE and Remove Extreme Outliers

**Machine Learning Models:**
For this project I will implement the data to these models and determine which one fits the best:
* Logistic Regression
* K-Nearest Neighbor
* Support Vector Machine
* Random Forest

**Model Parameter:**
To determine which machine learning model fits the dataset the best, I will use this parameter to decide:
* Precision-Recall
* F1-Score
* ROC-AUC


## Step-by-Step Project:
## Data Wrangling
* Scaling the 'Amount' and 'Time' columns
* Use SMOTE to handle imbalanced dataset and see the correlation of each columns
* Determine which feature have a negative and positive correlation
* Remove extereme outliers from features that have a high correlation with the classes

## Data Analysis
* Decide which technique fits the best for the imbalanced dataset through Precision-Recall curve and ROC-AUC curve

## Model Building
* Use Logistic Regression, KNN< SVC, and Decision Tree as the model and compare each one of them

## Results
The dataset is an imbalanced dataset with the class distribution like the above figure
![alt text](https://github.com/leoniemwindari/credit-card_fraud-detection/blob/main/class%20distribution%20of%20original%20dataset.png)

Class distribution after SMOTE:
![alt text](https://github.com/leoniemwindari/credit-card_fraud-detection/blob/main/class%20distribution%20after%20smote.png)

Precision-Recall curve for the imbalanced dataset technique:
![alt text](https://github.com/leoniemwindari/credit-card_fraud-detection/blob/main/precision-recall%20curve.png)

ROC-AUC curve for the imbalanced dataset technique:
![alt text](https://github.com/leoniemwindari/credit-card_fraud-detection/blob/main/roc%20curve.png)


## Conclusion
1. The best fit technique to handle this imbalanced dataset is SMOTE
2. The best fitting model for this dataset is

## Contact
Leonie M. Windari - @leoniemw_ds - leoniemwindari98@gmail.com
Website - https://leoniemwindari.wordpress.com/2021/02/05/credit-card-fraud-detection/






