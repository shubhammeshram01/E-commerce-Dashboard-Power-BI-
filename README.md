# E-commerce-Dashboard-Power-BI-
Analyzed e-commerce data and designed a dashboard on PowerBI. The goal was to uncover key insights into customer behavior, sales performance, and product trends, making the data easier to understand and act upon.

## Data Description :
The e-commerce dataset contains 113,270 rows and 21 columns. Below is a description of the key columns:

* customer_id: Unique identifier for each customer.
* customer_first_name / customer_last_name: First and last name of the customer.
* category_name: The product category (e.g., Office Supplies, Furniture).
* product_name: Name of the purchased product.
* customer_segment: Customer classification (e.g., Corporate, Consumer).
* customer_city / customer_state / customer_country / customer_region: Geographical details of the customer.
* delivery_status: The status of the order's delivery.
* order_date / ship_date: The order date and the shipping date.
* order_id: Unique identifier for each order.
* shipping_type: The type of shipping selected (e.g., Second Class, First Class).
* days_for_shipment_scheduled: Number of days scheduled for shipment.
* days_for_shipment_real: Actual number of days taken for shipment.
* order_item_discount: Discount applied to the order items.
* sales_per_order: Total sales value for each order.
* order_quantity: Quantity of items in the order.
* profit_per_order: Profit generated from each order.
* 
## To create a dashboard on PowerBI, I have followed the folwing steps :
1) Import data from the SQL Server (Extract Data)
2) Transform data
3) Load Data
4) Data modelling
5) Write DAX - CAalculated column and measure
6) Building Report
7) Publish Report
8) Share and Collaborate

## Following measures are created :
* TOTALYTD (Year to Date) Sales, TOTALYTD Quantity, TOTALYTD Profit, TOTALYTD Profit Margin
* PreviousYTD Sales, PreviousYTD Qunatity, PreviousYTD Profit, PreviousYTD Profit Margin
* YoY (year on year) Sales, YoY Profit, Yoy Quantity, YoY Profit Margin
* Profit Trend, Sales Trend, Quantity Trend, profit Margin Trend

## Following charts are created :
* Pie chart
* Bar chart
* Matrix Table
* KPI
* Trend Icon created to understand increasing-decreasing values
* Line area chart

## Key Insights :
* The West region has the highest YTD sales which is around 3.72M
* Total YTD sales and profit are 11.53M, 1.34 M respectively
* Profit margin is around 11.58% which calculated as sum(profit per order)\sum(sales per order)
* The YoY sales and YoY quantity have decreased by 0.83% and 7.29%
* The YoY sales for Office Supplies and technology have decreased
* YTD profits and YTD profit margins have increased by 4.50% and 5.375 respectively
* The Standard Shipping Class type has the highest YTD sales which contributes to 60.51%
* Staple envelope is the highest-selling product and Redifom Phone message book is the lowest-selling product

* ## E-commerce Dashboard :

  <img src = "https://github.com/shubhammeshram01/E-commerce-Dashboard-Power-BI-/blob/main/Dashboard%20Screeshot.png">

## Project Files
|Project Name| Dashboard | CSV File | My Linkedin | My Github |
|-|-|-|-|-|
|E-commerce Data Analysis| [Link](https://github.com/shubhammeshram01/E-commerce-Dashboard-Power-BI-/blob/main/Dashboard%20Screeshot.png) | [CSV](https://github.com/shubhammeshram01/E-commerce-Dashboard-Power-BI-/blob/main/ecommerce_data.csv) | [Linkedin](https://www.linkedin.com/in/shubhammeshram01/) | [Github](https://github.com/shubhammeshram01) |
