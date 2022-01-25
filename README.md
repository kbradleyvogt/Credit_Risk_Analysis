# Credit Risk Analysis

## Overview 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. In this project we will compare six different machine learning techniques to predict credit risk. Using the credit card credit dataset from LendingClub, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, we compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results 

The results from each of the six machine learning methods used.
- Naive Random Oversampling
    - Accuracy: 65%
    ![over](https://user-images.githubusercontent.com/86968320/151076615-97ddc431-a08c-4fd6-806e-270179329b86.png)

-  SMOTE Oversampling
    - Accuracy: 62%
    ![s_over](https://user-images.githubusercontent.com/86968320/151076627-14d176b6-313f-41b6-a552-20b0c0adba38.png)

- Cluster Centroids Under Sampling 
    - Accuracy: 51%
    ![under](https://user-images.githubusercontent.com/86968320/151076638-1f030597-b2be-48fa-98e3-e55183ad7697.png)

- SMOTEENN Combo Sampling
    - Accuracy: 63%
    ![combo](https://user-images.githubusercontent.com/86968320/151076684-06164772-2a0e-4037-9fa3-7dba52efd42c.png)

- Balanced Random Forest Classifier
    - Accuracy: 78%

- AdaBoost Classifer
    - Accurancy: 92%
![imbalanced](https://user-images.githubusercontent.com/86968320/151076601-bf7eb010-ad75-4781-9e79-0e32a565e315.png)


## Summary 
After looking at these six techniques, we see most  outcomes in the range of 50-70%. However, the resampling techniques, when used by themselves, do not produce great results. They are only marginally above random chance, and if deployed within a financial institution, they would  be a disaster. We have to keep in mind that it only takes a low percentage of defaults to cause tremendous damage to a financial insitution.

Conversely, the two classification methods we examine, Random Forest and AdaBoost, perform noticeably better, especially AdaBoost.
