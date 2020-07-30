# MITCriticalCare
Mortality Prediction on MIT Critical Care data

## Preprocessing
  * Remove unique patient identifiers
  * Manually removed few unwanted columns with domain experts opinion
  * Remove correlating variable with a threshold
  * One-hot encode all the categorical variable
  * Standard scale Age column
 
 ## Models
  Models tried on this dataset:
    * Logistic Regression
    * Decision Trees
    * Random Forest
    * XGBoost
    * LightGBM
    
