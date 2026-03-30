# 🛒 E-Commerce Sales Dashboard — Power BI

![Dashboard Preview](dashboard-preview.png)
(dashboard-preview.png)



---

## 📌 Project Overview

An interactive **E-Commerce Sales Dashboard** built in Power BI Desktop to analyze business performance across sales, profit, customers, products, and geography. The dashboard uses **slicers for dynamic filtering** by Quarter and State, allowing users to drill into specific time periods and regions.

---

## 📊 Dashboard Visuals

| Visual | Type | Description |
|--------|------|-------------|
| Sum of Amount | KPI Card | Total sales revenue generated |
| Sum of Profit | KPI Card | Total net profit earned |
| Sum of Quantity | KPI Card | Total units sold |
| Sum of AOV | KPI Card | Average Order Value per transaction |
| Sum of Amount by State | Bar Chart | Revenue comparison across states |
| Sum of Quantity by Category | Donut Chart | Units sold split by product category (Clothing 62%, Electronics 21%, Furniture 17%) |
| Sum of Profit by Month | Column Chart | Month-wise profit trend |
| Sum of Amount by CustomerName | Column Chart | Top customers by sales amount |
| Sum of Quantity by PaymentMode | Donut Chart | Orders split by payment method (COD, UPI, EMI, Debit, Credit) |
| Sum of Profit by Sub-Category | Bar Chart | Profitability by product sub-category |
| Quarter Slicer | Slicer | Filter all visuals by Q1 / Q2 / Q3 / Q4 |
| State Slicer | Slicer | Filter all visuals by State |

---

## 🔢 Key Metrics (Full Data)

| Metric | Value |
|--------|-------|
| 💰 Total Sales Amount | 139K |
| 📈 Total Profit | 18K |
| 📦 Total Quantity Sold | 1,783 |
| 🎯 Average Order Value (AOV) | 37K |

---

## 🗂️ Data Model

Two tables are used in this project:

**Orders Table**
- Order ID
- Customer Name
- State
- City
- Order Date

**Details Table**
- Order ID
- Category
- Sub-Category
- Amount
- Profit
- Quantity
- Payment Mode

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard creation & data modeling
- **Microsoft Excel** — Source data (Orders.xlsx, Details.xlsx)
- **DAX** — Measures for Amount, Profit, Quantity, AOV
- **Custom Background Theme** — Dark themed UI

---

## 🚀 How to Open This Project

1. Download and install **Power BI Desktop** (free) from [Microsoft Store](https://powerbi.microsoft.com/desktop)
2. Clone or download this repository
3. Open `ecommerce-sales-dashboard-powerbi.pbix` in Power BI Desktop
4. Use the **Quarter** buttons and **State** dropdown to filter the dashboard interactively

---

## 📁 Repository Structure

```
📁 ecommerce-sales-dashboard-powerbi/
│
├── 📊 ecommerce-sales-dashboard-powerbi.pbix   # Main Power BI file
├── 📁 data/
│   ├── 📗 Orders.xlsx                           # Orders source data
│   └── 📗 Details.xlsx                          # Product details source data
├── 🖼️ dashboard-preview.png                    # Dashboard screenshot
└── 📄 README.md                                # Project documentation
```

---

## 👤 Author

**Ahmed**
- 📧 ahmedmirza119@gmail.com

---

## ⭐ If you found this project helpful, please give it a star!
