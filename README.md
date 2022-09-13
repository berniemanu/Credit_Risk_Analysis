# Credit_Risk_Analysis
## Overview:
This analysis gives us a chance to use Machine learning statistical algorithms to make predictions. Jill has asked my help to evaluative and predict credit risk using Machine learning.

## Results:
### Deliverable 1: Using oversampling RandomOverSampler and SMOTE algorithms to resample the data, then use the undersampling ClusterCentroids algorithm.
* Accuracy score calculated using Oversampling
![image](https://user-images.githubusercontent.com/104685001/189817355-3c81c3a8-9839-4ccf-a6d8-78f624b4d4b3.png)

* Accuracy score calculated using SMOTE oversampling
![image](https://user-images.githubusercontent.com/104685001/189817405-adbd1f6b-6e8a-4884-8fc1-3c8e67006c2f.png)

* Accuracy score calculated using undersampling
![image](https://user-images.githubusercontent.com/104685001/189817437-a003c83e-64e4-4545-8178-90e054b7775f.png)

### Deliverable 2: Using combinatorial SMOTEENN algorithm
* An accuracy score for the model is calculated
![image](https://user-images.githubusercontent.com/104685001/189817520-70a20780-5d85-44ec-ba08-b8632cc51da9.png)

* A confusion matrix has been generated
![image](https://user-images.githubusercontent.com/104685001/189817575-08980d47-adb6-4705-b4d5-228bc5eebe0f.png)

* An imbalanced classification report has been generated
![image](https://user-images.githubusercontent.com/104685001/189817632-55a7377b-daa3-4198-9e88-2fb048eabf19.png)

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
* An accuracy score for the model is calculated using BalancedRandomForestClassifier algorithm
![image](https://user-images.githubusercontent.com/104685001/189817765-fee76db7-f999-4de6-b83b-1607a9efc26f.png)

* A confusion matrix has been generated using BalancedRandomForestClassifier algorithm
![image](https://user-images.githubusercontent.com/104685001/189817838-10f2a5f6-5b42-4a8d-bdb7-932e28309dd6.png)

* An imbalanced classification report has been generated using BalancedRandomForestClassifier algorithm
![image](https://user-images.githubusercontent.com/104685001/189817914-375164ea-ab30-41d9-9421-b2337f2b71e7.png)

* The features are sorted in descending order by feature importance
![image](https://user-images.githubusercontent.com/104685001/189818008-ad92a800-8285-4b88-8bf4-5d17fe714c8e.png)

## Summary:
Of all the six models, I would recommend EasyEnsembleClassifer model as it predicted with 92% recall. However with low precision this model has its downside in adding bad accounts to the bank portfolio.
