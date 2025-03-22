# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

The purpose of this analysis was to decide if a Logistic Regression model would be useful in helping identify high risk and healthy loan aggreements. The variable that was being use to predict was the loan status, using training and test data the analysis was completed. The results were ultimately found using the logisticregression model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    *Precison for high risk loans was at 84%, while for healthy loans it was 100%
    *Overall accuracy was recorded at 99%
    *Recall score for high risk loans was 94%, while for healthy loans it was 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

I reccomend the use of this model based upon the results that were give. The fact that the lowest score was in presicion was 84% i think still gives an accurate look at the data. Performance of this model works whether we are trying to predict the high risk(1) or healthy(0) loans. Overall I am satisfied with the performance of this model and believe it has provided accurate results for this specific data set.

If you do not recommend any of the models, please justify your reasoning.
