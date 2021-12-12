# Credit_Risk_Analysis
## Overview of the Analysis
Fast Lending hopes that using machine learning to determine credit risk in loan applicants can ultimately lower their default rates. This deliverable examines credit risk using multiple machine learning modelling techniques and algorithms for Fast Lending's best interest.
## Results
### Deliverable 1
#### RandomOverSampler
![RandomOverSampler](https://user-images.githubusercontent.com/88520929/145730896-cd1d845b-d817-40da-80bb-42c39a5c6791.PNG)
- Accuracy Score: 64.7%
- Precision Score: 99.0%
- Recall Score: 60.0%
#### SMOTE
![SMOTE](https://user-images.githubusercontent.com/88520929/145730901-6a25c4c1-9e56-4d41-a77c-332aba7aedfa.PNG)
- Accuracy Score: 66.2%
- Precision Score: 99.0%
- Recall Score: 69.0%
#### ClusterCentroids
![clusterCentroids](https://user-images.githubusercontent.com/88520929/145730914-78c2d55b-d395-4eb1-b00e-7944c2e1dc8b.PNG)
- Accuracy Score: 54.4%
- Precision Score: 99.0%
- Recall Score: 40.0%
### Deliverable 2
#### SMOTEENN
![SMOTEENN](https://user-images.githubusercontent.com/88520929/145730927-254fd18c-3f60-407f-8d84-7ef3b42c6d2c.PNG)
- Accuracy Score: 67.8%
- Precision Score: 99.0%
- Recall Score: 57.0%
### Deliverable 3
#### BalancedRandomForestClassifier
![brf](https://user-images.githubusercontent.com/88520929/145730945-7b947e2c-d061-45b2-b4cf-5d4c8ced586b.PNG)
- Accuracy Score: 78.9%
- Precision Score: 99.0%
- Recall Score: 87.0%
#### EasyEnsembleClassifier
![ecc](https://user-images.githubusercontent.com/88520929/145730953-0181a08f-326a-4aac-bad8-6e3cb5937b6b.PNG)
- Accuracy Score: 93.2%
- Precision Score: 99.0%
- Recall Score: 94.0%
## Summary
For this deliverable, three methods - resampling algorithms, a combinatorial SMOTEENN algorithm, and ensemble classifiers - were used to predict credit risk. In all, the ensemble classifiers were the most effective models. I would recommend using ensemble classifiers, especially the easy ensemble classifier, as a model to predict credit risk.
