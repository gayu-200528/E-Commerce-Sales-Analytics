# E-Commerce Sales & Customer Analytics 

##  Project Overview
This project analyzes e-commerce sales, customer behavior, product performance, and order status using Microsoft Power BI. The interactive dashboards help understand sales trends, identify top-performing products, and explore customer segments.

##  Project Objectives
- Analyze total sales, quantity, orders, and customers.
- Track monthly sales trends.
- Compare sales across product categories.
- Analyze payment methods and order statuses.
- Identify top-selling products and customers.
- Explore customer locations and segments.
- Analyze product prices and quantities sold.

##  Tools & Technologies
- **Microsoft Power BI** – Dashboard creation and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **CSV Files** – Data sources

##  Dataset Files
The project uses four CSV files:

| File | Description |
|---|---|
| `orders.csv` | Order details, dates, quantities, sales, and order status |
| `customers.csv` | Customer details, cities, segments, and signup dates |
| `products.csv` | Product names, categories, Product ID, and unit prices |
| `payments.csv` | Payment ID, Payment methods, payment Amounts, Payments dates, and payment status |

##  Dashboard Pages

### 1. Sales Analysis
- Total Sales
- Total Quantity
- Total Orders
- Total Customers
- Monthly Sales Trend
- Sales by Product Category
- Payment Method Analysis
- Order Status Analysis
- Top 5 Products by Sales

### 2. Customer Details
- Total Customers
- Total Sales
- Total Orders
- Customers by City
- Customers by Segment
- Top 5 Customers by Sales
- Sales by Customer Segment

### 3. Product Performance
- Total Products
- Total Sales
- Total Quantity
- Average Order Value
- Quantity by Product Category
- Unit Price by Product
- Product Details Table

## 🔗 Data Modeling
The report connects the four tables using relationships between their relevant keys:

- Customers → Orders
- Products → Orders
- Orders → Payments

These relationships help analyze sales, customer, product, and payment data together.

##  Key Insights
The dashboards can help users:
- Identify high-performing product categories.
- Track changes in monthly sales.
- Compare customer segments.
- Identify top products and customers by sales.
- Understand order status distribution.
- Explore product prices and quantities sold.

##  Project Structure

text
E-Commerce-Sales-Analytics/
├── E-Commerce-Sales-Analytics.pbix
├── orders.csv
├── customers.csv
├── products.csv
├── payments.csv
├── README.md
├── sales-analysis.png
├── customer-details.png
└── product-performance.png

 ## Dashboard Screenshots**

## 1. Sales Analysis Dashboard

![Sales Analysis](Sales_Analysis.png)

# Conclusion:
The Sales Analysis Dashboard provides insights into overall sales performance, total orders, revenue, and sales trends. It helps identify sales patterns over time and understand which areas contribute more to total sales. This dashboard supports better sales planning and business decision-making.

## 2. Customer Analysis Dashboard

![Customer Analysis](./Customer_Analysis.png)

# Conclusion:
 The Customer Analysis Dashboard helps understand customer information, customer segments, and purchasing behavior. It provides insights into customer distribution and helps identify important customer groups. These insights can help businesses improve customer satisfaction and develop better customer retention strategies.



## 3. Product Performance Dashboard

![Product Analysis](./Product_Analysis.png)

# Conclusion:
 The Product Performance Dashboard analyzes product performance using product-related information such as price, category, stock quantity, and ratings. It helps identify popular products and compare product performance. These insights can support better inventory management and product-related business decisions.

## Final Conclusion

The E-Commerce Sales & Customer Analytics project demonstrates how Power BI can be used to analyze e-commerce data and convert raw data into meaningful business insights. The project uses data cleaning and transformation, data modeling, and DAX measures to create interactive dashboards for sales analysis, customer analysis, and product performance.
These dashboards help users understand sales trends, customer behavior, and product performance in a clear and organized way. Overall, the project demonstrates the importance of data visualization and business intelligence in supporting data-driven decisions and improving business performance.

