# Sales-detail-Power-Bi

E-Commerce Sales Analysis Dashboard
Project Overview
This project involves a comprehensive analysis of e-commerce sales data to derive actionable insights into business performance, customer behavior, and profitability. Using a combination of raw transaction data and customer demographics, this project visualizes key metrics to help stakeholders understand sales trends and optimize operational strategies.

The analysis is powered by a Power BI Dashboard (First Report.pbix) which connects transactional details with geographical order data.

Dataset Description
The repository contains two primary datasets in CSV format:

1. Details.csv
Contains granular information about each transaction.

Order ID: Unique identifier for each order.

Amount: Total sales value of the transaction.

Profit: Profit or loss generated from the sale.

Quantity: Number of items purchased.

Category: Broad product category (e.g., Electronics, Furniture, Clothing).

Sub-Category: Specific product type (e.g., Phones, Chairs, Saree).

PaymentMode: Method of payment (e.g., COD, EMI, Credit Card, UPI).

2. Orders.csv
Contains customer-level details and order timelines.

Order ID: Key to link with the Details dataset.

Order Date: The date the transaction occurred.

CustomerName: Name of the buyer.

State: The Indian state where the order was delivered.

City: The specific city of delivery.

Key Features & Insights
The Power BI dashboard provides the following analytics:

Profitability Analysis: Identification of high-profit vs. loss-making product categories.

Sales Performance: Tracking total sales amount and quantity across different months and years.

Geographical Mapping: Visualization of sales distribution across various Indian states and cities (Top performing regions like Maharashtra, Uttar Pradesh, and Delhi).

Customer Segmentation: Analysis of purchasing patterns by customer and location.

Payment Trends: Breakdown of preferred payment methods used by customers.

Technologies Used
Power BI: For data modeling and interactive visualization.

Python/Pandas: (Optional) Used for initial data cleaning and exploratory data analysis.

CSV: Data storage format.

How to Use
Clone the Repository:

Bash
git clone https://github.com/your-username/ecommerce-sales-analysis.git
View the Data: Explore Details.csv and Orders.csv to understand the raw data structure.

Open the Dashboard:

Ensure you have Power BI Desktop installed.

Open the First Report.pbix file to interact with the visualizations.

If prompted, refresh the data sources to link the CSV files from your local directory.

Sample Data Insight
Based on the data, the store handles a diverse range of categories, with significant transactions in Clothing and Electronics. The Profit column indicates a mix of highly profitable items and some that may require pricing strategy adjustments.

Suggested Repository Structure
Plaintext
├── Data/
│   ├── Details.csv
│   └── Orders.csv
├── Reports/
│   └── First Report.pbix
├── README.md
└── .gitignore
