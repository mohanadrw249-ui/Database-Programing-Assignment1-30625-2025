# Database-Programing-Assignment1-30625-2025
📌 Project Overview
This project demonstrates the design and implementation of a relational database system using SQL.
It focuses on applying Common Table Expressions (CTEs) and Window Functions to perform advanced data analysis.
The system models a simple Store Management System including customers, products, and orders.
🗄️ Database Schema
The database contains 3 related tables:
1. Customers
CustomerID (PK)
CustomerName
Phone
City
2. Products
ProductID (PK)
ProductName
Price
Stock
3. Orders
OrderID (PK)
CustomerID (FK)
ProductID (FK)
Quantity
OrderDate
🔗 Relationships
One Customer → Many Orders
One Product → Many Orders
🧠 CTE Implementations
✔ Simple CTE
Used to join customers, orders, and products.
✔ Multiple CTEs
Used to calculate:
Total quantity per customer
Total sales per product
✔ Recursive CTE
Generated a sequence of numbers (1–10).
✔ Aggregation CTE
Calculated total quantity per customer.
✔ CTE with JOIN
Combined multiple tables to show detailed order information.
📊 Window Function Implementations
🔢 Ranking Functions
ROW_NUMBER()
RANK()
DENSE_RANK()
PERCENT_RANK()
📈 Aggregate Window Functions
SUM() OVER()
AVG() OVER()
MIN() OVER()
MAX() OVER()
🔄 Navigation Functions
LAG()
LEAD()
📊 Distribution Functions
NTILE()
CUME_DIST()
📌 Key Findings
Window functions help analyze data without grouping rows.
CTEs simplify complex SQL queries and improve readability.
The system provides insights into customer purchasing behavior and product performance.
📷 Screenshots
All query outputs and results are included in the repository under the /screenshots folder.
⚖️ Academic Integrity
This work is original and created for academic purposes only, following university guidelines.
🚀 How to Run
Run the SQL script in MySQL / Oracle / DBMS tool.
Execute tables creation first.
Insert sample data.
Run CTE and Window Function queries.
📎 Conclusion
This project demonstrates practical skills in advanced SQL programming using CTEs and Window Functions for real-world data analysis.
