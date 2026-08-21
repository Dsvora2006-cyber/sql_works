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
# Shopping Portal — SQL Practice (DDL, DML & Queries)

A SQL practice project simulating a simple e-commerce/shopping portal database. Includes schema creation, sample data, practice queries (SELECT and more), and a dedicated set of UPDATE query exercises — all with sample execution outputs.

## 📁 Project Structure

```
├── ShopingPortal.docx     # Schema, sample data, and student practice questions
├── update_data.docx       # UPDATE query practice with before/after result tables
└── README.md
```

## 🗄️ Database Schema

| Table | Description |
|---|---|
| `Customer` | Customer details — name, email, mobile, gender, city, registration date |
| `Category` | Product categories (Electronics, Clothing, Books, etc.) |
| `Product` | Products with price, stock, brand, and linked category |
| `Orders` | Customer orders with date, amount, payment mode, and status |
| `Order_Details` | Line items linking orders to products with quantity and price |

## 📝 What's Inside

**`ShopingPortal.docx`**
- Table creation (DDL) with primary keys, foreign keys, and check constraints
- Sample `INSERT` data for all tables
- Student practice questions (SELECT/DQL) with query + formatted output

**`update_data.docx`**
- `UPDATE` statement practice — customer city/email, product stock/price/brand, order status
- Each question shows the query, rows-affected result, and the table after the update

## ▶️ How to Use

1. Run the schema + sample data script to set up the tables (Oracle SQL).
2. Try solving each practice question yourself before checking the given answer.
3. Compare your output against the provided formatted result tables.

## 🛠️ Tech

- **Database:** Oracle SQL
- **Format:** `.docx` practice sheets

## 📌 Notes

- Sample dates and IDs are for practice purposes only.
- Feel free to fork and add your own queries (JOINs, aggregations, subqueries, etc.).

## 🔗 Connect

- LinkedIn: [linkedin.com/in/darshan-vora2006]

| File | Description |
|---|---|
| `ShoppingPortal_Queries.docx` | Table creation, insert, and select-all queries |
| `ShoppingPortal_Full_Queries.docx` |
