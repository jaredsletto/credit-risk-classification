# credit-risk-classification
Module 20 Challenge

## Overview of the Analysis

The analysis I completed in this challenege focused on the sample size of the data. The supports for '0' were a lot more for the original data set. I used train_test_split and the linear regression model to make predictions. Then, I calculated the accuracy score of the model. Generated a confusion matrix. Printed the classification report

## Results

* Machine Learning Model 1:
  I had an accuracy score of 95.2%. This was very high for the original data.
  My precision score for '0' was 100%. the recall score for '0' was 99%.
  My precision score for '1' was 85%. the recall score for '1' was 91%.
  The model was better at predicting '0'.
  There were far more supports for '0' so we want to see what would happen if we used the RandomOverSampler.

* Machine Learning Model 2:
  The accuracy score increased to 99.4%.
  My precision score for '0' was 100%. the recall score for '0' was 99%.
  My precision score for '1' was 84%. the recall score for '1' was 99%.
  The second model was more accurate and had a higher recall score.

  
## Summary

Module 2 performs best because it has higher accuracy recall and f-1 scores for '1's. Both models were nearly perfect at predicting '0's. It is more important to predict the '1's as they are less frequent. 
