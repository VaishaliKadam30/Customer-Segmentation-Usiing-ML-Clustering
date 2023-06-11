# Customer-Segmentation-Using-ML-Clustering
Why we do segmentation?
Because you can’t treat every customer the same way with the same content, same channel, same importance. They will find another option which understands them better.

Introduction:
The dataset which we are going to use in this problem has taken from the UCI Machine Learning Repository. This is a transactional data set which contains all the actual transactions for a UK-based and registered ecommerce online retail store. The company mainly sells unique all-occasion gifts. This dataset has several features which includes the Invoice Number, Stock Code, Product Description, Product Quantity, Invoice Date, Unit Price, Customer ID, etc.

Before starting with the model, let's first understand what is Customer Segmentation.

About Dataset
● A company that sells some of the product, and you want to know how well the selling performance of the product. You have the data that we can analyze, but what kind of analysis can we do? Well, we can segment customers based on their buying behavior on the market.

● Keep in mind that the data is really huge, and we can not analyze it using our bare eyes. We will use machine learning algorithms and the power of computing for it.

● This project will show you how to cluster customers on segments based on their behavior using the clustering algorithm in Python.

● I hope that this project will help you on how to do customer segmentation step-by-step from preparing the data to cluster it.

About the project
We have a dataset with customer details, inovice dates, order value, quantity etc. and we need to divide people on clusters so that we can make customised strategies for each person. We will follow the Recency, Frequency and Revenue model for dividing customers into clusters. First we will make clusters based on the recency of transactions. People who are most active will be in one cluster and most inactive people for instance will be in another cluster. Similarly we will make clusters according to how frequency people trasact and we will make clusters according to the total revenue value of customers. Finally an overall score will be calculated based on the 3 factors and an overall cluster number will be alloted to each customer ID. Then we can accordingly have different strategies for different clusters.

Customer Prediction
Define an appropriate time frame for Customer Prediction Value calculation

Identify the features we are going to use to predict future and create them

Calculate lifetime value (LTV) for training the machine learning model

Build and run the machine learning model

Check if the model is useful

1. How to decide the timeframe
Deciding the time frame really depends on your industry, business model, strategy and more. For some industries, 1 year is a very long period while for the others it is very short. In our example, we will go ahead with 6 months.

2. Identifying the features for prediction
RFM scores for each customer ID (which we calculated in the previous article) are the perfect candidates for feature set. To implement it correctly, we need to split our dataset. We will take 3 months of data, calculate RFM and use it for predicting next 6 months. So we need to create two dataframes first and append RFM scores to them.

After the first two steps, it is easy to calculate CLTV and train and test the model.

What is RFM Clustering
Recenecy, Frequency and Monetary value. It means overall clusters will be based on these 3 factors.
