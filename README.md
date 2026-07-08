# 🎵 Chinook Music Store Sales & Business Intelligence Pipeline

An end-to-end business intelligence and data modeling project focused on transforming raw music store database transactions into interactive, executive-ready insights. This project simulates a real-world E-commerce music platform, analyzing global revenue trends, customer purchasing behavior, and employee performance.

---

## 📊 Dashboard & Data Model Preview
*A visual walkthrough of the dynamic 4-page report and its underlying architecture:*

### 📐 Optimized Star Schema Data Model
![Chinook Data Model](modeling.png)

### 📈 Interactive Executive Pages
| Page 1: Sales Overview | Page 2: Customer Insights |
|---|---|
| ![Overview](dashboard_1.png) | ![Customer Insights](dashboard_2.png) |

| Page 3: Music Performance | Page 4: Employee Analysis |
|---|---|
| ![Music Performance](dashboard_3.png) | ![Employee Analysis](dashboard_4.png) |

---

## 🛠️ Tech Stack & Key Features
* **Data Warehousing & Modeling:** SQL & Power Query, Star Schema Architecture (Fact & Dimension Tables).
* **Business Intelligence Tool:** Power BI 📊
* **Advanced Querying:** Custom analytical scripts integrated via Advanced Editor.
* **Dashboard Structure:** Dynamic 4-page executive report.

---

## 📐 Data Modeling (Star Schema)
To ensure optimal reporting performance and efficient cross-tabulation analytics, the relational database was restructured from a transactional format into a clean Star Schema[cite: 1]:
* **Fact Table:** `FactInvoiceLine` capturing detailed sales metrics (Total Revenue, Tracks Sold, Average Invoice Value)[cite: 1].
* **Dimension Tables:** `Track` (genres, artists, prices), `Customer` (demographics), `Date` (timelines), and `Employee` (support reps).
---

## 📊 Dashboard Pages & Deep-Dive Sections
The final interactive report is divided into four specialized pages to give management a 360-degree view of the business[cite: 1]:
1. **Overview:** High-level summary of total sales, key performance indicators (KPIs), and historical revenue trends[cite: 1].
2. **Customer Insights:** Geographic distribution analysis and profiling of top-spending customer segments[cite: 1].
3. **Music Performance:** Deep-dive into track-level performance, discovering that core genres like **Rock** and **Metal** heavily dominate overall store sales.
4. **Employee Analysis:** Evaluation of sales support staff contributions and customer management efficiency[cite: 1].

---

## 📂 Repository Contents
* 📊 `shinook project.pbix` - The core Power BI dashboard file with the complete data model.
* 📄 `chinook presentation.pdf` - High-fidelity project presentation and business breakdown[cite: 1].
* 📜 `Query Example put in Advanced editor` - Advanced query scripts used during the ETL and data preparation phase.
* 📝 `README.md` - Project documentation.

---
*Generated as part of my Advanced Data Analytics portfolio.*
