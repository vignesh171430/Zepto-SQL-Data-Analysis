
# Zepto Database Analysis (PostgreSQL)

## 📖 Project Overview
This project demonstrates an end‑to‑end **SQL analysis of Zepto’s product dataset** using PostgreSQL. It covers database schema creation, data exploration, cleaning, and analytical queries to extract meaningful insights about product categories, discounts, inventory, and revenue.

## 🎯 Objectives
- Create a structured PostgreSQL table for Zepto product data.  
- Explore the dataset to identify null values, duplicates, and stock status.  
- Clean the data by removing invalid records and standardizing units.  
- Perform analytical queries to uncover business insights such as top discounts, revenue by category, and inventory weight distribution.

## 🛠️ Tools & Technologies
- **Database:** PostgreSQL  
- **Language:** SQL  
- **Techniques:** Joins, Aggregations, Grouping, Window Functions, Case Statements  

## 📊 Key Features
1. **Schema Design**  
   - Defined `zepto` table with attributes like SKU, category, MRP, discount, stock status, and weight.  

2. **Data Exploration**  
   - Count of rows, sample data preview.  
   - Detection of null values.  
   - Identification of distinct product categories.  
   - Stock vs out‑of‑stock product counts.  
   - Duplicate product names.  

3. **Data Cleaning**  
   - Removed products with invalid prices (`mrp = 0`).  
   - Converted values from paise to rupees for consistency.  

4. **Data Analysis Queries**  
   - **Q1:** Top 10 best‑value products by discount percentage.  
   - **Q2:** High‑MRP products that are out of stock.  
   - **Q3:** Estimated revenue per category.  
   - **Q4:** Products with MRP > ₹500 and discount < 10%.  
   - **Q5:** Top 5 categories with highest average discount.  
   - **Q6:** Price per gram analysis for products above 100g.  
   - **Q7:** Categorization of products into Low, Medium, Bulk based on weight.  
   - **Q8:** Total inventory weight per category.  

## 🚀 Outcomes
- Clear insights into product pricing, discount strategies, and inventory distribution.  
- Demonstrated ability to clean and analyze real‑world retail data using PostgreSQL.  
- Showcased SQL proficiency through structured queries and business‑oriented analysis.
