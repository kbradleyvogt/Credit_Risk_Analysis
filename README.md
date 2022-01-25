# Credit Risk Analysis

## Overview 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. In this project we will compare six different machine learning techniques to predict credit risk. Using the credit card credit dataset from LendingClub, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, we compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results 

The results from each of the six machine learning methods used.
- Naive Random Oversampling
    - Accuracy: 65%

-  SMOTE Oversampling
    - Accuracy: 62%

- Cluster Centroids Under Sampling 
    - Accuracy: 51%

- SMOTEENN Combo Sampling
    - Accuracy: 63%

- Balanced Random Forest Classifier
    - Accuracy: 78%

- AdaBoost Classifer
    - Accurancy: 92%


## Summary 