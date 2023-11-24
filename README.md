# ML_Bank_Churn
About Us
Pranav Narayanan 20BCE1745
Prasanth 20BCE1666
Data Processing
The data processing that need to be done include:
Drop RowNumber, CustomerID, and Surname.
Encode Geography and Gender.
Log Transform Age, CreditScore, and Balance.
Scale range of Age, CreditScore, Balance, EstimatedSalary from 0 to 1.
conclusion
In predicting if a customer will churn or not, we employed 4 types of models: Logistics Regression, Decision Tree, Support Vector Machine and Random Forest. The performances of the models are fairly good with accuracies ranging from 81% - 87%. Other performance metrics that we considered are sensitivity.
From density plots we can see that customer with more products and older customer are more often leaving the bank. We can also observe that customer having only 2 products has very less churn rate.
Overall, Random forest is the best model for predicting churn among the four models.
