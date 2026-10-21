# E-commerce Database – SQL Analysis (MySQL)

A MySQL database for an online shop, with SQL queries to analyze revenue,
customers and orders.

## Objective
To practice database design and answer business questions using SQL.

## Database Design
5 related tables:
- `customers` – customer details
- `products` – product, category, price, stock
- `orders` – orders and their status (Delivered, Pending, Cancelled)
- `order_items` – products in each order
- `payments` – payment mode and amount

Relationships use primary keys and foreign keys.

## Data
Sample data created by me for practice:
20 customers, 20 products, 20 orders, 22 order items and 15 payments.
This is not real business data.

## SQL Concepts Used
CREATE TABLE, INSERT, PRIMARY KEY, FOREIGN KEY, JOIN, GROUP BY,
SUM, COUNT, WHERE, ORDER BY, aliases

## Business Questions Answered
1. What is the total revenue?
2. Which products earn the most revenue (delivered orders only)?
3. Who are the top customers by spend?
4. How many orders were cancelled?

## Key Results (sample data)
- Total revenue: ₹21,225
- Top product: Python Hoodie (₹3,998)
- Top customer: Simran Kaur (₹3,198)
- Cancelled orders: 3 out of 20

## Files
- `ecommerce_database.sql` – table creation, sample data and queries
- `er_diagram.png` – database diagram
- `query_results.png` – sample query output

## Author
**Sikandar Khan**, aspiring Data Analyst, India

🔗 [LinkedIn](https://www.linkedin.com/in/sikandar-khan-5ba465422/)
💻 [GitHub](https://github.com/sikandar-data-analyst)
📧 sikandarkhankhan980@gmail.com
