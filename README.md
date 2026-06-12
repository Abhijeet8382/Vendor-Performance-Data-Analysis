# Vendor Performance Data Analytics: End-to-End Project

## 📌 Business Problem
Effective inventory and sales management are critical for optimizing profitability in the retail and wholesale industry. The enterprise must ensure it is not incurring losses due to inefficient pricing, poor inventory turnover, or an over-reliance on specific vendors. 

The goal of this project is to investigate the profitability variance between high-performing and low-performing vendors, identify brands needing price adjustments, and analyze the impact of bulk purchasing.

## 🛠️ Tools & Tech Stack
* **Python:** Pandas, NumPy, SciPy (Data Cleaning, EDA, Hypothesis Testing)
* **SQL (SQLite):** Data Ingestion, Joins, Aggregations
* **Power BI:** Interactive Dashboards & Data Visualization

## ⚙️ Steps Followed
1. **Data Ingestion (ETL):** Automated the extraction of raw inventory and invoice data into an SQLite database.
2. **Data Transformation:** Executed SQL queries to create unified, aggregated summary tables.
3. **Exploratory Data Analysis (EDA):** Used Python to clean data, identify outliers, and perform correlation analysis.
4. **Statistical Testing:** Conducted T-Tests to validate significant statistical differences in profit margins.
5. **Dashboarding:** Built a dynamic Power BI dashboard to visualize KPIs like Unsold Capital and Vendor Contribution.

## 💡 Key Insights
* **Bulk Purchasing Impact:** Vendors buying in large volumes see an average unit price reduction of 72%, proving that bulk pricing strategies successfully encourage higher volume purchases.
* **Locked Capital:** Identified **$2.71 Million** tied up in unsold inventory, highlighting slow-moving products that inflate warehouse holding costs.
* **Profitability Variance:** Counterintuitively, statistical testing revealed that low-performing vendors maintain significantly higher profit margins (40.4% - 42.6%) compared to high-performing vendors, suggesting they sell premium niche items.

## 📁 Repository Structure
* `01_Data_Ingestion_and_ETL.ipynb` - Python scripts for moving raw CSVs into SQLite.
* `02_Exploratory_Data_Analysis.ipynb` - Initial data exploration and outlier detection.
* `03_Vendor_Performance_Analysis.ipynb` - Deep dive analytics and hypothesis testing.
* `Presentation/` - Comprehensive business summary.
* `Dashboard/` - Power BI dashboard file and screenshots.
* `Dataset/` - Cleaned dataset used for this analysis.
