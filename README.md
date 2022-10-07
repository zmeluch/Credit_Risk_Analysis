# Credit Risk Analysis

## Overview of Project
In this project data from LendingClub was used in supervised machine learning models to determine which is
the best to predict credit risk. First the data was read in and cleaned using pandas. Then data was split 
into test and training groups. The data was the resampled using oversampling, undersampling and combination 
approach models. And the performance for each was evaluated with an accuracy score, confusion matrix and 
classification report. Then the process was repeated with two ensemble models, Balanced Random Forest Classifier
and Easy Ensemble Classifier.

## Results
### Random Over Sampler

![RandomOverSampler](https://user-images.githubusercontent.com/103155045/194446933-11997065-11da-4c0c-930a-c9de6ee07f03.png)
  
  - The accuracy score is 0.6390117682133347.
  - The precison for high risk is .01 and for low risk is 1.
  - The recall for high risk is .61 and for low risk is .67.


### SMOTE

![SmoteOversampling](https://user-images.githubusercontent.com/103155045/194446958-c9c96f5c-1d46-4a6c-9b12-ee665626ca32.png)

  - The accuracy score is 0.631475841119048.
  - The precison for high risk is .01 and for low risk is 1.
  - The recall for high risk is .61 and for low risk is .65.


### Cluster Centroids

![ClusterCentroids](https://user-images.githubusercontent.com/103155045/194446982-118cd230-e66f-4032-bdcf-dd7dc1903ab4.png)

  - The accuracy score is 0.5104185551808743.
  - The precison for high risk is .01 and for low risk is 1.
  - The recall for high risk is .59 and for low risk is .43.


### SMOTEENN

![SMOTEENN](https://user-images.githubusercontent.com/103155045/194446992-0d5f1ca0-ceeb-4235-a0de-e730d3c28e95.png)

  - The accuracy score is 0.6630467626334047.
  - The precison for high risk is .01 and for low risk is 1.
  - The recall for high risk is .76 and for low risk is .57.


### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/103155045/194447007-f62718da-2094-4ff4-abea-12d17e97b6a4.png)

  - The accuracy score is 0.7877672625306695.
  - The precison for high risk is .04 and for low risk is 1.
  - The recall for high risk is .67 and for low risk is .91.

### Easy Ensemble Classifier

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/103155045/194447034-26153e97-2fc0-4af5-bd55-e7dc8a90a222.png)

  - The accuracy score is 0.925427358175101.
  - The precison for high risk is .07 and for low risk is 1.
  - The recall for high risk is .91 and for low risk is .94.
## Summary

