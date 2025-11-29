# EV-Revolution-Analysis
# ⚡EV Market Evolution: Year-over-Year Analysis

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Completed-success?style=for-the-badge)

## 📌 Project Overview
This interactive dashboard visualizes the adoption trends of Electric Vehicles (EVs) in Washington State from **2000 to 2025**. The goal of this analysis was to identify market leaders, growth patterns, and the shift between battery technologies (BEV vs. PHEV).

![Dashboard Preview](images/dashboard_screenshot.png)
*(Note: View the full interactive dashboard in the `dashboard/` folder)*

## 🔍 Key Insights & Statistics
- **Total Fleet Size:** 250,659 Vehicles
- **Adoption Surge:** Exponential growth observed starting in 2020.
- **Top Manufacturers:**
  1. Tesla (Market Leader)
  2. Chevrolet
  3. Nissan
- **Technology Split:**
  - **79.6%** Battery Electric Vehicles (BEV)
  - **20.4%** Plug-in Hybrid Electric Vehicles (PHEV)

## 🛠️ Tools & Technologies Used
- **Microsoft Power BI:** Main visualization and reporting tool.
- **Power Query (M):** Used for ETL (Extract, Transform, Load) to clean the raw CSV data.
- **DAX (Data Analysis Expressions):** Created custom measures for "Year-over-Year Growth" and dynamic fleet counts.
- **Excel/CSV:** Raw data storage and preliminary inspection.

## 📂 Dataset
The dataset is sourced from the Washington State Department of Licensing (DOL).
- **File:** `data/Electric_Vehicle_Population_Data.csv`
- **Key Columns:** `Model Year`, `Make`, `Electric Vehicle Type`, `City`, `Electric Range`.

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/EV-Market-Analysis.git](https://github.com/YourUsername/EV-Market-Analysis.git)
