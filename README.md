# Credit_Risk_Analysis

## Overview of Analysis

This project involves data preperation, statistical reasoning, and machine learning to determine the credit risk associated with various loans. I employed various techniques to build, train, and evaluate models with unbalanced classes from a dataset from LendingClub, a p2p lending servivces provider. 

Utilizing Python, Jupyter Notebook, and the imbalanced-learn and scikit-learn libraries, I oversampled the data using the RandomOverSampler and SMOTE algorithms and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results

### Naive Random Oversampling
- **Balanced Accuracy Test:** 64.0%
- **Precision Score:** high_risk 1%; low_risk 100% 
- **Recall Score:** high_risk 66%; low_risk 62% 
![Native_Random_Oversampling](https://github.com/tysonseang/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Images/Native_Random_Oversampling.png)

### SMOTE Oversampling
- **Balanced Accuracy Test:** 65.1%
- **Precision Score:** high_risk 1%; low_risk 100% 
- **Recall Score:** high_risk 61%; low_risk 69% 
![SMOTE_Oversampling](https://github.com/tysonseang/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Images/SMOTE_Oversampling.png)

### Undersampling
- **Balanced Accuracy Test:** 65.5%
- **Precision Score:** high_risk 1%; low_risk 100% 
- **Recall Score:** high_risk 69%; low_risk 40% 
![Undersampling](https://github.com/tysonseang/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Images/Undersampling.png)

### Combination (Over & Under) Sampling: 
- **Balanced Accuracy Test:** 65.5%
- **Precision Score:** high_risk 1%; low_risk 100%
- **Recall Score:** high_risk 75%; low_risk 56%
![Combination_Sampling](https://github.com/tysonseang/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Images/Combination_Sampling.png)

### Random Forest Classifier
- **Balanced Accuracy Test:** 76.9%
- **Precision Score:** high_risk 3%; low_risk 100% 
- **Recall Score:** high_risk 66%; low_risk 88% 
![Balanced_Random_Forest](https://github.com/tysonseang/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Images/Balanced_Random_Forest_Classifier.png)

### Easy Ensemble AdaBoost Classifier
- **Balanced Accuracy Test:** 93.2%
- **Precision Score:** high_risk 9%; low_risk 100% 
- **Recall Score:** high_risk 92%; low_risk 94% 
![Easy_Ensemble_AdaBoost](https://github.com/tysonseang/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Images/Easy_Ensemble_AdaBoost_Classifier.png)