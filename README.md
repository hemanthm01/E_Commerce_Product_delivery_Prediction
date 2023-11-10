# E_Commerce_Product_delivery_Prediction
E Commerce Product Delivery Prediction
-----------------------------------------
![image](https://github.com/hemanthm01/E_Commerce_Product_delivery_Prediction/assets/120650945/7e9822f7-ff8e-48cc-9c9f-755dd879df09)

## Project Overview:
The aim of this project is to predict whether products from an international e-commerce company will reach customers on time or not. Additionally, the project analyzes various factors influencing product delivery and studies customer behavior. The company primarily sells electronic products.

---------------------------------------------------------------------------------------------
## Data Dictionary:
The dataset used for model building contains 10,999 observations of 12 variables, including:

| Variable             | Description                                             |
|----------------------|---------------------------------------------------------|
| ID                   | ID Number of Customers                                 |
| Warehouse_block      | The Company's Warehouse block (A, B, C, D, E)          |
| Mode_of_Shipment     | The mode of shipment (Ship, Flight, Road)              |
| Customer_care_calls  | Number of calls made for shipment inquiries            |
| Customer_rating      | Customer rating (1 - Lowest, 5 - Highest)              |
| Cost_of_the_Product  | Cost of the product in US Dollars                     |
| Prior_purchases      | Number of prior purchases                              |
| Product_importance   | Product importance categorization (low, medium, high)  |
| Gender               | Gender of customers (Male, Female)                    |
| Discount_offered     | Discount offered on specific products                  |
| Weight_in_gms        | Weight of the product in grams                         |
| Reached.on.Time_Y.N  | Target variable (1 - Product did not reach on time, 0 - Product reached on time) |

---------------------------------------------------------------------------------------------------------------
## Conclusion
The aim of the project was to predict whether the product from an e-commerce company will reach on time or not. This project also analyzes various factors that affect the delivery of the product as well as studies the customer behavior. From the exploratory data analysis, I found that the product weight and cost has an impact on the product delivery. Where product that weighs between 2500 - 3500 grams and having cost less than 250 dollars had higher rate of being delivered on time. Most of the products were shipped from warehouse F though ship, so it is quite possible that warehouse F is close to a seaport.

The customer's behaviour also help in predicting the timely delivery of the product. The more the customer calls, higher the chances the product delivery is delayed. Interestingly, the customers who have done more prior purchases have higher count of products delivered on time and this is the reason that they are purchasing again from the company. The products that have 0-10% discount have higher count of products delivered late, whereas products that have discount more than 10% have higher count of products delivered on time.

Coming to the machine learning models, the decision tree classifier, random forest classifier and Logistic regression obtained highest accuracy of 100 without overfit. The K Nearest Neighbors had the lowest accuracy of 79%.
