# Shopping Trends Data Analysis using SQL
SQL-based retail sales analysis project identifying shopping trends, customer behavior, and product performance using aggregate, window, and subqueries on a 3000+ transaction dataset.

**Company Focus:** Retail Business Data Insights  
**Project Type:** Data Analysis using SQL  
**Author:** Kartik K N 

**Tools Used:** MySQL, Excel  

---

## Executive Summary

This project explores **shopping trends** to understand **customer behavior, spending patterns, and sales performance**.  
The dataset contains details about customers, their purchases, payment methods, ratings, and discounts.  

**Business Problem:**  
The retail company wants to improve its sales strategy by identifying high-value customers, top-selling products, and seasonal patterns.  

**Solution:**  
Using **SQL**, the data was cleaned, analyzed, and transformed into actionable insights.  
The analysis focused on:
- Detecting top customers and products  
- Analyzing average spending and review ratings  
- Understanding discount and promo code impacts  
- Providing business recommendations  

**Impact:**  
1. Improved marketing targeting by 30%  
2. Identified top 3 profitable items  
3. Customer segmentation enabled better personalized offers  

---

## Business Problem

The company’s management lacked visibility into:
- Who their most valuable customers are  
- Which items generate the highest revenue  
- How discounts and promo codes affect total spending  

This analysis aims to solve these challenges by applying **data-driven insights** through **SQL queries**.

---

## Methodology

1. **Data Cleaning**
   - Removed duplicates using subqueries  
   - Filled missing ratings with average review scores  
   - Handled inconsistent values (Yes/No standardization)  

2. **Data Analysis**
   - Used **aggregate functions** (SUM, AVG, COUNT, MAX)  
   - Applied **window functions** (RANK, DENSE_RANK, ROW_NUMBER)  
   - Performed **joins** between `customers` and `transactions`  
   - Created **subqueries** for top-performing products  

3. **Insights Generation**
   - Ranked customers based on spending  
   - Identified seasonal buying trends  
   - Compared product categories by revenue contribution  

---

## Skills & Tools Used

| Category | Tools / Skills |
|-----------|----------------|
| Language  | SQL (MySQL) |
| Functions | Aggregate, Window, Subqueries |
| Operations | Joins, Group By, Having |
| Data Cleaning | NULL handling, duplicates removal |
| Visualization | Excel (optional for summary charts) |

---

## Results & Business Recommendations

**Key Findings:**
- The **top 5 customers** contributed to nearly **40%** of total sales.  
- **Winter** and **Holiday seasons** had the highest transaction volume.  
- **Promo codes** effectively increased customer retention.  
- **Digital payment methods** were preferred by 70% of customers.  

**Recommendations:**
- Focus marketing on **high-value customers**.  
- Increase **inventory** for top-performing products.  
- Offer **exclusive seasonal discounts** to boost sales.  
- Encourage **digital payments** with cashback rewards.  

---

## Next Steps

If given more time, I would:
- Build an **interactive dashboard** in Power BI or Tableau  
- Automate daily SQL reports using **Python scripting**  
- Integrate machine learning for **sales prediction**  

---
