# credit-risk-classification


## Table of Contents

- [Overview](#overview)
- [Results](#results)
- [Summary](#summary)
- [Contributing](#contributing)

## Overview
The purpose of this project is to build a model to help identify credit worthiness of borrowers by training and fitting data into different models. The data being used to fit in the models are the loan status of each lending request. Various variables such as  the interest rate, the size of the loan, the income of the borrower and more are compared to predict the credit worthiness of a borrower. To do this the data has to be trained, tested, and split to format the data efficiently for the models. The logistic regression model was used on the original data and the resampled data. This model is useful becomes it helps to measure the relationship between two factors of a dataset, in particurarly, predicts the dependent variable.

##Results
* Machine Learning Model 1:
  * Accuracy: .92
  *Precision: .95
  *Recall: .94



* Machine Learning Model 2:
  * Accuracy: .99
  *Precision: .99
  *Recall: .99

##Summary
The macro averages were used for the accuracy, precision, and recall scores for each model because the weighted average scores were the same in both models. Based on the results I believe that model 2 is the better model to fit this data because there was higher scores in all three categories for both healthy loans and high risk loans, whereaas, the first model had a less balanced accuracy. For this reason I think that the balance on both loan status' from the second model makes that the better of the two options.In the case that we are only looking to predict the healthy loans then the first model would be the best beccause of the 100% accuracy rate but if we are trying to compare the two status types then model 2 would be the model that performs best.

## Contributing
Classwork --> helped with the training models and different sklearn libraries needed for each model


