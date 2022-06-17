# Credit Risk Analysis

## Overview
- The purpose of this analysis was to determine which model best predicted what loans were good or bad.

## Results
- Random Over Sampler <br/>
![ros](https://github.com/bmcnamee96/Credit_Risk_Analysis/blob/main/Resources/random_oversampling.png)
  - The precision was high for the low_risk loans but extremely low for high_risk loans.
  - The sensitivity score was very low for this model

- SMOTE Oversampling <br/>
![smote](https://github.com/bmcnamee96/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
  - The precision was high for the low_risk loans but extremely low for high_risk loans.
  - The sensitivity score was very low for this model

- Cluster Centroids <br/>
![cc](https://github.com/bmcnamee96/Credit_Risk_Analysis/blob/main/Resources/cluster_centroid.png)
  - The precision was high for the low_risk loans but extremely low for high_risk loans.
  - The sensitivity score was very low for this model

- SMOTEENN <br/>
![smoteenn](https://github.com/bmcnamee96/Credit_Risk_Analysis/blob/main/Resources/smoteenn.png)
  - The precision was high for the low_risk loans but extremely low for high_risk loans.
  - The sensitivity score was very low for this model

- Random Forest Classifier <br/>
![rf](https://github.com/bmcnamee96/Credit_Risk_Analysis/blob/main/Resources/random_forest.png)
  - The precision was high for both low and high risk loans
  - The recall for high_risk loans was low though
  - The sensitivity was higher for this model


- AdaBoost Classifier <br/>
![ada](https://github.com/bmcnamee96/Credit_Risk_Analysis/blob/main/Resources/ada_boost.png)
  - The precision was high for both low and high risk loans
  - The recall for hgih_risk loans was low though
  - The sensitivity was higher for this model
  - This was the best model for loan predictions 

## Summary
In conclusion, all of the models had a very low sensitivy score.  Even though the AdaBoost Classifier Model was the overall best at predicting loans, I would not recommend using any of these models.
