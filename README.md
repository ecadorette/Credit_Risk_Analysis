# Credit_Risk_Analysis
Module18

## Overview
The purpose of this analysis is to build a model to accurately asses credit risk. A dataset from LendingClub has been provided to use. `Machine Learning` algorithms were applied to predict risk.

## Analysis
Six `machine learning` models were applied to the dataset. Their results are shown below.

#### 1) RandomOverSampler
- Accuracy Score: 64%
- Precision Score: 99%
- Recall Score: 60%

![RandomOversampler](https://user-images.githubusercontent.com/114450503/224507292-78079e60-940a-446c-b454-cae333722b34.png)

#### 2) SMOTE
- Accuracy Score:66%
- Precision Score:99%
- Recall Score: 69%

![SMOTE](https://user-images.githubusercontent.com/114450503/224507296-79e631a4-769e-41ec-8bb6-52db4c7b708a.png)

#### 3) Cluster Centroids
- Accuracy Score:54%
- Precision Score:99%
- Recall Score:40%

![ClusterCentroids](https://user-images.githubusercontent.com/114450503/224507303-04cf982d-6386-4e5a-a59e-844167a99051.PNG)

#### 4) SMOTEENN
- Accuracy Score:64%
- Precision Score:99%
- Recall Score:57%

![SMOTEENN](https://user-images.githubusercontent.com/114450503/224507315-43df40b4-d1c9-4122-aea6-00f78a9d570a.PNG)


#### 5) BalancedRandomForestClassifier
- Accuracy Score:79%
- Precision Score:99%
- Recall Score:87%

![BalancedRandomForest](https://user-images.githubusercontent.com/114450503/224507321-403ebf6a-3f0d-4baf-a806-9bbf22039ff8.PNG)


#### 6) EasyEnsembleClassifier
- Accuracy Score:93%
- Precision Score:99%
- Recall Score:94%

![easyEnsembleClassifier](https://user-images.githubusercontent.com/114450503/224507325-6df3549f-54ad-44f8-95df-22f5f895f54c.png)

## Summary
The EasyEnsembleClassifier has the best accuracy rate at 93% so it would be the most ideal choice for this application. Once concern I have for the data is the small number of high-risk records there were for training the model. Since there were so few I would be worried the model wouldn't properly detect high-risk cases that don't follow the pattern of the cases we had to train the models with. I'm also not sure a 93% accuracy rate would be high enough for the bank to want to use, having more data to train with may help increase the accuracy rate.
