# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
  The purpose is to determine if the LGM can be accurate to predict healthy loans vs high risk loans
* Explain what financial information the data was on, and what you needed to predict.
  loan_status
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  value_counts
  original
  value_count
  0 75036
  1 2500

  oversampled
  0 56271
  1 56271
  
* Describe the stages of the machine learning process you went through as part of this analysis.

  Prepare, separate, train_test_split, pick ml model (LogisticRegression), fit model with training data, use data to make predictions.
  Finally, evaluate predictions by comparing metrics, etc.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

  SKLearn LogisticRegression
  train_test_split
  confusion_matrix
  classification_report

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1
  * Accuracy: 0.99
  * Precision Class 0: 1.00, Class 1: 0.85
  * Recall Class 0: 0.99, Class 1: 0.91



* Machine Learning Model 2:
  * Description of Model 2
  * Accuracy: 0.99
  * Precision Class 0: 1.00, Class 1: 0.84
  * Recall Class 0: 0.99, Class 1: 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
