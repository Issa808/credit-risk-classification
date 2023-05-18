# credit-risk-classification

## Overview of the analysis
The purpose of this project was to use a dataset of historical lending activity from a lending services company to predict the creditworthiness of borrowers. The records in the dataset each have loan status that determine whether its a risky or healthy loan. This status is decided by the other variables in the dataset which are the loan size, interest rate, borrower's income, debt to income ration, number of accounts, derogatory marks, and total debt. We first seperate the dependent and independent variables and then split the data into training and testing sets. Then we create a logistic regression model with the data to make our prediction and then do the same with the resampled training data.


## Results
* The healthy loans were predicted at a precision of almost 100% and the recall also had the same results as the precision.
* The risky loans had a precision of 87% and the recall was a little bit higher at 89%.
* The resampling training data had the same results as above except for a 98% recall for the risky loans. 



## Summary

Since the results from the machine learning model were pretty good, I would recommend this model. It had basically perfect predictions for the healhy loans and high accuracy for the risky loans. So, I would recommend it for the healhy loans more than the risky loans, but would still be good for both. 
