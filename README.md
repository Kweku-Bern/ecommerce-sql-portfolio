# 🛒 E-Commerce SQL Portfolio Project

This project simulates a small e-commerce platform using SQL. It includes a relational database schema with realistic customer, product, and order data. This project is part of my professional SQL portfolio, and it showcases my ability to design schemas, insert meaningful data, and run business-driven SQL queries.

---

## 📦 Database Structure

The database contains four main tables:

| Table        | Description |
|--------------|-------------|
| **Customers** | Stores customer details like name(first & last), email, registration date city, and country |
| **Products**  | Contains product information like id, name, category, price, and quantity |
| **Orders**    | Records order metadata like date, customer, total amount, and status |
| **Order_Items** | Lists each item in an order including quantity and unit price |

---

## 📁 Files in This Repository

| Folder/File                    | Purpose |
|-------------------------------|---------|
| `schema/create_tables.sql`    | Contains all `CREATE TABLE` statements to define the schema for: `Customers`, `Products`, `Orders`, and `Order_Items`. |
| `data/insert_data.sql`        | Contains `INSERT INTO` statements to populate all four tables with realistic sample data. Includes customer info, orders, product catalog, and order item details. |
| `queries/basic_queries.sql`   | Basic SQL queries: total customers, product list by category, orders by customer, etc. |
| `queries/analysis_queries.sql`| Business-focused queries: monthly revenue, top-selling products, customer behavior, sales trends. |
| `notes/data_issues.md`        | Documents data quality issues like inconsistent prices (e.g., product 102 sold at different unit prices) or orders with quantity = 0 (e.g., Order 1007). |
| `analysis/reports.md`         | Markdown file explaining insights from queries, e.g., which month had highest sales, most active customers, etc. |
| `visuals/` *(optional)*       | Folder to store charts (e.g., revenue over time, product sales) created using Excel or Python. Not required but recommended for data storytelling. |

---


