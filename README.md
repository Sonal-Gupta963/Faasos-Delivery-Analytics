# Faasos-Delivery-Analytics

This project involves SQL-based data analysis on a fictional dataset inspired by **Faasos**, an Indian food delivery brand. The goal is to understand customer behavior, driver performance, order trends, and ingredient combinations based on structured relational data.

---

## 📊 Project Overview

This SQL project explores multiple facets of the food delivery workflow using normalized tables such as:

- **Drivers and their registration details**
- **Customer orders and item customization**
- **Driver delivery logs (duration, distance, cancellations)**
- **Roll recipes and ingredients**

---

## 🗃️ Dataset Structure

The project is based on 6 main tables:

| Table Name        | Description |
|-------------------|-------------|
| `driver`          | Driver IDs and registration dates |
| `ingredients`     | Master list of all possible roll ingredients |
| `rolls`           | Roll types (Veg/Non-Veg) |
| `rolls_recipes`   | Ingredients used per roll |
| `driver_order`    | Order delivery info per driver |
| `customer_orders` | Customer orders, timestamps, exclusions/inclusions |

---

## 🧠 Key Questions Answered

- How many orders did each customer place?
- What were the most commonly excluded or added ingredients?
- Which drivers had the most delivery cancellations?
- What is the average delivery time per kilometer?
- Which roll is most ordered and at what time of day?
- How do Veg vs Non-Veg orders differ across customers?

---

## 🛠 SQL Features Used

- Joins (INNER, LEFT)
- Aggregations (`COUNT`, `SUM`, `AVG`)
- String functions (`TRIM`, `LOCATE`, `LEFT`)
- Conditional logic with `CASE`
- Date/time functions (`DATEPART`, `DATEDIFF`)
- Subqueries and nested queries

---



