 Algonive_Project_Data_Analyst_Task2
 
📌 Project Overview
This project analyzes Blinkit (India’s Last Minute App) sales dataset using Power BI.
The dashboard provides insights into sales, items, ratings, outlet performance, and customer preferences based on multiple dimensions such as Outlet Size, Outlet Location, Item Type, and Outlet Type.

The goal of this project was to:

Perform data cleaning & transformation in Power BI.
Create KPIs using DAX formulas.
Build an interactive dashboard with filters and drilldowns.

📂 Dataset
The dataset contains transactional details of items sold at different Blinkit outlets.
Sample Columns:
Item Fat Content – Regular / Low Fat
Item Identifier – Unique product code
Item Type – Fruits, Vegetables, Canned, Frozen Foods, Household, etc.
Outlet Establishment Year – Year when outlet was established
Outlet Identifier – Unique store code
Outlet Location Type – Tier 1 / Tier 2 / Tier 3
Outlet Size – Small / Medium / High
Outlet Type – Supermarket / Grocery Store
Item Visibility – Share of visibility in the outlet
Item Weight – Product weight
Sales – Total sales value
Rating – Customer rating (out of 5)

🔄 Data Transformation
Performed in Power Query Editor:
Cleaned inconsistent values (e.g., "low fat" → "Low Fat").
Removed null/missing values.
Changed data types (numeric, categorical, date).
Created calculated columns for better categorization.

📊 KPIs (using DAX)
Total Items = COUNTROWS(ItemsTable)
Total Sales = SUM(ItemsTable[Sales])
Average Sales = DIVIDE([Total Sales], [Total Items])
Average Rating = AVERAGE(ItemsTable[Rating])

📈 Dashboard Features
KPIs:
Total Items → 8,523
Total Sales → $1.20M
Average Sales → $140.99
Average Rating → 3.97

Visuals:
Sales by Outlet Establishment Year (Line Chart)
Item Type vs. Sales (Bar Chart)
Outlet Size distribution (Donut Chart)
Sales by Outlet Location (Bar Chart)
Outlet Type Performance (Matrix Table with KPIs)
Fat Content impact on sales (Pie Chart & Bar Chart)

Filters (Slicers):
Outlet Location
Outlet Size
Item Type

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ef405a95-cad3-4324-97a5-13c6df6dc7a7"
