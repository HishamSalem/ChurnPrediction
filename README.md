Group#3 | Churn Prediction
This end-to-end data science project is executed as part of the requirements for the McGill Master of Management Analytics program.

Project Description
Telecommunicaion industry has a huge presence in the economic world. It is estimated that the global telecom services was valued at USD 1,657.7 billion in 2020. One of the major problems Telcos (Telecommunication Companies) face is customer churn. According to Profitwell, the average churn rate in telecom businesses is 22%.

The initial analysis involves the following:

Data Collection
Business Understanding
EDA
Feature Engineering
Model Training
Model Evaluation
Causal Analysis To view the code, access the notebook located in the directory.
The final deployment involves the following:

Parameter optimisation with Optuna
Managing model runs with MLflow
Updating & monitoring model in production
Deployment using Databricks
To view the code, access the notebook.

Objective
This project aims is to use machine learning techniques to remedy the problem of customer churn and provide measurable business value to the telecommunication companies.

Pain Points
Churn leads to higher Customer Acquisition Costs & reduced revenue - acquiring new customers is more costly than keeping the existing ones.

High churn rates are more likely to compound over time.

Business Value
Increased revenue
Higher customer satisfaction and loyalty
Higher market share
Methodology Overview
Our team focuses on predicting whether or not a customer is likely to churn, using predictive modelling. Using this information of churn likelihood, we can take proactive steps. One of the most effective methods in marketing, is sending promotions or coupons to customers. Since we cannot send coupons to everyone due to unsustainability of this strategy & high distribution costs, we pick specific customers to send coupons to. To achieve this we leverage the predictive information into an optimization model, which recommends a coupon distribution strategy to minimize the loss of revenue (opportunity cost) as a consequency of customer churn. We productionalize the model by training multiple models, logging them & deploy them on databricks.

While Churn prediction might not require frequent predictions, relevant processes like credit card fraud detection may make use of the end-to-end processflow that has been implemented.
