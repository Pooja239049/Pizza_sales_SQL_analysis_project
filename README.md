#  Pizza Sales Analysis Using SQL

##  Project Overview
This project focuses on analyzing pizza sales data using SQL and MySQL 
to answer key business questions and generate actionable insights. 
The analysis covers sales performance, customer preferences, revenue 
trends, popular pizza categories, and peak ordering hours.

##  Tools & Technologies
- **SQL / MySQL** — Data querying and analysis
- **MySQL Workbench** — Query execution and result visualization
- **Canva** — Presentation design

## 🗃️ Dataset
The dataset contains 4 interrelated tables:
| Table | Description |
|-------|-------------|
| `orders` | Order ID, date, and time |
| `orders_details` | Order ID, Pizza ID, quantity |
| `pizzas` | Pizza ID, type, size, price |
| `pizza_types` | Name, category, ingredients |

## Key Business Questions Solved
1. Total number of orders placed →
2. Total revenue generated from pizza sales
3. Highest-priced pizza → 
4. Most common pizza size ordered 
5. Top 5 most ordered pizza types → Classic Deluxe, BBQ Chicken, Hawaiian, Pepperoni, Thai Chicken
6. Total quantity ordered by pizza category → Classic (14,888) | Supreme (11,987) | Veggie (11,649) | Chicken (11,050)
7. Peak ordering hours 

##  Key Insights
- Large pizzas dominate customer orders across all categories
- Classic pizza category has the highest demand
- Lunch hours (12–1 PM) are peak business hours
- The Greek Pizza is the premium offering at $35.95

## 📁 Files
- `pizza_sales_queries.sql` — All SQL queries used in the analysis
- `Pizza_Sales_Analysis_Presentation.pdf` — Full project presentation
