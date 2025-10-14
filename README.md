# Luxury Sales Data Analysis in Excel

## Project Objective
This project performs an **Exploratory Data Analysis (EDA)** on a fictional luxury sales dataset using **Microsoft Excel**.  
The goal is to uncover sales trends, identify top-performing regions, and understand customer purchasing behavior.

---

## Background
The dataset simulates transactions from a fictional luxury retail company selling products like watches, jewelry, leather goods, and accessories through multiple sales channels (Online, Boutique, and Partner Stores).  
All data is synthetic and anonymized — created for educational and portfolio purposes.

---

## Dataset Overview
- **Rows:** 5,000 synthetic transactions  
- **Columns:**  
  `order_id`, `order_date`, `customer_id`, `country`, `region`, `channel`,  
  `brand_code`, `product_category`, `product_code`, `unit_price`,  
  `quantity`, `discount`, `sales_amount`, `sales_rep`
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
The data was analyzed using **Pivot Tables** and **Charts** in Excel.  
Key analyses include:

- **Sales by Region and Channel**  
  Identify which regions and sales channels generate the highest revenue.
- **Top Products and Brands by Revenue**  
  Determine best-selling categories and brand performance.
- **Monthly Sales Trends**  
  Track seasonal fluctuations in total sales volume.
- **Average Discount by Channel**  
  Compare pricing and discounting strategies across sales channels.
- **Customer Order Frequency**  
  Identify loyal and repeat customers.

---

## Dashboard
An interactive Excel Dashboard was created to visualize the findings.  
It includes:

- Total Revenue and Average Order Value (KPIs)
- Sales by Region (Column Chart)
- Channel Share (Pie Chart)
- Monthly Trend (Line Chart)
- Top 10 Brands by Sales (Bar Chart)

### Example Layout
![Dashboard Preview](visuals/dashboard_preview.png)

*(If viewing on GitHub, open the `/analysis` folder to download and explore the Excel dashboard.)*

---

## Key Insights
- **Europe** generates the highest total revenue, primarily through **Boutique** sales.  
- **Online Channel** drives high order volume but lower average prices due to discounts.  
- **Peak sales** occur in **November and December**, showing strong holiday seasonality.  
- **Average Discount** across all transactions is approximately **12%**, higher online.  
- **Top-selling category:** Watches, followed by Jewelry.

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
│ └── dashboard_preview.png
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
