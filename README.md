# iris_dataset_logistic_regerssiion
building a model for iris data using logistic regerssion

Logistic Regression is a supervised classification algorithm. Although the name says regression, it is a classification algorithm. Logistic regression measures the relationship between one or more independent variables (X) and the categorical dependent variable (Y) by estimating probabilities using a logistic(sigmoid) function. The term “Regression” comes because it estimates the probability of class membership or simply it is regressing for the probability of a categorical outcome.

Why Linear Regression is not used for a classification problem even it can regress the probability of a categorical outcome?

The main reasons why Linear regression is not used for classification. Classification needs probability belonging to the class, and it should be in the range between 0 and 1, while linear regression does not bound the predicted probability outcome in range. The linear regression model can generate the predicted probability as any number ranging from negative to positive infinity. Here logistic/sigmoid function comes in action. The logistic/sigmoid function is used because of its behavior of compressing the output between 0 and 1.
