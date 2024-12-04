# Dominos---Predictive-Purchase-Order-System

Problem Statement:
Dominos wants to optimize the process of ordering ingredients by predicting future sales and creating a purchase order. By accurately forecasting sales, Dominos can ensure that it has the right amount of ingredients in stock, minimizing waste and preventing stockouts. This project aims to leverage historical sales data and ingredient information to develop a predictive model and generate an efficient purchase order system.

Business Use Cases:
Inventory Management: Ensuring optimal stock levels to meet future demand without overstocking.
Cost Reduction: Minimizing waste and reducing costs associated with expired or excess inventory.
Sales Forecasting: Accurately predicting sales trends to inform business strategies and promotions.
Supply Chain Optimization: Streamlining the ordering process to align with predicted sales and avoid disruptions.

Approach:

1) Data Cleaning
2) test the predictions with multiple algorithms like ARIMA, SARIMAX ,FBPROPHET & XGBOOST
3) XGBOOST gave a good performance metrics
4) so train the model using XGBOOST
5) merge the predicted selling quantity with ingridiants data
6) multiply the predicted quantity and ingridiants qty used for each pizza

Output:

when the user enter the week upcoming week number for purchasing, the system will give the total quantity of each ingridants needed.

thank you,
Rafadh
