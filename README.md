# **Credit Card Default Prediction**
This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month credit card defaulter based on demographic and last six months behavioral data of customers

## **Problem statement**
To develop a Machine learning model to predict the risk of credit card defaulter from clints by taking insights from historical data provided such as repayment status, bill amount and payment amount. Also to create model to predict accuratly which type of clint are at risk of defaulting on their credit card payments.
## **Hypothesis Testing**
1. "There is a significant difference in the average 'AGE' between customers who default and those who do not."
   Null Hypothesis : There is no significant difference in the average 'AGE' between customers who default and those who do not.(Ho)
   Alternative Hypothesis : There is a significant difference in the average 'AGE' between the two groups.(H1)

   **Result : Reject the null hypothesis: There is a significant difference in the average 'AGE' between the two groups.**

2. The 'EDUCATION' level of customers is independent of their payment default status ('default_payment_next_month').
   Null Hypothesis : The 'EDUCATION' level of customers is independent of their payment default status.(H0)
   Alternative Hypothesis : The 'EDUCATION' level of customers is associated with their payment default status.(H1)

   **Result : Reject the null hypothesis:  The 'EDUCATION' level of customers is associated with their payment default status.**

3. There is a relationship between 'PAY_0' (payment status in the current month) and 'PAY_2' (payment status in the previous month).
   Null Hypothesis : 'PAY_0' and 'PAY_2' are independent of each other.(H0)
   Alternative Hypothesis : There is a relationship between 'PAY_0' and 'PAY_2'.(H1)

   **Result : Reject the null hypothesis: There is a relationship between 'PAY_0' and 'PAY_2'.**

## **Conclusion**

####  **ML Model Implementation**
1. ML Model - 1 - With all available variables.
2. ML Model - 2 - Using all continous variable.(Dropped for categorical variables)
3. ML Model - 3 - With selected variables from correlation and Multicolinearty.
4. ML Model - 4 - After treatment on outliers and dropped for variable which having high numbers of outliers.
5. ML Model - 5 - DecisionTree Method and selected variables based on outliers, colinearity.
6. ML Model - 6 - RandomForestClassifier and selected variables based on outliers, colinearity.
7. ML Model - 7 - Tried with treatment on imbalnaced data.

Check for below table which will give you all results,The highest scores are highlighted in yellow, while the lowest scores are highlighted in red.

![Capture11111](https://github.com/mramanmulla/MachineLearningModels/assets/135543618/c28dc31a-713c-4420-9936-2bdac03d5c8c)

