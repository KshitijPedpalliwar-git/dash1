# 🏪 Super Store Power BI Dashboard

## 📊 Overview
The **Super Store Dashboard** is a Power BI project that visualizes sales, profit, and customer insights using the Superstore dataset.  
It helps analyze key business metrics across regions, categories, and time periods to support data-driven decisions.

---

## 🎯 Objectives
- Track **Sales**, **Profit**, and **Quantity** across different product categories.
- Identify **top-performing regions, customers, and products**.
- Monitor **Profit Margin**, **Discount Impact**, and **Order Trends**.
- Provide an interactive and visual summary for business performance.

---

## ⚙️ Tools & Technologies
- **Power BI Desktop (.pbix)**
- **Excel / CSV Dataset** (Superstore)
- **Power Query** (for data transformation)
- **DAX** (for measures and calculated fields)

---

## 📈 Key Metrics (KPIs)
| KPI | Description | Formula Example |
|------|--------------|----------------|
| **Total Sales** | Total revenue generated from orders | `SUM(Sales)` |
| **Total Profit** | Overall profit after discounts | `SUM(Profit)` |
| **Profit Margin %** | Profitability ratio | `SUM(Profit) / SUM(Sales)` |
| **Total Orders** | Total number of transactions | `COUNTROWS(Orders)` |
| **Average Discount** | Average discount percentage applied | `AVERAGE(Discount)` |
| **Sales by Region** | Sales performance by region | Grouped by `Region` |
| **Sales Growth %** | Month-over-month sales growth | `(Current - Previous) / Previous` |

---

## 🗂️ Data Model
**Tables Used:**
- Orders
- Customers
- Products
- Regions
- Categories

**Relationships:**
- `CustomerID` → Customer Table  
- `ProductID` → Product Table  
- `Region` → Geography Table  

---

## 📊 Dashboard Features
- 📅 **Time Intelligence** – Compare sales over years/months.
- 🌍 **Regional Analysis** – Breakdown by region and state.
- 🛍️ **Category Insights** – Track top and bottom product categories.
- 💹 **Profitability Overview** – Visualize high and low-profit areas.
- 👥 **Customer Insights** – Identify top customers and order frequency.
- 🧮 **Dynamic Filters & Slicers** – Interact by region, category, or date.

---

## 🧮 Data Cleaning & Transformation
Performed in **Power Query Editor**:
- Removed nulls and duplicates.
- Filled down missing fields.
- Standardized date formats.
- Created calculated columns for sales, profit, and margin.

---

## 📸 Dashboard Preview
  
Example:
<img width="1290" height="726" alt="image" src="https://github.com/user-attachments/assets/a7d3218a-41d7-4eb1-a21e-5fc1bccf4b4c" />

