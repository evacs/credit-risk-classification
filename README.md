# credit-risk-classification
Module 20 Challenge

1. Overview:

The purpose of this analysis was to build a model that can accurately predict credit risk. I used a large set of loan data to train the model 
based on loan size,	interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and  loan status. 

2. Results:

-Accuracy score: 0.99
-Precision score: healthy-1.00, high-risk-0.85
-Recall score: healthy-0.99, high-risk-0.91

3. Summary:

This model has an overall accuracy score of 0.99, and is therefore a good candidate for predicting healthy and high risk loans. The precision rating is 
perfect for predicting healthy loans, however when the model predicts "high-risk," it is only correct about 85% of the time. The recall score is slightly 
lower for healthy loans and higher for high-risk loans. A higher precision score for healthy loans (vs higher recall rate for high-risk loans) should 
be preffered in this case, because this ensures that there is a low (to no-) chance that the model will identify a high-risk situation as a healthy one. 
This maximises the return on dispersed loans, although some loans may be denied to healthy candidates. This model should be used to assess risk for now, 
however there is room for improvement when it comes to predicting at-risk candidates.  

