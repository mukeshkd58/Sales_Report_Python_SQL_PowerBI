📊 Sales Report – Power BI Dashboard
📌 Project Overview

This project is a professional-grade Power BI Sales Report dashboard designed to transform raw transactional sales data into actionable business intelligence. The dashboard provides a 360-degree view of sales performance, helping stakeholders monitor KPIs, analyze trends, and identify growth opportunities using data-driven insights.

🎯 Objectives

Convert raw sales data into meaningful insights

Monitor key sales KPIs in real time

Identify sales trends, patterns, and growth opportunities

Support strategic and operational decision-making

Present insights in a clean, interactive, and user-friendly dashboard

🧩 Key Features

📈 Sales Performance Analysis (Total Sales, Revenue Trends)

🏷️ Product-wise & Category-wise Analysis

🌍 Region / Location-based Sales Insights

📅 Time Intelligence (Daily, Monthly, Yearly trends)

🎯 KPIs & Metrics Cards

🔍 Interactive Filters & Slicers

⚡ Optimized data model for fast performance

🛠️ Tools & Technologies Used

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (ETL)

CSV / Excel Sales Dataset

📂 Project Structure
Sales-Report-PowerBI/
│
├── Sales Report.pbix        # Main Power BI dashboard file
├── dataset/                # Raw sales data (CSV / Excel)
├── images/                 # Dashboard screenshots
└── README.md               # Project documentation
📥 Dataset Description

The dataset contains transactional sales records with fields such as:

Order ID

Order Date

Product Name

Category

Sales Amount

Quantity Sold

Profit

Region / City / Country

Note: Dataset can be replaced with any similar sales dataset.

🔄 Data Preparation (ETL Process)

Performed using Power Query:

Removed null and duplicate values

Standardized column names

Converted data types (Date, Currency, Numbers)

Created calculated columns where required

Loaded clean data into Power BI model

📐 Data Modeling

Star schema design

Fact table: Sales

Dimension tables: Date, Product, Region

Relationships created using primary & foreign keys

Proper cardinality and cross-filter direction applied

🧮 DAX Measures (Examples)
Total Sales = SUM(Sales[Sales Amount])


Total Profit = SUM(Sales[Profit])


Profit Margin = DIVIDE([Total Profit], [Total Sales])


Sales YoY Growth =
CALCULATE(
    [Total Sales] - SAMEPERIODLASTYEAR([Total Sales]),
    SAMEPERIODLASTYEAR('Date'[Date])
)
📊 Dashboard Pages
1️⃣ Sales Overview

Total Sales

Total Profit

Sales Trend Line

KPI Cards

2️⃣ Product Analysis

Top-selling products

Category-wise sales

Product performance comparison

3️⃣ Regional Analysis

Sales by region

Geographic performance

Region-wise contribution

4️⃣ Time Analysis

Monthly & yearly trends

Seasonal patterns

Growth comparison

🎛️ Interactivity

Slicers for Date, Region, Product, Category

Cross-filtering between visuals

Drill-down & drill-through features

📸 Screenshots

Add dashboard screenshots in the /images folder and link them here.

🚀 How to Use This Project

Clone the repository

git clone https://github.com/mukeshkd58/Sales_Report_Python_SQL_PowerBI

Open Sales Report.pbix in Power BI Desktop

Load or replace dataset if required

Refresh the data

Explore the dashboard interactively

📌 Use Cases

Business sales monitoring

Management reporting

Portfolio project for Data Analysts

Power BI practice & learning

🧠 Learning Outcomes

Power BI dashboard design

Data modeling best practices

Writing optimized DAX measures

Business storytelling with data

🤝 Contribution

Contributions are welcome!

Fork the repository

Create a feature branch

Commit your changes

Open a pull request

📬 Contact

Author: Mukesh Kumar
Skills: Power BI | Data Analysis | Data Visualization

⭐ If you like this project

Give it a ⭐ on GitHub to support and motivate further work!