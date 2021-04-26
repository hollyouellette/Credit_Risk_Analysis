# Credit Risk Analysis

## Overview of Purpose

LendingClub, a peer-to-peer lending services company is seeking to test different machine learning models that could enables lenders to analyze risk based on a variety of other variables. In this project, analysis was performed to test a variety of different machine learning models using a credit card dataset and evaluate there performance. The purpose of this analysis was to evaluate the performance of each of these models and to recommend on whether they should be used to predict credit risk.

## Results

### Oversampling Algorithms

  **RandomOverSampler**
    *Balanced Accuracy Score:* 0.659
    *Precision:* 
      - High precision is predicting low-risk
      - Low precision is predicting high-risk
    *Sensitivity:*
      - 0.66 for both high-risk and low-risk predictions
  
  **SMOTE**
    *Balanced Accuracy Score:* 0.627
    *Precision:* 
      - High precision is predicting low-risk
      - Low precision is predicting high-risk
    *Sensitivity:*
      - 0.61 for predicting high-risk 
      - 0.64 for predicting low-risk 

### Undersampling Algorithm

   **CluseredCentroids**
    *Balanced Accuracy Score:* 0.591
    *Precision:* 
      - High precision is predicting low-risk
      - Low precision is predicting high-risk
    *Sensitivity:*
      - 0.61 for predicting high-risk 
      - 0.57 for predicting low-risk 
     
### Combinational Approach

   **SMOTEENN**
    *Balanced Accuracy Score:* 0.638
    *Precision:* 
      - High precision is predicting low-risk
      - Low precision is predicting high-risk
    *Sensitivity:*
      - High sensitivity for predicting high-risk 
      - 0.57 for predicting low-risk 

### Machine Learning Models to Reduce Bias

  **Balanced Random Forest Classifier**
    *Balanced Accuracy Score:* 0.902
    *Precision:* 
      - High precision is predicting low-risk
      - Low precision is predicting high-risk
    *Sensitivity:*
      - 0.75 for predicting high-risk 
      - High sensitivity for predicting low-risk 
