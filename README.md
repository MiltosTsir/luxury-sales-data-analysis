# Luxury Sales Data Analysis in Excel

## Project Objective
This project performs an **Exploratory Data Analysis (EDA)** on a fictional luxury sales dataset using **Microsoft Excel**.  
The goal is to uncover sales trends, identify top-performing regions, and understand customer purchasing behavior.

This analysis helps luxury retailers understand how sales channels and regional demand impact overall performance, supporting **data-driven marketing and inventory planning decisions**.

---

## Background
The dataset simulates transactions from a fictional luxury retail company selling products like watches, jewelry, leather goods, and accessories through multiple sales channels (Online, Boutique, and Partner Stores).  
All data is synthetic and anonymized — created for educational and portfolio purposes.

---

## Dataset Overview
- **Rows:** 5,000 synthetic transactions  
- **Columns:**  

| Original Field | New Field | Notes |
|----------------|------------|--------|
| `product_category` | `luxury_category` | Renamed and simplified |
| `order_date` | `Order Date` | Improved readability |
| `sales_amount` | `Revenue` | Clear financial terminology |
| `discount` | `Discount %` | Clarified measurement |
| `unit_price` | `Unit Price (€)` | Added currency symbol |
| `channel` | (values updated) | “Boutique” → “Store” |

- Data generated synthetically to simulate real-world luxury retail operations.

---

## Data Cleaning and Preparation
Data cleaning was performed directly in Excel to ensure accuracy before analysis.  
The following checks and transformations were applied:

1. **Duplicate Check:**  
   Used conditional formatting and COUNTIF to identify duplicate `order_id` values.  
2. **Missing Values:**  
   Verified completeness using Excel formulas to flag empty or invalid fields.  
3. **Sales Calculation Validation:**  
   Confirmed that `sales_amount = unit_price * quantity * (1 - discount)`.  
4. **Outlier Detection:**  
   Flagged `unit_price` values greater than 10,000 as potential outliers.  
5. **Data Consistency:**  
   Checked for valid region-country combinations (e.g., “France” → “Europe”).

---

## Analysis and Dashboard
The data was analyzed using **Pivot Tables**, **Slicers**, and **Charts** in Excel.  
Key analyses include:

- **Sales by Region and Channel** — Identify which regions and sales channels generate the highest revenue.  
- **Top Products and Brands by Revenue** — Determine best-selling categories and brand performance.  
- **Monthly Sales Trends** — Track seasonal fluctuations in total sales volume.  
- **Average Discount by Channel** — Compare pricing and discounting strategies across sales channels.  
- **Customer Order Frequency** — Identify loyal and repeat customers.

---

## Dashboard
An interactive Excel Dashboard was created to visualize the findings.  
It includes:

- **KPIs Displayed:**  
  - Total Revenue (€)  
  - Average Order Value (€)  
  - Total Orders  
  - Average Discount (%)  

- **Visual Components:**  
  - Sales by Region (Column Chart)  
  - Channel Share (Pie Chart)  
  - Monthly Trend (Line Chart)  
  - Top 10 Brands by Sales (Bar Chart)

### Dashboard Preview
![Dashboard Preview](visuals/dashboard_preview.png)



---

## Key Insights
- **Europe** generates the highest total revenue, primarily through **Boutique** sales.  
- **Online Channel** drives high order volume but lower average prices due to discounts.  
- **Peak sales** occur in **November and December**, showing strong holiday seasonality.  
- **Average Discount** across all transactions is approximately **12%**, higher online.  
- **Top-selling category:** Watches, followed by Jewelry.

---

## Additional Visuals

| Visualization | Description |
|----------------|-------------|
| ![Top Brands](visuals/top_brands_chart.png) | Top 10 brands by total revenue |
| ![Regional Sales](visuals/regional_sales.png) | Revenue distribution by region |
| ![Monthly Trend](visuals/monthly_trend.png) | Monthly revenue trend 2020–2024 |

---

## Tools Used
- **Microsoft Excel** — Data Cleaning, Pivot Tables, Charts, and Dashboard  
- **GitHub** — Version control and project documentation  


---

## Repository Structure
luxury-sales-data-analysis/
│
├── data/
│ └── luxury_sales_data.xlsx
│
├── analysis/
│ └── luxury_sales_dashboard.xlsx
│
├── visuals/
│ ├── dashboard_preview.png
│ ├── top_brands_chart.png
│ ├── regional_sales.png
│ └── monthly_trend.png
│
└── README.md


---

## Learning Outcomes
This project demonstrates the full lifecycle of a **data analysis process** using Excel:
- Data cleaning and validation  
- Exploratory data analysis  
- KPI creation and dashboard visualization  
- Business storytelling and insights presentation  

---

## About this Project
This project is part of my **Data Analysis Portfolio**.  
It focuses on using **Excel** as a complete tool for end-to-end data analysis — from raw data cleaning to storytelling with dashboards.
