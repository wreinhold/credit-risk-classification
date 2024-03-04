# credit-risk-classification

# Module 12 Report Template

## Overview of the Analysis

For my analysis, I used Logistic Regression models to aim to predict classifications for loans. If the model could accurately predict healthy or high-risk loans, this would help the peer-to-peer loaning services company to determine if they should issue a loan. The data set included a history of loans issued, including several factors that could help predict and a column that labeled the loans as healthy or high-risk.

I split the data into training sets and testing sets, fit a logistic regression model using the training set, and then tested the model with the testing set. After trying this model, I then used Imbalanced Learning's RandomOverSampling method and recreated the process. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy Score: 0.9520479254722232
  * Precision 
      * Healthy Loans: 1.00
      * High-Risk Loans: .85
  * Recall
      * Healthy Loans: .99
      * High-Risk Loans: .91



* Machine Learning Model 2 (Resampled):
  * Balanced Accuracy Score: 0.9936781215845847
  * Precision 
      * Healthy Loans: 1.00
      * High-Risk Loans: .84
  * Recall
      * Healthy Loans: .99
      * High-Risk Loans: .99

## Summary


After my analysis, the second model is recommended. While both were accurate, the second model was better at predicting the test y values. For healthy loans, the models are nearly identical in performance, but the second model tended to provide slightly more false negatives for high-risk loans. If the company is risk-averse and worried about supplying more high-risk loans, then they should use the first model. However, the small difference in the precision scores should not make a large difference, and the overall resampled model tended to be more accurate by 5%, which is why I would recommend it. 
