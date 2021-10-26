# Credit_Risk_Analysis

## Overview of Analysis
Use multiple machine learning algorithms to create a model that will predict credit card risk (results and type listed below). The models were created using credit data from LendingClub.

## Results

### RandomOveraSampler Oversampling
- The calculated accuracy score is 65.14%.
- Precision is approximately 66.667.
- Recall is approximately 0.92.

### SMOTE Oversampling
- The calculated accuracy score is 62.67%
- Precision is approximately 60.92%.
- Recall is approximately 0.86.

### ClusterCentroids Undersampling
- The calculated accuracy score is 51%
- Precision is approximately 58.62%.
- Recall is approximately 0.52.

### SMOTEENN Combination Sampling
- The calculated accuracy score is 62.47%.
- Precision is approximately 71.26%.
- Recall is approximately 0.77.

### Balanced Random Forest Classifier
- The calculated accuracy is 78.78%.
- Precision is approximately 66.67%.
- Recall is approximately 0.35.

### Easy Ensemble AdaBoost Classifier
- The calculated accuracy is 92.54%.
- Precision is approximately 90.8%.
- Recall is approximately 7.47.

## Summary
All of the models that were used, except fot the Ensemble Classifier, showed weak perfarmance in determining credit card risk. The model predicts correctly over 90% of the time. We recommend only this model be used for practical purposes. The others do not perform confidently enough.
