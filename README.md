# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to use Python to build and evaluate several machine learning models to predict credit risk. In order to complete this task, I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling:

- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the ClusterCentroids algorithm.
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

After all, I evaluated the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results

***Naive Random Oversampling***

Accuracy Score: 67.4%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 72%
Recall Low Risk: 63%

***SMOTE Oversampling***

Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Low Risk: 66%

***Cluster Centroid Undersampling***

Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Low Risk: 66%

***SMOTEENN Sampling***

***Balanced Random Forest Classifying***

***Easy Ensemble Classifying***



## Summary



