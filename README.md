Sales Management Project using Power BI and SQL
📌 About This Project
This is a personal project I completed to practice real-world data analysis and dashboard creation skills using SQL and Power BI.
The goal was to design an executive sales report for sales managers and sales representatives, based on business needs and user stories.

Through this project, I aimed to simulate working on a professional business request and gain deeper hands-on experience in data cleaning, transformation, modeling, and visualization.

🎯 Business Request and User Stories
The business asked for an interactive sales overview dashboard to track sales performance .
Based on their request, I created user stories to guide the project:


No.	As a (Role)	I want (Request)	So that I (User Value)	Acceptance Criteria
1	Sales Manager	A dashboard overview of sales in 2020 and 2021	Easily track top-performing customers and products	A Power BI dashboard showing top 10 products and customers with filters
2	Sales Manager	A dashboard comparing sales vs. budget	Monitor performance against targets	A Power BI graph comparing sales and budget
3	Sales Representative	A detailed overview of sales per customer	Focus on customers with the highest sales potential	A Power BI page with customer-level filtering
4	Sales Representative	A detailed overview of sales per product	Focus on top-selling products	A Power BI page with product-level filtering

🛠️ Data Cleansing & Transformation (SQL)
To build the required data model, I performed data extraction and transformation using SQL.

The following tables were prepared:
DIM_Calendar.sql
DIM_Customers.sql
DIM_Product.sql
FACT_InternetSales.sql
Additionally, a budget dataset (FACT_SentSalesBudget.xlsx) was provided and connected during the modeling phase.

All SQL scripts are available in the SQL_Queries folder.

🧩 Data Model
After cleaning and preparing the data, I created a relational model inside Power BI.

The model connects:
Sales and Budget Fact tables
Customer, Product, and Calendar Dimension tables
This model helped achieve correct data relationships for analysis.
(Screenshot available in the repository)

📊 Final Dashboard Overview
The completed dashboard includes:

A Summary Page for overall sales and budget tracking
A Customer Details Page for customer-wise sales analysis
A Product Details Page for product-wise sales insights

The full Power BI report is available as Sales_Report_Final.pbix.
(Requires Power BI Desktop to open.)

Below are some screenshots name from the final report:
Sales_Overview_Screenshot.png
Customer_Details_Screenshot.png
Product_Details_Screenshot.png

🙏 Thank You!
Thank you for taking the time to explore my project!
I truly enjoyed working on this and improving my Power BI and SQL skills.

