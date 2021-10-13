# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to display our knowledge in statistical reasoning and machine learning to predict the credit risk using different machine learning models. In this analysis, we used the resampling models, the SMOTEEN algorithm and the ensemble classifiers to predict the credit risks.

## Results

Naive Random Oversampler

- Balanced Accuracy: 65%
- High Risk: Precision is 1% with a recall of 62% 
- Low Risk: precision is 100 % with a recall of 68%

<img width="707" alt="NROS" src="https://user-images.githubusercontent.com/85713532/137202936-049e7f62-8684-44b4-817a-89f1ad02e0b1.png">

SMOTE Oversampling

- Balanced Accuracy: 64%
- High Risk: Precision is 1% with a recall of 63% 
- Low Risk: precision is 100 % with a recall of 66%

<img width="710" alt="SMOTE" src="https://user-images.githubusercontent.com/85713532/137202967-b6d03aee-53e4-4ad2-83ba-ad08ecc5d09d.png">

ClusterCentroid Undersampling

- Balanced Accuracy: 51%
- High Risk: Precision is 1% with a recall of 59% 
- Low Risk: precision is 100 % with a recall of 44%

<img width="697" alt="CC" src="https://user-images.githubusercontent.com/85713532/137202979-f269ea00-b427-4dc0-be44-87a5747e4cd1.png">

SMOTEEN Over/Under Sampling

- Balanced Accuracy: 64%
- High Risk: Precision is 1% with a recall of 70% 
- Low Risk: precision is 100 % with a recall of 58%

<img width="705" alt="SMOTEEN" src="https://user-images.githubusercontent.com/85713532/137202997-021809a2-2015-4055-8eae-a3493b017273.png">


Balanced Random Forest Classifier

- Balanced Accuracy: 79%
- High Risk: Precision is 4% with a recall of 67% 
- Low Risk: precision is 100 % with a recall of 91%

<img width="802" alt="FC" src="https://user-images.githubusercontent.com/85713532/137203011-b7eb2939-d52d-47b2-a78c-31955a193186.png">

Easy Ensemble AdaBoost Classifier

- Balanced Accuracy: 92%
- High Risk: Precision is 7% with a recall of 90% 
- Low Risk: precision is 100 % with a recall of 94%

<img width="712" alt="EEC" src="https://user-images.githubusercontent.com/85713532/137203020-bb709de7-4e72-48a7-919c-f5a63ce213c9.png">

## Summary

From analyzing the information that we received from the models, we can see that the emsemble classifier model has the highest balanced accuracy at 92 percent. This means that it's the most accurate for highlighting high credit risk. Both the Random Forest and Ensemble classifier models brought a far higher accuracy than the other models. I believe that a bank can use the ensemble classifier model because of its accuracy compared to the other models.


