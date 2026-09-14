# Vrinda Store – Annual Sales Report 2022

An Excel-based sales analysis of **Vrinda Store**, an Indian D2C/e-commerce apparel brand, covering FY2022 order data across multiple sales channels (Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, and others). The workbook contains raw transactional data, PivotTables, and dashboard-style summary sheets built from it.

## 📈 Dashboard Preview

![Vrinda Store Annual Report 2022 Dashboard](blob:https://claude.ai/bdec778f-116a-4eff-919a-86acbbc1ec7e)



## 📁 Repository Contents

| File | Description |
|---|---|
| `Vrinda_Store_Data_Analysis.xlsx` | Full workbook — raw order data, pivot tables, and summary sheets |
| `images/dashboard.png` | Screenshot of the consolidated dashboard (Report 2022 sheet) |

## 📊 Workbook Structure

The workbook is organized into the following sheets:

| Sheet | Contents |
|---|---|
| **Vrinda Store** | Raw order-level dataset (~31,000 rows) — the source data for all analysis |
| **Vrinda Store Report 2022** | Consolidated dashboard summarizing key metrics |
| **Sales vs Orders** | Monthly sales revenue and order volume (Jan–Dec) |
| **Order Status** | Breakdown of orders by status (Delivered, Cancelled, Returned, Refunded) |
| **Men vs Women** | Revenue split by customer gender |
| **Sales Top 5 States** | Top 5 Indian states by sales revenue |
| **Age and Gender** | Order distribution by age group (Teenager, Adult, Senior) and gender |
| **Channel** | Order share by sales channel |

## 🗂️ Raw Data Schema (`Vrinda Store` sheet)

Each row represents a single order line item, with the following fields:

| Column | Description |
|---|---|
| `index` | Row index |
| `Order ID` | Unique order identifier |
| `Cust ID` | Customer identifier |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Age Group` | Teenager / Adult / Senior |
| `Date` | Order date |
| `Month` | Order month |
| `Status` | Delivered / Cancelled / Returned / Refunded |
| `Channel` | Sales channel (Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others) |
| `SKU` | Stock keeping unit |
| `Category` | Product category (e.g., Kurta, Set) |
| `Size` | Product size |
| `Qty` | Quantity ordered |
| `currency` | Currency (INR) |
| `Amount` | Order amount |
| `ship-city` | Shipping city |
| `ship-state` | Shipping state |
| `ship-postal-code` | Shipping postal code |
| `ship-country` | Shipping country |
| `B2B` | Whether the order is B2B (boolean) |

## 🔑 Key Insights

- **Total orders analyzed:** ~31,000
- **Order status:** the vast majority of orders (~28.6K) were successfully **Delivered**, with smaller shares Cancelled, Returned, or Refunded
- **Gender split:** **Women** customers generated significantly higher revenue than Men (roughly 64% vs 36% of total sales)
- **Top states by sales:** Maharashtra, Karnataka, Uttar Pradesh, Telangana, and Tamil Nadu lead in revenue
- **Top channel:** **Amazon** is the largest sales channel by order volume, followed by Myntra and Flipkart
- **Seasonality:** sales peak in **March** and gradually decline through the second half of the year, dipping lowest in **November/December**
- **Customer demographics:** **Adults** account for the largest share of orders across both genders, followed by Teenagers and Seniors

## 🛠️ Tools Used

- Microsoft Excel
- PivotTables & PivotCharts for aggregation
- Dashboard-style summary sheet for reporting

## 🚀 How to Use

1. Clone or download this repository
2. Open `Vrinda_Store_Data_Analysis.xlsx` in Microsoft Excel (or a compatible spreadsheet tool)
3. Explore the **Vrinda Store Report 2022** sheet for the consolidated dashboard
4. Use the underlying **Vrinda Store** sheet to build your own pivot tables or import the data into other BI/analysis tools (Power BI, Tableau, Python/pandas, etc.)

## 📌 Notes

- All monetary values are in **INR (₹)**
- Data reflects orders placed during the **2022** calendar year
- This project is intended for portfolio/demonstration purposes in data analysis and dashboarding

## 📄 License

This project is shared for educational and portfolio purposes. Please check with the original data source before any commercial use.
