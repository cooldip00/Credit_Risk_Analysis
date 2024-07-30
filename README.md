# Credit_Risk_Analysis

The purpose of this analysis was to utilize credit card datasets from an actual company (LendingClub) and use linear regression to sample and predict the data. The data was oversampled through the use of the RandomOverSampler and SMOTE algorithms, while it was undersampled using the ClusterCentroids algorithm. After obtaining the results, the BalancedRandomForestClassifier and EasyEnsembleClassifier models were utilized to predict credit risk.

### Undersampling
- **ClusterCentroids Algorithm:** Used for undersampling the dataset to handle class imbalance.
![Undersampling](https://github.com/cooldip00/Credit_Risk_Analysis/blob/main/Images/undersampling.png)

### Oversampling
- **RandomOverSampler:** Used for oversampling the minority class to balance the dataset.
- **SMOTE (Synthetic Minority Over-sampling Technique):** Another method used for oversampling the minority class by generating synthetic examples.
![Oversampling pt1](https://github.com/cooldip00/Credit_Risk_Analysis/blob/main/Images/oversample_pt1.png)
![Oversampling pt2](https://github.com/cooldip00/Credit_Risk_Analysis/blob/main/Images/oversample_pt2.png)

### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/cooldip00/Credit_Risk_Analysis/blob/main/Images/smote_oversampling.png)

### Combination Sampling
![Combination Sampling](https://github.com/cooldip00/Credit_Risk_Analysis/blob/main/Images/combination_sampling.png)

### RandomForestClassifier
![Random Forest](https://github.com/cooldip00/Credit_Risk_Analysis/blob/main/Images/randomforest.png)
