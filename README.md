# Module 12 Report

## Overview of the Analysis

The purpose of the analysis is to use historical lending data to train and evaluate a model to determine creditworthiness. The lending data used included: loan size, interest rate, borrower income and total debt. The data also has a column called "loan_status" with values of 0 (healthy loan) or 1 (unhealthy loan). Using the value_counts function, it showed that there are 75036 healthy loans and 2500 unhealthy loans. 

The data was split into training and testing sets and a logistic regression model was created with the original data. Then predict a logistic regression model with resampled training data.

---
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

 Machine Learning Model 1:
   Model 1 
       Accuracy = 99%
       Precision  
           0 (healthy loan) = 100%
           1 (unhealthy loan) = 84%
       Recall 
           0 (healthy loan) = 99%
           1 (unhealthy loan) = 98%


Oversampled Model:
  Accuracy = 99%
  Precision  
    0 (healthy loan) = 100%
    1 (unhealthy loan) = 83%
  Recall 
    0 (healthy loan) = 99%
    1 (unhealthy loan) = 99%

---
## Summary

Both models produce similar results when looking at the balance daccuracy scores so neither looks to perform better than the other. Due to the similarities in results, the oversampling exercise isn't necessary going forward. Since we are looking to predict creditworthiness it's more important to predict the 1 (unhealthy loans) so the model can detect future borrowers. 

