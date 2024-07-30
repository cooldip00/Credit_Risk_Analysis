# Credit_Risk_Analysis

The purpose of this analysis was to utilize credit card datasets from an actual company (LendingClub) and use linear regression to sample and predict the data. The data was oversampled through the use of the RandomOverSampler and SMOTE algorithms, while it was undersampled using the ClusterCentroids algorithm. After obtaining the results, the BalancedRandomForestClassifier and EasyEnsembleClassifier models were utilized to predict credit risk.

### Undersampling
- **ClusterCentroids Algorithm:** Used for undersampling the dataset to handle class imbalance.
- ![Undersampling](path_to_your_image/undersampling.png)

### Oversampling
- **RandomOverSampler:** Used for oversampling the minority class to balance the dataset.
- **SMOTE (Synthetic Minority Over-sampling Technique):** Another method used for oversampling the minority class by generating synthetic examples.
![Oversampling pt1](path_to_your_image/oversampling_pt1.png)
![Oversampling pt2](path_to_your_image/oversampling_pt2.png)

### SMOTE Oversampling
![SMOTE Oversampling](path_to_your_image/smote_oversampling.png)

### Combination Sampling
![Combination Sampling](path_to_your_image/combination_sampling.png)

### RandomForestClassifier
![Random Forest](path_to_your_image/random_forest.png)
