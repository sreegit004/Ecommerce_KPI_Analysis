STARBUCKS E-COMMERCE KPI ANALYSIS 📊

---

```markdown
# Starbucks KPI & Customer Behavior Analysis ☕

[![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![Database](https://img.shields.io/badge/Database-Relational-blue?style=for-the-badge)](https://en.wikipedia.org/wiki/Relational_database)

## 📌 Executive Summary
This project delivers a comprehensive, end-to-end analytics solution using **SQL Server** to evaluate Starbucks transactional data. By writing optimized relational queries, this analysis transforms raw transactional rows into strategic business intelligence across revenue performance, customer loyalty behavior, product mix, and operational efficiency. 

The core objective is to translate complex data into actionable operational insights—such as optimizing store labor hours during peak periods and maximizing the ROI of loyalty reward programs.

---

## 🛠️ Tech Stack & SQL Techniques Used
* **Environment:** SQL Server Management Studio (SSMS)
* **Visualization Support:** Power BI / Microsoft Excel
* **Advanced SQL Techniques Demonstrated:**
    * **Aggregation & Analytics:** `SUM()`, `COUNT(DISTINCT)`, `AVG()`
    * **Conditional Logic:** `CASE WHEN` for behavioral segmentation
    * **Time-Series Analytics:** `DATEPART()`, `DATENAME()`, `CAST()` for granular temporal trends
    * **Modularity:** Common Table Expressions (CTEs) for highly readable, maintainable queries
    * **Advanced Analytics:** Window Functions (`ROW_NUMBER()`, `RANK()`, Over clauses)
    * **Dataset Merging:** `UNION ALL` for unifying structural metrics

---

## 📐 Data Architecture & Schema
The analysis is executed against the `Starbucks_Comprehensive_Data` table inside the `Starbucks_DB` database. The core schema evaluates the following critical structural entities:

| Field Category | Column Names |
| :--- | :--- |
| **Transaction Metadata** | `TransactionID`, `TransactionDate` |
| **Customer Profile** | `CustomerID`, `LoyaltyStatus` |
| **Product Hierarchy** | `ProductID`, `ProductCategory`, `ProductSubCategory`, `UnitPrice` |
| **Sales Metrics** | `Quantity`, `TotalLineItemPrice` |
| **Geography & Operations**| `StoreRegion`, `StoreLocation`, `OrderType`, `PaymentMethod` |
| **Marketing / Loyalty** | `IsRewardRedeemed` |

---

## 🎯 Strategic Business Objectives & KPI Framework

### 1. High-Level Core Business KPIs
The script establishes a reliable baseline of operational health by measuring:
* **Total Revenue:** Gross sales yield across all regions.
* **Average Order Value (AOV):** Total Revenue divided by Total Orders to evaluate ticket sizes.
* **Total Items Sold & Total Orders Count:** Absolute volume tracking.
* **Average Items Per Order (AIPO):** Cross-selling efficiency score.

### 2. Analytical Deep-Dives & Problem Statements
* **Temporal Demand & Busiest Hour Analysis:** Pinpointing exact peak hours, days of the week, and day-parts to optimize store staffing and supply chain allocations.
* **Product Mix & Contribution Margin:** Evaluating the exact volume share contribution percentage per product and tracking `ProductCategory` popularity.
* **Loyalty & Reward Optimization:** Quantifying regular vs. loyalty member mix and measuring the redemption velocity of promotions (`IsRewardRedeemed`).
* **Operational Footprint & Channel Dynamics:** Dissecting performance across geographical `StoreRegion` hubs, `OrderType` (In-Store, Drive-Thru, Mobile), and `PaymentMethod` preferences.

---

## 📂 Project Structure
```text
Starbucks-KPI-Analysis/
├── README.md                               # Professional project documentation
├── sql/
│   └── starbucks_kpi_analysis.sql          # Fully documented, production-ready SQL script
├── dashboard/
│   └── starbucks_analytics_dashboard.pbix  # Power BI / Excel visualization dashboards
└── assets/
    └── screenshots/                        # Dashboard and query execution UI captures

```

---

## 🚀 How to Run and Validate This Project

### Prerequisites

* SQL Server 2022+ or Azure SQL Database.
* SQL Server Management Studio (SSMS) or Azure Data Studio.

### Step-by-Step Deployment

1. **Clone the Repository:**
```bash
git clone [https://github.com/your-username/Starbucks-KPI-Analysis.git](https://github.com/your-username/Starbucks-KPI-Analysis.git)

```


2. **Database Setup:** Load your database instance and ensure the source dataset is designated as `Starbucks_DB`.
3. **Execute the Analytical Engine:** Open and execute `sql/starbucks_kpi_analysis.sql`.
4. **Dashboard Integration:** (Optional) Map the SQL view outputs or query results directly into Power BI to populate the visual reporting layer.

---

## 💡 Business Value & Key Interview Takeaways

> **For Recruiters:** This project demonstrates advanced data fluency, writing clean, execution-optimized SQL instead of basic scripts. It highlights the ability to frame raw technical queries around core corporate objectives: revenue optimization, customer retention, and resource management.

* **Operational Efficiency:** Identifying peak ordering times allows management to strategically scale staff, preventing bottleneck delays.
* **Marketing ROI:** Isolating loyalty behavior versus reward redemption rates directly informs marketing teams whether current incentives are effectively driving recurring transactions.
* **Inventory Optimization:** Identifying top-performing categories and sub-categories ensures high-demand items maintain optimal stock safety levels.

---

📫 **Connect with Me:** 
LinkedIn: https://www.linkedin.com/in/sreechakraborty/ | Mail: sree.onlyofficials.009@gmail.com

```
