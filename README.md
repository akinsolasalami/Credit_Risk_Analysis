# Credit_Risk_Analysis

## Overview of the Analysis

We employed different techniques to train and evaluate models with unbalanced classes. We used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Results 


### Naive Random Oversampling
![naive_random_oversampling](Resoures/naive_random_oversampling.png "naive_random_oversampling")


* __Accuracy Score: 68%__


### Smote Oversampling
![smote_oversampling](Resoures/smote_oversampling.png "smote_oversampling")


* __Accuracy Score: 62%__

### Undersampling
![undersampling](Resoures/undersampling.png "undersampling")


* __Accuracy Score: 51%__

### Combination
![combination](Resoures/combination.png "combination")

* __Accuracy Score: 65%__

### Balanced Random Forest Classifier
![random_forest_classifier](Resoures/random_forest_classifier.png "random_forest_classifier")

* __Accuracy Score: 87%__

### Easy Ensemble AdaBoost Classifier
![easy_ensemble_classifier](Resoures/easy_ensemble_classifier.png "easy_ensemble_classifier")

* __Accuracy Score: 94%__


## Summary
Out of the 6 methods used the Easy Ensemble Adaboost Classifier was the best with an accuracy score of 94%. Easy Ensemble provdes the best method for our credit risk analysis. 