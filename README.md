# Vishal Retail Store Sales Performance Analysis using Power BI

## Objective
Create an interactive dashboard that shows sales performance by category, city, and month, along with written insights for business stakeholders.

## Tools Used
- Microsoft Excel (data cleaning and transformation)
- Power BI Desktop (data modeling, analysis, and dashboard design)

## Dataset
The dataset consists of three related tables:

**Customers**
- age, city, customer_id, gender, loyalty_member, signup_date

**Orders**
- order_id, customer_id, product_id, order_date, Months, quantity, price, payment_method, Sales
- Measures: Avg Order Value, Total Orders, Total Sales

**Products**
- product_id, product_name, category, price

## What I Did
1. Cleaned and transformed the raw dataset in Excel (checked for inconsistencies, formatted columns, and prepared it for analysis).
2. Imported the cleaned Customers, Orders, and Products tables into Power BI Desktop and built relationships between them using customer_id and product_id.
3. Extracted Months from order_date for time-based trend analysis.
4. Created calculated measures: Avg Order Value, Total Orders, and Total Sales.
5. Built a multi-page Power BI report with three sections:
   - **Client Brief** — project overview/context page
   - **Sales Dashboard** — the main interactive dashboard
   - **Insights** — written summary of key findings
6. Designed the dashboard with:
   - KPI cards: Total Sales, Avg Order Value, Total Orders
   - Line chart: Revenue by Month
   - Bar chart: Top 5 Categories by Sales
   - Bar chart: Top 5 Cities by Revenue
   - Donut charts: Sales by Loyalty Member, Sales by Gender, Sales by Payment Method
   - Slicers: City, Months, Category
7. Applied a consistent color theme and icons for a clean, business-friendly look.
8. Wrote 4 key insights based on the dashboard's findings.

## Key Insights
1. Home was the top-performing category with 473K in sales, nearly double Electronics (208.47K).
2. Revenue dropped sharply from January (236K) to November (80K) a steady month-over-month decline worth investigating.
3. Sheffield led all cities in revenue at 233.61K, closely followed by Birmingham at 224.89K.
4. Loyalty program members drove 51.54% of total sales (847.8K), showing the program's positive impact on repeat purchases.

## Files in this Repo
- `Vishal_Retail_Store_Sales_Dataset.xlsx` — the cleaned dataset (Customers, Orders, Products)
- `Vishal_Retail_Store_Sales_Performance_Analysis...` — the Power BI (.pbix) file with the full report
- `Client_Brief.png` — screenshot of the client brief page
- `Performance_DA_Dashboard_SS.png` — screenshot of the main sales dashboard
- `Performance_Analysis_Insights.png` — screenshot of the insights page
