# Analysis-of-chocolate-sales
End-to-end global chocolate retail sales analysis using SQL, Python, and Tableau. Leveraged advanced CTEs and window functions for RFM and Cohort analysis. Conducted Pearson correlation and statistical significance testing ($p\text{-value}$) in Python to evaluate promotional pricing impacts. Includes interactive Tableau retention dashboards.

# 🍫 Chocolate Sales & Advanced Customer Analytics

## 📌 Project Overview
An end-to-end data analytics project evaluated on global chocolate sales performance. The project integrates multi-table SQL queries, statistical validation, RFM customer segmentation, cohort retention analysis, and Tableau visualization to generate data-driven commercial strategies.

---

## 🛠️ Tech Stack & Methods
* **SQL & Data Aggregation**: `pandasql` (`sqldf`) for relational multi-table joins (CTE, Window Functions).
* **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, `scipy.stats` (Pearson Correlation).
* **Advanced Analytics**: RFM Segmentation, Cohort Analysis, Statistical Hypothesis Testing.
* **BI & Dashboards**: Tableau Public.

---

## 🔍 Key Insights & Strategic Findings

### 1. Statistical & Correlation Analysis
* **Revenue vs. Profit ($r = 0.9662$, $p < 0.001$):** Exceptionally strong, statistically significant positive linear relationship, indicating consistent pricing margins.
* **Discount Impact ($r = -0.13$ with Revenue / $-0.12$ with Profit):** Promotional discounts show near-zero/negative correlation with sales volume and profitability. **Strategic Takeaway:** Broad price discounting fails to drive incremental volume and actively erodes profit margins.

### 2. Customer Analytics (RFM & Cohorts)
* **RFM Segmentation:** Evaluated Recency, Frequency, and Monetary metrics alongside demographic features (Gender, Age, Loyalty Membership, Location).
* **Cohort Analysis:** Tracked customer acquisition layers over time to analyze lifecycle retention. 
* 📊 **Tableau Interactive Dashboard:** [View Cohort Analysis Dashboard on Tableau Public](https://public.tableau.com/app/profile/mariia.korotnian/viz/Cohortanalysischocolate/Cohortanalysis)
* 📊 **Dashboard of RFM analysis:** [https://public.tableau.com/app/profile/mariia.korotnian/viz/Chocolaterfmanalysis/Dashboard1?publish=yes]

### 3. Store & Geographical Dynamics
* **Average Check Consistency:** Stable average check (~$25.3–$25.7) across all sales channels (Airport, Mall, Online, Retail) and months.
* **Top Performers:** Australia leads total revenue and monthly order stability, while Toronto leads overall city profit.
* **Category Demand:** **Praline** and **White Chocolate** dominate consumer preference across major metropolitan markets (Berlin, London, New York, Paris, Sydney, Toronto).
 
<img src="https://github.com/user-attachments/assets/9fb6e3fd-107a-4201-b257-ebc2c0c7724a" alt="Overall Sales Dashboard" width="100%" />
<img src="https://github.com/user-attachments/assets/0cde7e20-4870-431c-8c50-ecfb19ed011f" alt="Sales Dynamics" width="100%" />
<img src="https://github.com/user-attachments/assets/fe89157d-b588-4e75-90de-235af42afaae" alt="Australia Performance" width="100%" />
<img src="https://github.com/user-attachments/assets/4e1217af-13ed-45d5-b527-560cf9bf308b" alt="Categories Heatmap" width="100%" />


---

## 📂 Repository Structure
