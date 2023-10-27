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
<img src="https://user-images.githubusercontent.com/140676710/278646644-01d68b03-14dc-4b56-9844-9654ad604f21.png" width="500">
View the potential status of delivered and canceled orders :
* Delivered orders are higher than canceled orders with a very big difference
* High total order delivery affects total revenue with a value of 97.77% higher than canceled orders with a value of 2.23%
* 17925 delivered orders and 3746 canceled orders. This high order success is an opportunity to continue to increase orders by retaining these customers as royal customers


3.  Comparison of Canceled and Delivered Based on total amount
<img src="https://user-images.githubusercontent.com/140676710/278648246-d00a3668-8665-4489-b823-0da61feeaf54.png" width="500">
4. Comparison of Canceled and Delivered Based on total orders
<img src="https://user-images.githubusercontent.com/140676710/278647573-55b647e1-1bef-440b-add0-f937a9272e43.png" width="500">
5. Heatmap - Correlation
<img src="https://user-images.githubusercontent.com/140676710/278648724-b6405f3b-aa38-41c3-a91e-5367007035bd.png" width="500">

## User Retention Analysis
<img src="https://user-images.githubusercontent.com/140676710/278649202-8af5300e-5371-4f56-ac07-62e1caf1db86.png" width="500">

## User Segmentation

