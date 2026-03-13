# UrbanCart Retail Analytics (SQL Project)

## Project Overview

UrbanCart is a growing online retail business operating across multiple cities. The management team aims to become more **data-driven** by understanding customer behavior, improving product strategy, and optimizing revenue performance.

In this project, **SQL** is used to analyze UrbanCart's transactional dataset and answer **25 business questions** related to:

- Customer behavior
- Revenue performance
- Product performance
- Payment method usage
- Basket analysis and product bundling

The analysis provides actionable insights that can help the business improve **marketing decisions, product placement, and cross-selling opportunities**.

---

# Tools Used

- SQL  
- PostgreSQL  
- GitHub (Project Documentation)

---

# Dataset Structure

The analysis is based on a retail transactional database containing the following core entities.

---

## Customers

Information about registered customers.

**Key Fields**

- `customer_id`
- `full_name`
- `gender`
- `city`
- `signup_date`

---

## Orders

Contains order-level information.

**Key Fields**

- `order_id`
- `customer_id`
- `order_date`
- `payment_method`
- `order_status`

---

## Order Items

Details of products purchased within each order.

**Key Fields**

- `order_id`
- `product_id`
- `quantity`
- `price`

---

## Products

Product catalog and inventory details.

**Key Fields**

- `product_id`
- `product_name`
- `category`
- `stock_quantity`

---

# Business Questions Answered

The project answers **25 business questions**, grouped into major analytical themes.

---

## Customer & Order Fundamentals

- Total number of orders
- Unique customers
- Cities generating the most orders
- Repeat customer percentage
- Monthly order trends

---

## Revenue & Product Performance

- Total revenue generated
- Revenue by product category
- Top revenue-generating products
- Average order value (AOV)
- Inventory risk analysis

---

## Customer Behavior & Segmentation

- Highest spending customers
- Average products per order
- Gender-based purchasing behavior
- City-wise order value comparison
- Customer purchase behavior over time

---

## Payment & Order Flow Insights

- Most used payment methods
- Relationship between payment method and order status
- City payment preferences
- Payment method for high-value orders
- Items per order by payment method

---

## Advanced Basket Analysis

- Frequently purchased product combinations
- Most common product pairs
- Product pairs driving high-order values
- Potential bundle recommendations
- Cross-selling opportunities

---

# Key Insights

Some important insights discovered from the analysis:

- UrbanCart processed **1200 total orders** from **100 customers**
- **Barishal** generates the highest number of orders, while **Rajshahi** has the highest **average order value**
- **Fashion** and **Grocery** are the most revenue-generating product categories
- The **Power Bank (10000mAh)** is the highest revenue-generating individual product
- **Cash on Delivery (COD)** is the most frequently used payment method

### Frequently Purchased Product Pairs
- Potato 1kg + Peanut 500g  
- Farm Fresh Milk 1L + Potato 1kg  

### High-Value Product Bundles
- Miniket Rice 5kg + Power Bank 10000mAh

### Cross-Selling Opportunity
- Deshi Egg (12 pcs) + GP Internet Pack

---

# Repository Structure

```
UrbanCart-SQL-Analytics
│
├── UrbanCart Retail Analytics.sql
├── UrbanCart Retail Analytics.pdf
└── README.md
```

---

# Project Outcome

This project demonstrates how SQL can be used to:

- Extract insights from retail transactional data
- Analyze customer purchasing behavior
- Identify product bundling opportunities
- Support business decision-making through data

---

# Author

**Lutfor Shuvo**
Finance Undergraduate  
University of Chittagong  

**Interests**
- Data Analytics
- Business Intelligence
- Financial Analytics
- Data-driven decision making
