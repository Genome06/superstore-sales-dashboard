# Global Superstore Data Analysis & Visualization
This project demonstrates an end-to-end data analytics workflow, from raw data cleaning and feature engineering using Python to creating an interactive business intelligence dashboard in Tableau.

## 📌 Project Overview
The goal of this project is to analyze the "Global Superstore" dataset to uncover business performance insights. By processing raw transactional data, I transformed it into a structured format suitable for high-level executive reporting, focusing on profitability and operational efficiency.

## 🛠️ Tech Stack
- **Data Processing:** Python (Pandas, NumPy)
- **Environment:** Jupyter Notebook / Google Colab
- **Visualization:** Tableau Desktop
- **Dataset:** Global Superstore (Retail Data)

## 📊 Key Performance Indicators (KPIs)
The dashboard focuses on four primary metrics to evaluate business health:
1. **Total Sales:** Overall revenue generated.
2. **Total Profit:** Net earnings after costs.
3. **Profit Margin (%):** Efficiency of turning sales into profit.
4. **Total Orders:** Total volume of transactions.

## ⚙️ Data Engineering Process
1. **Data Cleaning:** Handled missing values, corrected data types, and removed duplicates.
2. **Feature Engineering:**
   - `profit_margin`: Calculated the percentage of profit relative to sales.
   - `shipping_duration`: Calculated the days elapsed between order and ship date.
   - `is_profitable`: A boolean flag to quickly segment profitable vs. loss-making transactions.
3. **Date Transformation:** Extracted Year, Month, and Week numbers for time-series analysis.

## 📈 Dashboard Highlights
**[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/GlobalSuperstoreExecutiveSalesInsightsDashboard/GlobalSuperstoreDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)📈**

![Dashboard Screenshot](<img width="1365" height="767" alt="Global Superstore Dashboard" src="https://github.com/user-attachments/assets/98e8f78f-be89-46f6-9c30-420866ba9bae" />)

The dashboard includes:
  - **Sales Trend (Line Chart):** Monitoring revenue fluctuations over time to identify seasonality.
  - **Geographical Distribution (Map):** Highlighting sales performance across different states.
  - **Category & Sub-Category Performance (Bar Charts):** Identifying which product lines drive the most revenue.

## 💡 Key Insights
Based on the analysis and the interactive dashboard, several key business insights were identified:

1. **Profitability vs. Volume:** While the business achieved high Total Sales ($12.64M), the average **Profit Margin stands at 11.6%**. This indicates a healthy business, but suggests potential for cost optimization in low-margin categories like Furniture.
2. **Seasonal Peaks:** The Sales Trend analysis reveals consistent revenue spikes during **Q4 (November - December)**, likely driven by end-of-year holidays. This suggests a need for increased inventory and shipping capacity during these months.
3. **Geographic Performance:** Certain states contribute significantly more to the total profit despite having moderate sales volumes, highlighting the importance of focused marketing in high-margin regions.
4. **Category Efficiency:** The **Technology** category consistently delivers the highest profit margins, whereas **Office Supplies** drives the highest volume of orders, serving as the main customer acquisition segment.

## 🚀 How to Use
1. Clone this repository.
2. Explore the notebooks `.ipynb` file to see the data transformation logic.
3. Open the `.twbx` file in Tableau Desktop or Tableau Reader to interact with the dashboard.
