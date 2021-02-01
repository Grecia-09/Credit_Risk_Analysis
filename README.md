# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to use Python to build and evaluate several machine learning models to predict credit risk. In order to complete this task, I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling:

- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the ClusterCentroids algorithm.
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
- Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

After all, I evaluated the performance of these models and made a recommendation on whether they should be used to predict credit risk.

## Results

***Naive Random Oversampling***

<img width="737" alt="oversampling" src="https://user-images.githubusercontent.com/70611325/106529077-b9d0a080-649e-11eb-8637-a7c2b92ea5d6.png">

- Accuracy Score: 64%
- The high_risk precision is low at 1%, which indicative a large number of false positives, and 66% sensitivity which makes a F1 of only 2%.
- Due to the high number of the low_risk population, the low_risk sensitivity is 62% with 100% presicion.

***SMOTE Oversampling***

<img width="730" alt="SMOTE" src="https://user-images.githubusercontent.com/70611325/106529075-b9380a00-649e-11eb-8d16-6b9eeeaa2be0.png">

- Accuracy Score: 65%
- The high_risk precision is still low at 1%, with 61% sensitivity which makes a F1 of only 2%.
- Due to the high number of the low_risk population, the low_risk sensitivity is 69% with 100% presicion.


***Cluster Centroid Undersampling***

<img width="755" alt="Undersampling" src="https://user-images.githubusercontent.com/70611325/106529073-b89f7380-649e-11eb-9a18-148f74bdb3df.png">

- Accuracy Score: 54%
- The high_risk precision is still low at 1%, with 67% sensitivity which makes a F1 of only 1%.
- Due to a large number of number of false positives, the low_risk sensitivity is 42% with 100% presicion.


***SMOTEENN Sampling***

<img width="727" alt="SMOTENN" src="https://user-images.githubusercontent.com/70611325/106529071-b6d5b000-649e-11eb-8f90-d420ad1ccc66.png">

- Accuracy Score: 66%
- The high_risk precision is still low at 1%, with 75% sensitivity which makes a F1 of only 2%.
- Due to the large number of false positives, the low_risk sensitivity is 56% with 100% presicion.


***Balanced Random Forest Classifying***

<img width="817" alt="Screen Shot 2021-02-01 at 3 46 30 PM" src="https://user-images.githubusercontent.com/70611325/106532265-b5a78180-64a4-11eb-87d0-30e0d2c62f2b.png">

- Accuracy Score: 79%
- The high_risk precision is 3% with 70% sensitivity which makes a F1 of 6%.
- Due to the lower number of false positives, the low_risk sensitivity is 87% with 100% presicion.

***Easy Ensemble Classifying***

<img width="730" alt="Screen Shot 2021-02-01 at 3 46 37 PM" src="https://user-images.githubusercontent.com/70611325/106532261-b4765480-64a4-11eb-8f0f-c424bcbfe3ad.png">

- Accuracy Score: 93%
- The high_risk precision is the highest at 9% only with 92% sensitivity which makes a F1 of 16%.
- Due to the lower number of false positives, the low_risk sensitivity is 94% with 100% presicion.


## Summary



