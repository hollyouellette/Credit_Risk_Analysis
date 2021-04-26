# Credit Risk Analysis

## Overview of Purpose

LendingClub, a peer-to-peer lending services company is seeking to test different machine learning models that could enables lenders to analyze risk based on a variety of other variables. In this project, analysis was performed to test a variety of different machine learning models using a credit card dataset and evaluate there performance. The purpose of this analysis was to evaluate the performance of each of these models and to recommend on whether they should be used to predict credit risk.

## Results

### Oversampling Algorithms

 **RandomOverSampler**
 <img align="right" src="https://github.com/hollyouellette/Credit_Risk_Analysis/blob/main/analysis/Naive_Random_Oversampling.png" width=550>
 
  *Balanced Accuracy Score:* 0.659 <br><br>
  *Precision:* <br>
     - High precision is predicting low-risk<br>
     - Low precision is predicting high-risk<br>
   *Sensitivity:*<br>
     - 0.66 for both high-risk and low-risk predictions<br><br>

  **SMOTE**<br><br>
    *Balanced Accuracy Score:* 0.627<br>
    *Precision:* <br>
      - High precision is predicting low-risk<br>
      - Low precision is predicting high-risk<br>
    *Sensitivity:*<br>
      - 0.61 for predicting high-risk <br>
      - 0.64 for predicting low-risk <br>

### Undersampling Algorithm

   **CluseredCentroids**<br><br>
    *Balanced Accuracy Score:* 0.591<br>
    *Precision:* <br>
      - High precision is predicting low-risk<br>
      - Low precision is predicting high-risk<br>
    *Sensitivity:*<br>
      - 0.61 for predicting high-risk <br>
      - 0.57 for predicting low-risk <br><br>
     
### Combinational Approach

   **SMOTEENN**<br><br>
    *Balanced Accuracy Score:* 0.638<br>
    *Precision:* <br>
      - High precision is predicting low-risk<br>
      - Low precision is predicting high-risk<br>
    *Sensitivity:*<br>
      - High sensitivity for predicting high-risk <br>
      - 0.57 for predicting low-risk <br><br>

### Machine Learning Models to Reduce Bias

  **Balanced Random Forest Classifier**<br><br>
    *Balanced Accuracy Score:* 0.902<br>
    *Precision:* <br>
      - High precision is predicting low-risk<br>
      - Low precision is predicting high-risk<br>
    *Sensitivity:*<br>
      - 0.75 for predicting high-risk <br>
      - High sensitivity for predicting low-risk <br><br>
  
  **Easy Ensemble AdaBooster Classifier**<br><br>
    *Balanced Accuracy Score:* 0.607<br>
    *Precision:* <br>
      - High precision is predicting low-risk<br>
      - Low precision is predicting high-risk<br>
    *Sensitivity:*<br>
      - 0.42 for predicting high-risk <br>
      - 0.79 for predicting low-risk <br><br>
