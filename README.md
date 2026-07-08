# 🎵 Chinook Music Store Sales & Business Intelligence Pipeline

An end-to-end business intelligence and data modeling project focused on transforming raw music store database transactions into interactive, executive-ready insights. This project simulates a real-world E-commerce music platform, analyzing global revenue trends, customer purchasing behavior, and employee performance.

---

## 📊 Dashboard & Data Model Preview
*A visual walkthrough of the dynamic 4-page report and its underlying architecture:*

### 📐 Optimized Star Schema Data Model
![Chinook Data Model](Chinook%20Modiling.png)

### 📈 Interactive Executive Pages
| Page 1: Sales Overview | Page 2: Customer Insights |
|---|---|
| ![Overview](Sales%20Overview.png) | ![Customer Insights](Customer%20Insights.png) |

| Page 3: Music Performance | Page 4: Employee Analysis |
|---|---|
| ![Music Performance](Music%20Performance.png) | ![Employee Analysis](Employee%20Analysis.png) |

---

## 🛠️ Tech Stack & Key Features
* **Data Warehousing & Modeling:** SQL & Power Query, Star Schema Architecture (Fact & Dimension Tables).
* **Business Intelligence Tool:** Power BI 📊
* **Advanced Querying:** Custom analytical scripts integrated via Advanced Editor.
* **Dashboard Structure:** Dynamic 4-page executive report.

---

## 📐 Data Modeling (Star Schema)
To ensure optimal reporting performance and efficient cross-tabulation analytics, the relational database was restructured from a transactional format into a clean Star Schema:
* **Fact Table:** `FactInvoiceLine` capturing detailed sales metrics (Total Revenue, Tracks Sold, Average Invoice Value).
* **Dimension Tables:** `Track` (genres, artists, prices), `Customer` (demographics), `Date` (timelines), and `Employee` (support reps).
---

## 📊 Dashboard Pages & Deep-Dive Sections
The final interactive report is divided into four specialized pages to give management a 360-degree view of the business:
1. **Overview:** High-level summary of total sales, key performance indicators (KPIs), and historical revenue trends.
2. **Customer Insights:** Geographic distribution analysis and profiling of top-spending customer segments.
3. **Music Performance:** Deep-dive into track-level performance, discovering that core genres like **Rock** and **Metal** heavily dominate overall store sales.
4. **Employee Analysis:** Evaluation of sales support staff contributions and customer management efficiency.

---

## 📂 Repository Contents
* 📊 `shinook project.pbix` - The core Power BI dashboard file with the complete data model.
* 📄 `chinook presentation.pdf` - High-fidelity project presentation and business breakdown.
* 📜 `Query Example put in Advanced editor` - Advanced query scripts used during the ETL and data preparation phase.
* 📝 `README.md` - Project documentation.

