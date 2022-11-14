# Credit_Risk_Analysis

## Purpose
The purpose of this analysis is to compare machine learning models agains the data to find which machine learning model performs the best for this data.

## Results

### RandomOverSample Model


!["RandomOverSample"](https://github.com/40super/Credit_Risk_Analysis/blob/main/images/RandomOverSampleScreen%20Shot%202022-11-14%20at%2012.02.51%20PM.png)

* The random over sample model has an accuracy of 59% which is relativly low while the precision of 0.99 on average and a recall of 0.52. 

### SMOTE Oversampling 

!["SMOTE OverSample"](https://github.com/40super/Credit_Risk_Analysis/blob/main/images/SMOTE_OverScreen%20Shot%202022-11-14%20at%2012.03.06%20PM.png)

* The SMOTE Oversample has an accuracy of 61% which is relativly decent while the precision of 0.99 on average and a recall of 0.67. 


### SMOTE Undersampling

!["SMOTE UnderSample"](https://github.com/40super/Credit_Risk_Analysis/blob/main/images/SMOTE_UnderScreen%20Shot%202022-11-14%20at%2012.03.29%20PM.png)

* The SMOTE Undersample has an accuracy of 49% which is not good while the precision of 0.99 on average and a recall of 0.45.


### SMOTEEN 

!["SMOTEEN"](https://github.com/40super/Credit_Risk_Analysis/blob/main/images/SMOTEENScreen%20Shot%202022-11-14%20at%2012.03.39%20PM.png)

* The SMOTEEN has an accuracy of 61% which is the same as SMOTE oversampling while the precision of 0.99 on average and a recall of 0.58.

### BalancedRandomForestClassifier

!["BalancedRandomForestClassifier"](https://github.com/40super/Credit_Risk_Analysis/blob/main/images/BRFScreen%20Shot%202022-11-14%20at%2012.25.05%20PM.png)

* The Balanced Random Forest Classifier has an accuracy of 79% which is a excellent performance while the precision of 0.99 on average and a recall of 0.90.

### ADABoost Classifier

!["ADA"](https://github.com/40super/Credit_Risk_Analysis/blob/main/images/BOOSTScreen%20Shot%202022-11-14%20at%2012.25.28%20PM.png)

* The ADABoost Classifier has an accuracy of 93% which is a excellent performance but can be a sign of overfitting while the precision of 0.99 on average and a recall of 0.94.

## Summary

In summary, all models performed decent with all having a precision of .99 and a average recall of .70. For this dataset, I would recommend using the BalancedRandomForestClassifier or ADABoost due to having the highest recall stats and having the greatest accuracy compared to other models.