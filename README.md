# Shopping Portal - SQL Practice Project

A SQL practice project simulating an e-commerce (Shopping Portal) database — 
built with table creation, data insertion, and query exercises covering 
SELECT, WHERE, LIKE, BETWEEN, ORDER BY, and multi-condition filtering.

## 📌 About

This project contains a relational database schema for a shopping portal 
with 5 interconnected tables, along with 50+ practice SQL queries 
(with questions and expected outputs) useful for learning and practicing SQL.

## 🗂️ Database Schema

The database consists of 5 tables:

| Table | Description |
|---|---|
| `Customer` | Stores customer details (name, email, mobile, gender, city) |
| `Category` | Product categories (Electronics, Clothing, Books) |
| `Product` | Products with price, stock, brand, and category |
| `Orders` | Customer orders with payment mode and status |
| `Order_Details` | Line items for each order (product, quantity, price) |

**Relationships:**
- `Product.Category_ID` → `Category.Category_ID`
- `Orders.Customer_ID` → `Customer.Customer_ID`
- `Order_Details.Order_ID` → `Orders.Order_ID`
- `Order_Details.Product_ID` → `Product.Product_ID`

## 📁 Files

| File | Description |
|---|---|
| `ShoppingPortal_Queries.docx` | Table creation, insert, and select-all queries |
| `ShoppingPortal_Full_Queries.docx` |
