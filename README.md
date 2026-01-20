# 🍕 Pizza Sales Analysis using SQL

## 📌 Project Overview
This project analyzes a **Pizza Sales Dataset** using **SQL** to extract meaningful business insights.  
The goal is to understand sales performance, customer ordering patterns, and product popularity through well-structured SQL queries.

This project demonstrates skills in:
- Database design
- SQL querying
- Data analysis
- Business insight generation

---

## 🗂️ Dataset Description
The dataset consists of the following tables:

- **orders** – Stores order date and time  
- **order_details** – Stores order line items and quantities  
- **pizzas** – Stores pizza size and price  
- **pizza_types** – Stores pizza category and ingredients  

---

## 🧩 Database Schema
The project follows a **relational database model**, later converted into a **star schema** for analytical queries.

### Relationships:
- One pizza type → many pizzas  
- One order → many order details  
- Many-to-many relationship between orders and pizzas resolved using `order_details`

---

## ⭐ Star Schema (For Analytics)
- **Fact Table:** `fact_pizza_sales`
- **Dimension Tables:**
  - `dim_date`
  - `dim_pizza`
  - `dim_pizza_type`
  - `dim_order`

This structure enables faster and simpler analytical queries.

---

## 🔍 SQL Analysis Performed
Some of the key analyses include:

- Total revenue generated
- Total number of orders
- Most popular pizza types
- Best-selling pizza sizes
- Sales by category
- Peak ordering hours
- Revenue trends by date

---

## 🛠️ Tools & Technologies
- **Database:** MySQL  
- **Language:** SQL  
- **Environment:** MySQL Workbench  
- **Version Control:** Git & GitHub  

---

## 📊 Sample Insights
- Identified the **top-selling pizzas** by revenue and quantity  
- Analyzed **customer order patterns** by time of day  
- Determined the **most profitable pizza categories**

---

Author ~ Tusshar Singh

