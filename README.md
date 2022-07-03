# Credit_Risk_Analysis
### Overview of the analysis

#### Deliverable 1: Use Resampling Models to Predict Credit Risk
#### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk 

#### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk


### Naive Random Oversampling
![Pic 1](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Accuracy_Score.png)    
![Pic 1](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Confusion_Matrix.png)
![Pic 1](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Imbalanced_Classification_Report.png)
1. Balanced Accuracy: 0.6612700484668286
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.68/0.65

### SMOTE Oversampling
![Pic 2](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/SMOT1.png) 
![Pic 2](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/SMOT.png) 
![Pic 2](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Smot_Accuracy_score.png)
1. Balanced Accuracy: 0.6792948456015411
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.70/.66

### Undersampling
![Pic 3](.PNG)     
1. Balanced Accuracy: 0.6303296388959394
2. Precision:  The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .63/.40

### Combination Under-Over Sampling
![Pic 4](.PNG)     
1. Balanced Accuracy: 0.5173713090878325
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.57

### Balanced Random Forest Classifier
![Pic 5](.PNG)     
1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .67/.91

### Easy Ensemble AdaBoost Classifier
![Pic 6](.PNG)     
1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .91/.94

## Summary:
