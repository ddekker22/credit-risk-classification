# credit-risk-classification

## Overview:
The logistic regression model predicts whether a loan is healthy or high-risk based on the criteria of the borrower and economy, such as interest rates, debt-to-income ratio, and loan size. 

## Results:
- **Accuracy Score**: The accuracy score for this model is 99%. This means the model is correct 99% of the time at evaluating healthy vs high-risk loans. However, due to the imbalance of the two classes, this does not show the full picture.

- **Precision Score**: The precision score for this model is 99% for healthy loans, and 91% for high-risk loans. This means that the model correctly predicts true positives 99% and 91% of the time respectively.  

- **Recall Score**: The recall score for hte logistic regression model is 100% for healthy loans and 85% for high-risk loans. This implies that the model correctly catches all (or nearly all) of the healthy loans, but only 85% of the high-risk loans. 15% of the high-risk loans are being missed by the model. 

## Summary:
Given that the model misses 15% of the high-risk loans, it is not the best model; however, it is still extremely good. There is an imbalance of healthy loans to high-risk loans: healthy loans are almost 30 times more common than high-risk loans. However, missing the high-risk loans can have a higher financial loss. Ideally, we would want a model that over-identifies the high-risk loans. This model slightly under-identifies them, but it is still overall a very accurate model, and I would still recommend its use. 

### Final Notes:
Information on accuracy, precision, recall, and confusion matrices was researched at the following site: https://www.evidentlyai.com/classification-metrics/accuracy-precision-recall <br>
All other materials for this module were taken from in-class learning and examples. 
