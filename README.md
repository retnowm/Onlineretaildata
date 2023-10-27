Here I tried to do Analysis on the online retail sales dataset in 2010 to see the behavior of users who return to make transactions and the characteristics of the users

## Variables Description:
- order_id : Order number
- product_code : Product number
- product_name : Product name
- quantity : Large number of orders
- order_date : Order date
- price : Product price
- customer_id : Customer number

## Data Cleaning
Data cleaning is used to identify data that has a NaN value. This data cleaning includes to detect any missing values in each column and changing certain column data types to support the analysis process. There is a creation of a new column for calculating the results of the quantity and price columns. Include a manufacturing column for order status which can be seen from the order_id column.

## Data Visialization & Correlation
1. Summary of Delivered & Cancelled Orders
