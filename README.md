# AquaFizz Employee Compliance and Sales Analysis

## 1. Project Overview

### Objective
The main goal of this project is to analyze employee working hours and customer order data to ensure compliance with AquaFizz’s policies and optimize sales. The analysis involves examining working hours for compliance and generating business insights from customer and sales data.

### Company Background
AquaFizz is a newly established beverage startup offering health-focused sparkling water beverages. The company aims to provide refreshing, nutrient-enhanced drinks while promoting overall wellness.

### Business Task
- Analyze employee working hours for compliance with company standards  
- Analyze sales data to gain insights into customer behavior  
- Identify top-performing products  

---

## 2. Data Understanding

### Employee Working Hours Data
**Dataset Name:** Workers Timing Dataset  

Includes:
- Time of entry  
- Time of exit  

---

### Orders Data
**Dataset Name:** Orders Dataset  

Includes:
- `date` – Date the order was placed  
- `order_id` – Unique identifier for each order  
- `customer_id` – Identifier linking the order to a customer  
- `beverage` – Type of beverage ordered  
- `cost_price` – Cost price of the beverage  
- `selling_price` – Selling price of the beverage  

---

### Customers Data
**Dataset Name:** Customer Dataset  

Includes:
- `customer_id` – Unique identifier  
- `first_name` – First name  
- `last_name` – Last name  
- `email` – Email address  
- `city` – Customer city  
- `country` – Country of residence  
- `user` – User type identifier  
- `code` – Internal customer code  

---

## 3. Data Preprocessing

### Employee Working Hours Processing
- Convert benchmark working time (8 hours 30 minutes → **8.5 hours**)  
- Calculate actual working hours (convert minutes to decimal)  
- Compare with benchmark (tolerance: **-6 minutes**)  
- Break total time into hours and minutes  
- Calculate deviation for non-compliance  
- Generate non-compliance messages with date and deviation  

---

### Orders & Customers Data Processing

#### Profit Calculation
Profit = Selling Price - Cost Price
#### Key Analyses
- Top 5 customers by total sales  
- Top cities by sales  
- Monthly profit analysis  
- Highest profit margin beverage  
- Top 10 beverage purchasers  
#### Profit Margin Formula
Profit % = (Selling Price - Cost Price) / Cost Price × 100
#### Dashboard
Create an Excel dashboard including:
- Sales by top customers  
- Sales by cities  
- Monthly trends  
- Profit margins  

---

## 4. Analysis Tasks

### Profit per Sale
Example:
TropicalTwist Profit = 96.8112 - 45.46 = 51.3512
### Tasks
- Calculate profit per order  
- Identify top 5 customers by sales  
- Identify top cities by sales  
- Perform monthly sales analysis  
- Find highest profit % beverage  
- Identify top 10 beverage purchasers  

### Dashboard Requirements
- Sales by top customers  
- Sales by cities  
- Monthly trends  
- Profit margin by beverage  

---

## 5. Conclusion

### Employee Compliance
Ensure employees meet required working hours and flag discrepancies.

### Sales Insights
Identify top products, customers, and locations to support business decisions.

---
