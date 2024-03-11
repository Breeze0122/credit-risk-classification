# Module 20 Report Template

## Overview of the Analysis


The purpose of this analysis is to utilize machine learning, the logistic regressions technique to assess credit risk. 


The data obtained are loan size, interest rate, borrower income, reason debt vs income, nomber of accounts open, derrogatory marks, total of debts and the loan status. 

This las columns is giving us the infomation regarding the status of the loan 0 if the loan is healthy and 1 if the loan represent a high-risk loan.


## Results

1. Accuracy score: 0.9918
2. Precision score: 
    2.a 0 (healthy loans) = 1.00
    2.b 1 (high-risk loan)= 0.85
3. Recall score:
    3.a 0 (healthy loans) = 0.99
    3.b 1 (high-risk loan)= 0.92

## Summary


The logistic regression model demostrates strong performance across various metrics. Regarding the accurancy of 99% indicating that it correctly cassifies the majority of insances, I mean, the healthy and high-risk loans are classified correctly the 99% of the times.

The precision and recall scores for both classes are also high, suggesting that the model is effective at correclty identifying both types of loans.

As resume, the model's ability to predict both clases accurately suggests its robustness and reliability for credit risk analysis, comparing it to other potetial models, could give a different result, however, the logistic regresssion seems to perform best for this specific task, since the strong performance demostrated it is recommended for use by company for credit risk analysis.