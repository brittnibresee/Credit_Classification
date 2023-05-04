# Credit Risk Classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis was to evaluate a model based on loan risk.
* The data set included details of the size of the loan, debt to income ratio, interest rate, number of accounts, derogetory marks and total debt. These records were used to predict loan status. '1' represented high risk loan and '0' represented low risk loan.
* The data provided contains 77,536 records. Out of the total records, 2,500 were classified as high risk.
* The first stage of the machine learning process was splitting the dataset into training and testing using the train test-split model from sklearn.
* Model 1 was fitted and trained in a logistics regression model. Then used to predict the test data. The random oversampling method was used for Model 2. The data was resampled and a new logistics regression model was created.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  *The balanced accuracy score of Model 1 is 0.952 which means 95.2% of total predictions are correct.
  *The Precison score for label '0'/Healthy Loan was 100% and precision score for label '1'/High Risk Loan was 85%. 
  *Recall score for label '0'/Healthy Loan is 99% and recall score for label '1'/High Risk Loan is 91%. That means almost 100% of actual '0's are predicted correctly as '0' and only 91% of actual '1' are correctly predicted as '1'.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  The balanced accuracy score for Model 2 is 0.993 indicating 99.3% of total predictions are correct.
  * The precison score for label '0'/Healthy Loans is 100% and the precision score for label '1'/ High Risk Loan is 84%. This means nearly 100% of all the records that the model predicted as '0' are actually '0'. While 84% of the records predicted as '1', are actually '1'.
  * Both labels have a recall score of 99%. This indicated that almost 100% of actual '0's and '1's are predicted correctly as '0' and '1's.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Model 2 performs better according to this testing and classification. The accuracy for model 2 is higher than the accuracy of model 1. Model 2 had the ability to correctly identify '1's and '0's correctly.
* Accurately predicting '1's and '0's can be found equally important. However, some company's feel the accuracy of correctly identifying '1's is more important.

Being able to predict '1's/High Risk Loans would be more important than predicting '0's/Healthy Loans. It would be risky for a company/bank to put less emphesis on the '1's/High Risk Loans compared to the '0's/Healthy Loans. Healthy Loan data is valuable but not high risk.


