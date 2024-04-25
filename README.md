# E-Comm-SQL Analysis

# Description:
Data collected on warehouse operations, product delivery, and customer ratings are investigated here. Approximately 60% of all deliveries made from this warehouse are late. To find out the cause of this issue, I perform EDA using SQL.

For this project, I pull a dataset from Kaggle, link below. Queried in Big Query. 

https://www.kaggle.com/datasets/prachi13/customer-analytics/data

# Dataset
The dataset used here is the E-Commerce Shipping Data from Kaggle posted by Prachi Gopalani.

Contents of the dataset are described on Kaggle but posted here for completeness:

The dataset used for model building contained 10999 observations of 12 variables. The data contains the following information:

- ID: ID Number of Customers.
- Warehouse block: The Company have big Warehouse which is divided in to block such as A,B,C,D,E.
- Mode of shipment:The Company Ships the products in multiple way such as Ship, Flight and Road.
- Customer care calls: The number of calls made from enquiry for enquiry of the shipment.
- Customer rating: The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best).
- Cost of the product: Cost of the Product in US Dollars.
- Prior purchases: The Number of Prior Purchase.
- Product importance: The company has categorized the product in the various parameter such as low, medium, high.
- Gender: Male and Female.
- Discount offered: Discount offered on that specific product.
- Weight in gms: It is the weight in grams.
- Reached_on_Time_Y_N: It is the target variable, where 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.
