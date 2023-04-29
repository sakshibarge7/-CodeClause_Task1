# -CodeClause_Task1
# Churn Prediction in Telecom Industry using Logistic Regression

Description- According to EuropeanBusiness Review, telecommunication providers lose close to $65 million a month from customer churn. Isn't that expensive? With many emerging telecom giants, the competition in the telecom sector is increasing and the chances of customers discontinuing a service are high. This is often referred to as Customer Churn in Telecom. Telecommunication providers that focus on quality service, lower-cost subscription plans, availability of content and features whilst creating positive customer service experiences have high chances of customer retention. The good news is that all these factors can be measured with different layers of data about billing history, subscription plans, plans, cost of content, network/bandwidth utilization, and more to get a 360-degree view of the customer. This 360-degree view of customer data can be leveraged for predictive analytics to identify patterns and various trends that influence customer satisfaction and help reduce churn in telecom.

This project is focused on predicting customer churn in the telecom industry using logistic regression. Customer churn refers to the loss of customers or subscribers to a service. In the telecom industry, customer churn is a significant problem, with telecommunication providers losing close to $65 million a month.

# Statement

The aim of this project is to predict the likelihood of customer churn using logistic regression. The data for this project is obtained from a CSV file that contains information about customer subscriptions, billing history, and other relevant factors. The dataset contains information about whether a customer has churned or not, and the objective is to build a model that can predict whether a customer is likely to churn.

# Dependencies

Python 3.6 or higher,
pandas,
numpy,
seaborn,
sklearn

# Files

data - 'telecom_data.xlsx': the dataset used in this project

notebooks - 'ChurnPridection_CodeClause1.ipynb': Jupyter notebook containing code for the churn prediction model

# Project Description

Telecommunication providers that focus on Tenure,total Charges, availability of content and features whilst creating positive customer service experiences have high chances of customer retention. All these factors can be measured with different layers of data about Phone Service,Multiple Lines,Internet Service,Online Security,Online Backup,Device Protection,Tech Support,Streaming TV,Streaming Movies, and more to get a 360-degree view of the customer.

This project uses logistic regression, a statistical method used to analyze and model relationships between a dependent variable and one or more independent variables. In this case, the dependent variable is customer churn, while the independent variables could include factors such as customer demographics, subscription plans, network usage, and more. By using logistic regression, we can build a predictive model that helps identify the factors that are most likely to cause customer churn.

This project includes visual representations of the relationship between gender, senior citizen, and total charge with customer churn. These plots can help identify any differences in churn rates based on gender, senior citizen status, and total charge. By analyzing these plots, we can gain insights into the factors that are most likely to influence customer churn and use this information to improve customer retention strategies.

Regarding the plots of churn with gender, senior citizen, and total charge, these are visual representations of the relationship between these variables and customer churn. The gender plot shows the churn rate for male and female customers, which can help identify any differences in churn rates based on gender. Similarly, the senior citizen plot shows the churn rate for customers who are senior citizens versus those who are not. Finally, the total charge plot shows the churn rate for different ranges of total charges, which can help identify any patterns in customer churn based on the amount they are paying for their subscription.

By analyzing these plots, we can gain insights into the factors that are most likely to influence customer churn and use this information to improve customer retention strategies.

# Model

Logistic regression is used to build the model for this project. The model is trained using the training dataset and is then used to predict the likelihood of customer churn in the test dataset. The probabilities of customer churn are calculated using the predict_proba() method of the logistic regression model.

# Conclusion

By leveraging customer data and using logistic regression, telecommunication providers can predict customer churn and identify the factors that influence it. By improving customer retention strategies based on these insights, providers can reduce churn rates and improve customer satisfaction.
