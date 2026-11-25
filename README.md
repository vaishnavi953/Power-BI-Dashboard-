# India Sales Performance Dashboard – Power BI

Created an interactive Power BI dashboard to analyze sales and profit data across India for 2018.

**Author:** Vaishnavi  
**Tool:** Microsoft Power BI Desktop  
**Skills:** Power BI, DAX, Data Cleaning, Data Visualization, Data Analysis

## Project Objective

The main aim of this project was to understand the company's sales and profit performance. I analyzed different categories, products, customers, states and cities to find out which areas were performing well and which needed improvement.

## Dataset

The project uses two tables: Orders and Details, connected using Order ID.

| Table | Rows | Columns |
|---|---:|---|
| Orders | 500 | Order ID, Order Date, Customer Name, State, City |
| Details | 1,500 | Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode |

**Period:** January – December 2018

## Key Metrics (KPIs)

- Total Sales: ₹437,771
- Total Profit: ₹36,963
- Profit Margin: 8.44%
- Total Quantity: Around 5.6K
- Total Customers: 336
- Total Orders: 500
- Average Order Value: ₹875.54

## DAX Measures

Created DAX measures to calculate:

- Total Sales
- Total Profit
- Total Quantity
- Profit Margin %
- Total Customers
- Total Orders
- Average Order Value

## Dashboard Features

- KPI cards for sales, profit, quantity and customers.
- Slicers to filter data by state, city, date and payment mode.
- Sales analysis by state.
- Profit analysis by category and sub-category.
- Profit comparison across cities.
- Quantity sold by category using a donut chart.
- Orders by payment mode using a donut chart.
- Monthly profit analysis.

## Key Insights

1. Electronics had the highest sales, around ₹166K, but its profit margin was lower than Clothing.
2. Clothing had the highest quantity sold, contributing around 63% of total quantity.
3. Some products, such as Furnishings, Electronic Games, Kurti, Skirt and Leggings, were making losses.
4. Profit changed from month to month, with losses in May, July, September and December.
5. Rajasthan and Andhra Pradesh had negative profits.

## What I Learned

- How to connect multiple tables and create relationships in Power BI.
- How to create DAX measures for business calculations.
- How to use slicers and different charts.
- How to analyze sales and profit data.
- How to find useful insights from business data.
