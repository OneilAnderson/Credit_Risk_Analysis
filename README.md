# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to display our knowledge in statistical reasoning and machine learning to predict the credit risk using different machine learning models. In this analysis, we used the resampling models, the SMOTEEN algorithm and the ensemble classifiers to predict the credit risks.

## Results

Naive Random Oversampler

- Balanced Accuracy: 65%
- High Risk: Precision is 1% with a recall of 62% 
- Low Risk: precision is 100 % with a recall of 68%

SMOTE Oversampling

- Balanced Accuracy: 64%
- High Risk: Precision is 1% with a recall of 63% 
- Low Risk: precision is 100 % with a recall of 66%

ClusterCentroid Undersampling

- Balanced Accuracy: 51%
- High Risk: Precision is 1% with a recall of 59% 
- Low Risk: precision is 100 % with a recall of 44%

SMOTEEN Over/Under Sampling

- Balanced Accuracy: 64%
- High Risk: Precision is 1% with a recall of 70% 
- Low Risk: precision is 100 % with a recall of 58%

Balanced Random Forest Classifier

- Balanced Accuracy: 79%
- High Risk: Precision is 4% with a recall of 67% 
- Low Risk: precision is 100 % with a recall of 91%

Easy Ensemble AdaBoost Classifier

- Balanced Accuracy: 92%
- High Risk: Precision is 7% with a recall of 90% 
- Low Risk: precision is 100 % with a recall of 94%

## Summary

From analyzing the information that we received from the models, we can see that the emsemble classifier model has the highest balanced accuracy at 92 percent. This means that it's the most accurate for highlighting high credit risk. Both the Random Forest and Ensemble classifier models brought a far higher accuracy than the other models. I believe that a bank can use the ensemble classifier model because of its accuracy compared to the other models.



