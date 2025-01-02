Synthetic Sales Data Generator
This project provides a Python-based generator for creating a realistic, synthetic sales dataset for a fictional beverage wholesale company. The data is tailored for use in analytics, pricing strategy development, and machine learning projects. It incorporates key features like customer segmentation (B2B and B2C), regional preferences, and dynamic pricing strategies.

Features
Dynamic Pricing
Adjust prices for seasonal demand (e.g., summer and Christmas peaks).
Incorporate inflation and premium brand pricing adjustments.
B2B and B2C Customer Logic
B2B Customers:
Discounts based on order quantities.
Flexible price ranges for dynamic pricing.
B2C Customers:
Fixed, inflation-adjusted pricing with no discounts.
Regional Preferences
Simulates regional product preferences (e.g., Erdinger Weißbier is preferred in Bavaria).
Probabilistic product selection based on predefined regional weights.
Multi-Item Orders
Customers can order multiple unique items per transaction, avoiding duplicates within the same order.
Dataset Structure
The generated dataset contains the following columns:

Column	Description
Order_ID	Unique identifier for each order.
Customer_ID	Unique identifier for each customer.
Customer_Type	Indicates whether the customer is B2B or B2C.
Product	Name of the product purchased.
Category	Product category (e.g., Soft Drinks, Alcoholic Beverages).
Unit_Price	Price per unit, including dynamic adjustments.
Quantity	Number of units purchased.
Discount	Discount applied (only for B2B customers).
Total_Price	Final price after applying discounts.
Region	Region of the customer (e.g., Bavaria, Berlin).
Order_Date	Date of the order, randomly generated within the given timeframe.
Month	Month of the order, derived from the order date.
Year	Year of the order, derived from the order date.

