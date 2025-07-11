#  Sales Data Analysis using SQL

This project presents a detailed analysis of sales transactions stored in a relational database. The analysis uses SQL queries to extract insights related to products, sales representatives, regions, customer behavior, and discount trends.

---

##  Database Overview

- **Database Name**: `Sales`
- **Table**: `sales_data`

###  Table Fields

####  Product Details
- `Product_ID`
- `Product_Category`
- `Unit_Cost`
- `Unit_Price`

####  Sales Transaction Details
- `Sale_Date`
- `Sales_Rep`
- `Region`
- `Sales_Amount`
- `Quantity_Sold`
- `Discount`

####  Customer and Channel Details
- `Customer_Type`
- `Payment_Method`
- `Sales_Channel`
- `Region_and_Sales_Rep`

---

##  SQL Queries Performed

- Retrieve **all sales records**
- List **distinct product categories**
- Filter sales by **Sales_Rep = 'Bob'**
- Get **Top 5 highest Sales_Amount**
- Find sales with **Discount > 0.10**
- Display sales from the **South region**
- Identify Sales_Reps who sold **Electronics**
- List **new customers** with discounts < 0.05
- Aggregate **total Sales_Amount by Region**
- Show **total sales and average discount** by Payment Method
- Find the **month with highest Sales_Amount**
- Compute **average Unit Cost and Unit Price** per product
- Find **sales with above-average discounts**
- List **regions with above-average sales**

---

##  Key Insights

- Identified **top-performing regions and sales reps**
- Revealed **monthly and category-wise sales trends**
- Analyzed **customer behavior** by discount and payment method
- Highlighted **high-performing regions**

---

##  Tools Used

- SQL (Structured Query Language)
- Relational Database (assumed MySQL or PostgreSQL)

---

##  Conclusion

The analysis helped uncover performance metrics, customer behavior patterns, and strategic sales insights to guide decision-making and improve m
