# Credit Card Fraud Detection : Project Overview
Recognizing fraud transaction from all transaction so that the customers are not charged for items that they did not purchase.

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, matplotlib, seaborn, numpy, scikit-learn

## Dataset
* **Source** : Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud
* The datasets contains transactions made by credit cards in September 2013 by european cardholders.
* This dataset presents transactions that occurred in two days.
* It contains only numerical input variables which are the result of a PCA transformation.
* The only features which have not been transformed with PCA are 'Time' and 'Amount'. 
* Feature **Time** contains the seconds elapsed between each transaction and the first transaction in the dataset. 
* The feature **Amount** is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. 
* Feature **Class** is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Project Detail
**Handle Imbalanced Dataset**
For this project I will compare these technique to handle imbalanced dataset and determine which one fits the best :
* Random Under-Sampling Technique
* Random Over-Sampling Technique
* SMOTE (Synthetic Minority Over-sampling Technique)

**Machine Learning Models**
For this project I will implement the data to these models and determine which one fits the best:
* Logistic Regression
* K-Nearest Neighbor
* Random Forest

**Model Parameter**
To determine which machine learning model fits the dataset the best, I will use this parameter to decide:
* Accuracy
* Precision-Recall
* F1-Score
* ROC-AUC


## Step-by-Step Project:
## Data Cleaning
* 

## Data Transformation
* Scaling the 'Amount' and 'Time' columns
* Split the data for the train and test set
* Use SMOTE to handle imbalanced dataset and see the correlation of each columns
* Determine which feature have a negative and positive correlation
* Remove extereme outliers from features that have a high correlation with the classes


## Data Clustering
* Use t-SNE, PCA, and Truncated SVD to cluster the class and compare them

## Model Building
* Use Random-Under Sampling, Random-Over Sampling, and SMOTE to handle imbalanced dataset (and with cross validation)
* Use Logistic Regression, KNN< SVC, and Decision Tree as the model and compare each one of them



## Results
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables. 

![alt text]()


## Conclusion

## Contact
Leonie M. Windari - @leoniemw_ds - leoniemwindari98@gmail.com
Website - 






