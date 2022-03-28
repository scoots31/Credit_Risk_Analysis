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

![Screen Shot 2022-03-27 at 7 40 03 PM](https://user-images.githubusercontent.com/93485455/160308618-ec4b5a9e-793b-4c36-a0ff-1f02be365ad9.png)
![Screen Shot 2022-03-27 at 7 43 25 PM](https://user-images.githubusercontent.com/93485455/160308786-49d09624-c87e-4cdd-b8d3-b08cbf6129dc.png)


### SMOTE Oversampling

![Screen Shot 2022-03-27 at 7 41 38 PM](https://user-images.githubusercontent.com/93485455/160308689-1b5f3779-c034-447f-afd6-a60c609505f8.png)
![Screen Shot 2022-03-27 at 7 42 43 PM](https://user-images.githubusercontent.com/93485455/160308747-83798947-9945-40ef-9aea-00554380d4f2.png)


### Undersampling

![Screen Shot 2022-03-27 at 7 44 44 PM](https://user-images.githubusercontent.com/93485455/160308844-fc6789e0-76c4-40dc-a625-57a48067a72d.png)
![Screen Shot 2022-03-27 at 7 45 22 PM](https://user-images.githubusercontent.com/93485455/160308884-e2e10a41-c0af-40cd-916f-5cd6467a536e.png)



