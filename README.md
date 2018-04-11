# Customer-Lifetime-Value-prediction
Classification of Potential churners
- Developed an attrition model using logistic regression to predict customer churn based on RFM (Recency, Frequency, Monetary) metrics. The model generalized well to new data giving us high sensitivity (~70%) and reducing the risk of not identifying a potential churner.
- Developed a Random forest model that gave us a higher accuracy (~80%)

Prediction of the Customer Lifetime Value
- Used l-1 regularized regression to predict the number of months a customer will stay on the system using both historical and recent behavior. The model generalized at a high accuracy.

Segmentation of customers
- Used K-means techniques to arrive at 7 optimal customer segments. The R-squared was 93.8%
- It was inferred that 3 of the 7 segments consisted of customers that were "sleeping" i.e. not active on the system
- We recommended specific actions on customers sleeping for 1, 3 and 6 months respectively (duration of dormancy) that would help maximize lifetime value
