# **Coffee Shop Sales Analysis Dashboard**

[![Tableau Public](https://img.shields.io/badge/Tableau-Public-blue?logo=tableau)](https://public.tableau.com/views/STUDYCASEREVOU_17649675015860/Dashboard1)
[![Domain](https://img.shields.io/badge/Domain-Retail%20&%20F%26B%20Analytics-orange)](#)
[![Role](https://img.shields.io/badge/Role-Business%20Analyst-green)](#)


_**Business Overview & Problem Statement**_

Retail coffee shop management frequently struggles with limited visibility into multi-branch transaction patterns, hourly customer traffic surges, and regional performance trends. Without clear operational and sales insights, stores often face:
* Inefficient shift scheduling and staffing during non-peak vs. peak hours.
* Untargeted promotional strategies that fail to maximize top-line revenue.
* Lack of inventory optimization across top-selling product categories.


_**Live Interactive Dashboard**_

<p align= "center">
<img width="800" height="409" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/a8381354-c96f-41d6-9bd6-d886500d9354" width="800">
</p>

_**Data Architecture & Tools Used**_

* **Dashboarding & Data Visualization:** Tableau Public
* **Data Processing:** Data Cleaning & Transformation via Structured Tabular Dataset
* **Core Analytics Focus:** Sales Performance, Peak-Hour Transaction Trends, Top 5 Best-Selling Products, Category-Wise Revenue Distribution


_**Key Business Insights**_

1. **Peak Transaction Hours:** 
   * Transaction surges concentrate heavily during specific morning and afternoon windows, highlighting exact windows requiring maximum customer-facing staff.
2. **Product Category Performance:** 
   * A core group of top-selling products drives the majority of daily revenue, confirming the importance of prioritized inventory restocking.
3. **Branch & Regional Trends:** 
   * Revenue distribution across branches reveals distinct purchasing volumes, allowing leadership to tailor localized promotional campaigns.


_**Strategic Business Recommendations**_

* **Operational Shift Reallocation:** Adjust barista and floor-staff scheduling based on peak-hour transaction patterns to reduce customer wait times and improve service throughput.
* **Targeted Time-Based Promotions:** Introduce bundle promotions during lower-traffic hours to balance customer flow and boost off-peak revenue.
* **Inventory & Stock Optimization:** Ensure 100% stock availability for top-selling product categories to prevent stockouts and protect top-line growth.


_**Project Structure**_

```text
├── data/
│   └── Coffee Shop Sales Dataset.xlsx    # Raw sales dataset (Excel)
├── dashboards/
│   └── coffee_shop_dashboard.twbx        # Tableau Packaged Workbook file
├── dashboard_preview.gif                 # Preview of Dashboard 
├── .gitignore                            # Excludes temporary & system files
├── LICENSE                               # MIT License
└── README.md                             # Project documentation
