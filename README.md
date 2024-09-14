# Aamazon sales dashboard  

# Sales Performance:

The dashboard shows that the company has made 9.71M in total sales, with 2K units left in stock and 29K units sold.

# Product Performance:

The dashboard shows the sales performance of different product categories, such as Boys Boxer Shorts, Boys Clothing Sets, Boys Dhotis Mundus, Boys Ethnic Wear, Boys Hats Caps, Boys Kurta Sets, Boys Pyjama Sets, and Boys Sports Shirts.
The "Boys Kurta Sets" category has the highest sales, followed by "Boys Pyjama Sets."

# Geographical Performance:

The dashboard shows the total amount of sales by state and city. The highest sales are in Maharashtra and Karnataka, followed by Uttar Pradesh and Tamil Nadu.
The dashboard also shows the percentage of sales by city. The highest sales are in Bengaluru, Hyderabad, and Mumbai, followed by New Delhi and Chennai.

# Order Fulfillment Performance:

The dashboard shows the status of different orders, including pending, pending-waiting for pick up, shipped-damaged, shipped-delivered to buyer, shipped-lost in transit, shipped-out for delivery, shipped-picked up, shipped-rejected by buyer, shipped-returned to seller, and shipped-returning to seller.

# Daily Performance:

The dashboard shows the sum of total amount by day. The sales have been relatively consistent over the past 30 days, with a slight dip around day 30.
This dashboard provides a comprehensive overview of the company's sales performance. It allows the company to track its progress, identify areas for improvement, and make informed decisions about its business.

# Tables used 

Table 1: "amazon-fashion - YT"

This table seems to hold information about products sold on Amazon. The columns include:

amazon_prime_y_or_n: Indicates whether the product is eligible for Amazon Prime delivery.
asin: Amazon Standard Identification Number (ASIN) - a unique identifier for each product.
best_seller_tag_y_or_n: Indicates whether the product is a best-seller.
brand: The brand of the product.
Category: The category the product belongs to.
colour: The color of the product.
delivery_type: The type of delivery available for the product.
description: A description of the product.
discount_percentage: The percentage of discount offered on the product.
Table 2: "Amazon"

This table likely contains sales data for products sold on Amazon. The columns include:

Amount: The price of the product.
ASIN: The unique identifier for each product.
Category: The category the product belongs to.
Column20: An unknown column.
Courier Status: The status of the delivery.
currency: The currency used in the transaction.
Date: The date of the sale.
fulfilled-by: Who is responsible for fulfilling the order.
Fulfilment: The type of fulfillment method used.
Table 3: "Sale_Option"

This table likely contains information about different sales options or promotions offered by Amazon. The columns include:

Name: The name of the sale option.
Type: The type of sale option.
Relationship between tables

The tables are connected using relationships. The "amazon-fashion - YT" table is connected to the "Amazon" table using the "ASIN" column. This suggests that each product in the "amazon-fashion - YT" table has a corresponding sales record in the "Amazon" table. There is no visible relationship between the "Sale_Option" table and the other two tables.
