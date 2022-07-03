# Credit_Risk_Analysis
#### Overview of the analysis:
The purpose of this analysis is to understand how to utilize Machine Learning statistical algorithms to make predictions based on data patterns provided.
Through each of these methods, we split the data into training and testing datasets, and compiled accuracy scores, confusion matries, and classification reports as my results.We use Machine Learning to resample the dataset using Python libraries: scikit-learn and imbalanced-learn evaluate the results and provide a comparison for our analysis.

---
#### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk 
#### Naive Random Oversampling
![Pic 1](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Accuracy_Score.png)    
![Pic 2](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Confusion_Matrix.png)
![Pic 3](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Imbalanced_Classification_Report.png)
1. Balanced Accuracy: 0.6612700484668286
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.68/0.65
---
#### SMOTE Oversampling
![Pic 4](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/SMOT1.png) 
![Pic 5](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/SMOT.png) 
![Pic 6](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Smot_Accuracy_score.png)
1. Balanced Accuracy: 0.6792948456015411
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.70/.66
---
#### Undersampling
![Pic 7](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Undersampling1.png)
![Pic 8](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Undersampling2.png) 
![Pic 9](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Undersampling3.png) 
1. Balanced Accuracy: 0.6792948456015411
2. Precision:  The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.62/0.43
---
#### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk 
#### Combination Under-Over Sampling
![Pic 10](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Combination_1.png)     
![Pic 11](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Deliv_2.png) 
![Pic 12](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Deliv_2_Report.png) 
1. Balanced Accuracy: 0.5269102796100636
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.78/0.58
---
#### Balanced Random Forest Classifier
![Pic 13](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Balance%20accuracy.png) 
![Pic 14](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Confusion_Matrix_D3.pngsification_ReportD3.png) 
![Pic 15](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Classification_ReportD3.png)    
![Pic 16](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/List_by_Priority_D3.png)
1. Balanced Accuracy: 0.7877672625306695
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.67/0.91
---
#### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
#### Easy Ensemble AdaBoost Classifier
![Pic 17](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Train_EasyEnsemble.png)
![Pic 18](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/AccuracyScore_EasyEnsemble.png)
![Pic 19](https://github.com/Tifarahani/Credit_Risk_Analysis/blob/main/Resources/img/Report_EasyEnsemble.png)

1. Balanced Accuracy: 0.925427358175101
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = 0.91/0.94
---
#### Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model.
This analysis is trying to find the best model that can detect if a loan is high risk or not. Becasue of that, we need to find a model that lets the least amount of high risk loans pass through undetected. That correlating statistic for this is the recall rate for high risk. Looking through the different models, the ones that scored the highest were:
- Naive Random Oversampling (68%)
- SMOTEENN Sampling (76%)
- Easy Ensemble Classifying (91%)

---

* Resources:
   * Python 
   * Anaconda 
   * Jupyter Notebooks
