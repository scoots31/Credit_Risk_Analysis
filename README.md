# Credit Risk Analysis

## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we utilized Machine Learning statistical algorithms to make predictions based on data patterns provided. Our analysis includes using algorithms RandomSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForecastClassifier, and EasyEnsembleClassifier. 

## Results

We used Machine Learning to resample the dataset using Python libraries: scikit-learn and imbalanced-learn evaluate the results and provide a comparison for our analysis. We used the "loan status" to determine whether the application was considered "low" or "high" risk. Applications that had "current" as the "loan status" were classified as "low risk" and the remaining as "high risk". This reduced the dataset to 68,817 total applications with 99% classified as "low risk".

![Screen Shot 2022-03-27 at 6 38 56 PM](https://user-images.githubusercontent.com/93485455/160306146-63000b4f-277a-4e4d-9ded-89fc1dfc9f6d.png)

Using the 75/25% method to split the data for training vs. testing, 51,366 "low risk" and 246 "high risk" applications were categorized into the training set.


![Screen Shot 2022-03-27 at 6 41 55 PM](https://user-images.githubusercontent.com/93485455/160306237-04e37242-96cb-4a8c-9660-abda6a4446f7.png)


## Deliverable 1: Use Resampling Models to Predict Credit Risk

### Oversampling

RandomOverSampler: 65.9% accuracy, 1% precision, 72% recall and 2% F1 Score

![Screen Shot 2022-03-27 at 7 40 03 PM](https://user-images.githubusercontent.com/93485455/160308618-ec4b5a9e-793b-4c36-a0ff-1f02be365ad9.png)
![Screen Shot 2022-03-27 at 7 43 25 PM](https://user-images.githubusercontent.com/93485455/160308786-49d09624-c87e-4cdd-b8d3-b08cbf6129dc.png)


### SMOTE Oversampling

SMOTE: 66.2% accuracy, 1% precision, 63% recall and 2% F1 Score

![Screen Shot 2022-03-27 at 7 41 38 PM](https://user-images.githubusercontent.com/93485455/160308689-1b5f3779-c034-447f-afd6-a60c609505f8.png)
![Screen Shot 2022-03-27 at 7 42 43 PM](https://user-images.githubusercontent.com/93485455/160308747-83798947-9945-40ef-9aea-00554380d4f2.png)


### Undersampling

ClusterCentroids: 54.5% accuracy, 1% precision, 69% recall and 1% F1 Score

![Screen Shot 2022-03-27 at 7 44 44 PM](https://user-images.githubusercontent.com/93485455/160308844-fc6789e0-76c4-40dc-a625-57a48067a72d.png)
![Screen Shot 2022-03-27 at 7 45 22 PM](https://user-images.githubusercontent.com/93485455/160308884-e2e10a41-c0af-40cd-916f-5cd6467a536e.png)

## Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

SMOTEENN: 64.5% accuracy, 1% precision, 72% recall and 2% F1 Score

![Screen Shot 2022-03-27 at 7 50 33 PM](https://user-images.githubusercontent.com/93485455/160309179-775135d6-2c24-479f-bc86-ea5b50166d12.png)
![Screen Shot 2022-03-27 at 7 50 49 PM](https://user-images.githubusercontent.com/93485455/160309187-8c7b2800-8d42-46b0-be60-67fa52d26827.png)

## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

### BalancedRandomForestClassifier

BalancedRandomForestClassifer: 78.9% accuracy, 3% precision, 70% recall and 6% F1 Score

![Screen Shot 2022-03-27 at 8 12 30 PM](https://user-images.githubusercontent.com/93485455/160310490-8a6ecfb3-e596-487b-a953-00a22ac4026b.png)
![Screen Shot 2022-03-27 at 8 12 48 PM](https://user-images.githubusercontent.com/93485455/160310506-ddc6a591-d8b8-4246-8eec-9a8c6f897b91.png)
![Screen Shot 2022-03-27 at 8 13 45 PM](https://user-images.githubusercontent.com/93485455/160310515-0f0e80cf-bf5d-4059-8785-1c0acbec8624.png)

### EasyEnsembleClassifier

BalancedRandomForestClassifer: 78.9% accuracy, 3% precision, 70% recall and 6% F1 Score

![Screen Shot 2022-03-27 at 8 15 36 PM](https://user-images.githubusercontent.com/93485455/160310607-11911eb5-38c8-4059-be37-646359986bf7.png)
![Screen Shot 2022-03-27 at 8 15 58 PM](https://user-images.githubusercontent.com/93485455/160310614-b42d2387-2838-4798-bf86-c5c69aa112f1.png)

## Summary

### Ranking of models in descending order based on "High Risk" results:

EasyEnsembleClassifer: 93.2% accuracy, 9% precision, 92% recall, and 16% F1 Score

BalancedRandomForestClassifer: 78.9% accuracy, 3% precision, 70% recall and 6% F1 Score

SMOTE: 66.2% accuracy, 1% precision, 63% recall and 2% F1 Score

RandomOverSampler: 65.9% accuracy, 1% precision, 72% recall and 2% F1 Score

SMOTEENN: 64.5% accuracy, 1% precision, 72% recall and 2% F1 Score

ClusterCentroids: 54.5% accuracy, 1% precision, 69% recall and 1% F1 Score



Based on the results the best model is the EasyEnsembleClassifier with 93.2% accuracy. 



