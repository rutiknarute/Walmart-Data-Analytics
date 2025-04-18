# Walmart-Data-Analytics

## ⚙️ Tools & Technologies Used

- **Python 3.x**
  - Jupyter Notebook
  - pandas
  - mysql-connector-python
  - sqlalchemy
  - pymysql / psycopg2 (if using different DB engines)
- **MySQL**
- **SQL** (Aggregate functions, Window functions, Date/Time functions, Nested Queries)
- **Matplotlib / Seaborn** (for optional visualizations)

---

## 🧠 Business Questions Solved

1. **Transactions by Payment Method**  
   How many transactions occurred, and how much quantity was sold using each payment method?

2. **Top Rated Categories by Branch**  
   What is the highest-rated product category in each Walmart branch?

3. **Busiest Days by Branch**  
   Which day of the week sees the most customer traffic in each branch?

4. **Total Quantity by Payment Method**  
   How many items were sold per payment method overall?

5. **Rating Analysis by City and Category**  
   What are the average, minimum, and maximum ratings per category in each city?

6. **Preferred Payment Method by Branch**  
   What is the most frequently used payment method in each branch?

7. **Most Active Time Slot**  
   When are most items sold (Morning, Afternoon, or Evening) in each branch?

8. **Top-Selling Categories**  
   Which product categories perform the best in terms of sales quantity?
   
---
# System Requirements

Python 3.7+
Jupyter Notebook
VS Code (optional for editing)
MySQL Server (e.g., MySQL 8.0)

---

## 💻 Sample SQL Query

```sql
SELECT category, SUM(quantity) AS Total_Units_Sold
FROM walmart
GROUP BY category
ORDER BY Total_Units_Sold DESC;



     
