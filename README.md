# 📊 Superstore Sales Analysis & Interactive Dashboard

## 📌 Project Overview
This project performs end-to-end data analysis and dashboarding on the Superstore dataset to uncover key business drivers of profitability and enable data-driven decision-making.

The analysis combines **Exploratory Data Analysis (EDA), statistical modeling, and interactive visualization** to identify trends in sales, profit, customer behavior, and pricing strategy.

---

## 🛠️ Tools & Technologies
- **Python**: pandas, numpy, matplotlib, seaborn
- **Statistical Analysis**: scipy, statsmodels
- **Dashboarding**: Power BI (.pbix interactive dashboard)
- **Environment**: Google Colab

---

## 📂 Repository Structure
  │ ├─ README.md # Project documentation
  │ ├─ Sample - Superstore.csv # Raw dataset
  │ ├─ Superstore_EDA_Complete.ipynb # Python analysis notebook
  │ ├─ Superstore_Dashboard.pbix # Power BI dashboard


---

## 🧹 Data Cleaning & Feature Engineering
- Handled missing values and removed duplicates
- Converted date columns for time-series analysis
- Ensured correct data types for Sales, Profit, Discount
- Created **YearMonth** for trend analysis
- Engineered KPIs like:
  - Loss-making orders
  - Profit per order
  - Customer segments

---

## 📊 Analysis Performed

### 🔍 Exploratory Data Analysis (EDA)
- Sales and profit distribution across regions and categories
- Discount vs Profit relationship
- Monthly and seasonal trends
- Customer segmentation (low, medium, high value)
- Region–category performance using pivot tables & heatmaps

---

### 📉 Statistical & Advanced Analysis
- **Outlier Detection (IQR Method)**  
  → Identified extreme values affecting business insights  

- **Correlation Analysis**  
  → Correlation dropped from **0.47 to 0.19 after removing outliers**, showing initial relationship was inflated  

- **Multiple Linear Regression**  
  → Analyzed impact of Sales, Discount, and Quantity on Profit  
  → Model performance improved (**R² ≈ 0.27**)  

- **Hypothesis Testing**
  - **T-Test (South vs Others)**  
    → No statistically significant regional difference (p > 0.05)
  - **ANOVA (Category Comparison)**  
    → Significant difference across categories (p < 0.05)

---

## 📊 Key Insights

- Discount has a **strong negative impact** on profit
- Sales positively influence profit but are affected by discounting
- Category significantly impacts profitability (Technology highest margin)
- Regional differences are **not statistically significant**
- Outliers were distorting the sales–profit relationship
- Business shows **strong seasonality (Nov–Dec peak)**

---

## 📊 Dashboard Highlights (Power BI)
- KPI cards: Total Sales, Profit, Orders
- Region-wise and Category-wise performance
- Monthly sales trend analysis
- Customer segmentation filters
- Drill-down capability for detailed insights

---

## 💡 Business Recommendations

- Optimize discount strategy to reduce unnecessary profit loss
- Focus on high-margin categories like Technology
- Target high-value customers for retention
- Monitor and investigate loss-making orders
- Align inventory and marketing with seasonal demand

---

## 📈 Outcome
- Analyzed **9,994+ records** to extract business insights
- Built a regression model to identify key profit drivers
- Validated insights using statistical testing
- Developed an **interactive Power BI dashboard** for decision-making

---

## 📌 Conclusion
Profitability is influenced by multiple factors including pricing strategy, product category, and customer behavior.  
A data-driven approach combining analysis and visualization can significantly improve business performance.
