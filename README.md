# Project - Telecom Churn Prediction
What is Churn ....?
In Telecomp industry there are many service providers are available in the market. Customer shave option to choose service providers according to their choice. 
Any customer who switches from one service provider to another service provider for various reasons is known as Churn. It is also known as attrition where customers stop using services offered by telecom company and they no longer associated with the existing telecom service provider.

Customer churn rate is percentage of who have discontinued their subscription to a given period time it is calculated as below.
   **Number of customers lost / Total customers started with  = Churn Rate.**

Churn rate can be decided based on monthly or quarterly churn rate.

It is proven that retaining existing customers is less expensive than getting a new customer into business.
due to lot of competition in the market a high percentage of Churn rate is bigger problem telecom companies.

Customer churn is more expected in prepaid customers who can change their mind switch to another service provider any time without informing to telecom company hence this project is focused to understand the churn behaviour of recharge customers.
Post paid customers usually inform the service provider to stop the services.


# This project is to work on the prepaid model for one of the indian company in south east asian market.

Customer churn can be defined based on :
  - Revenue based Churn
  - Usage Based Churn

# Since we are working on Prepaid customer data it is decided to defin churn based on Usage as follows: 
    - Customers who have not had any usage, either incoming or outgoing - in terms of calls or internet over a period of time
    - When a customer has stopped using the services for a while, it may be too late to take any corrective actions to retain them
    - Since indian and southeast Asian market works based on 80 : 20 Principle. Which means 80 % of the revenue is generated from top 20% customers
    - Hence we are going focus on High value customers who are likely to churn.

# Following tasks have been completed in this project :
   1. Importing necessary libraries and load the data set
   2. understand and explore the data such as Analyzing different features present in the data set and handling missing values.
   3. Feature Engineering - this involves extracting new relevant features, extracting high value customers  and derive target variable i.e  "Churn" based on existing features.
   4. tag the customers with "1" and "0" where "1" refers to "Chrun" and "0" refers to "not likely to churn"
   5. Visualize the data with key features to understand the data pattern.
   6. Build the model by spliting training and testing data sets.
   7. Since it is a classification problem I have built logistic regression models to predict the churn.
   8. The ML model consists of
        - logistic regression
        - Decision Tree Classification
        - KNN classification
        - Random Forest
        - performed hyper parameter tuning by using GridSearchCV
        - Created simple neural network and also built neural networks tuning the optimal parameters using Tuner.
        - and finally Identify the misclassification cost and evaluate the model performance on testing data set.
    







