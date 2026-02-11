# Coffee Orders Data Analysis

## Project Overview
This project analyzes coffee sales data to explore sales trends across different coffee types and time periods. The dataset contains **47 rows and 6 columns**, representing the monthly sales of four major coffee types over multiple years.  
The objective is to identify sales trends, seasonal performance, and best-selling coffee varieties.

---

## Dataset Description
Columns in the dataset:
- `Years (Order Date)` – Year in which the sales occurred  
- `Months (Order Date)` – Month corresponding to the sales record  
- `Arabica` – Total monthly sales of Arabica coffee  
- `Excelsa` – Total monthly sales of Excelsa coffee  
- `Liberica` – Total monthly sales of Liberica coffee  
- `Robusta` – Total monthly sales of Robusta coffee  

---

## Data Cleaning & Preparation
1. Removed blank or merged header rows for proper structure.  
2. Renamed columns for clarity (e.g., `Years (Order Date)` → `Year`, `Months (Order Date)` → `Month`).  
3. Handled missing values by forward-filling data for months without entries.  
4. Converted year and month columns into a single `Date` column for time series analysis.  
5. Checked for duplicates and removed redundant rows.  
6. Saved the cleaned dataset for further visualization and analysis.

---

## Data Analysis & Visualization

### 1. Coffee Sales Trend Over Time
- **Insight:** All coffee types show steady sales with noticeable fluctuations across months.  
- **Arabica** and **Liberica** maintain strong, consistent sales, indicating stable demand.  
- **Visualization:** Line chart showing monthly sales trend for all coffee types.

---

### 2. Top-Selling Coffee Type
- **Insight:** **Excelsa** shows the highest average sales in several months, followed closely by **Liberica**.  
- **Visualization:** Bar chart comparing total annual sales for each coffee type.

---

### 3. Yearly Sales Performance
- **Insight:** The year **2019** records moderate growth, with sales rising during the middle of the year and tapering off toward December.  
- **Visualization:** Line plot of total monthly sales across the year.

---

### 4. Seasonal Trends
- **Insight:** Sales peak between **March and May**, likely due to higher coffee demand during the start of summer.  
- **Visualization:** Bar chart showing monthly averages across all coffee types.

---

### 5. Coffee Type Comparison
- **Insight:**  
  - **Arabica:** Stable and consistent sales, preferred by regular customers.  
  - **Excelsa:** Strong peaks, suggesting occasional promotions or seasonal preference.  
  - **Liberica:** Performs steadily with good contribution to total revenue.  
  - **Robusta:** Lower sales volume but steady, possibly catering to a niche market.  
- **Visualization:** Stacked bar or area chart comparing the contribution of each coffee type to total sales.

---

## Recommendations
1. **Promote Excelsa & Liberica:** These types perform best; offering combo packs or discounts may drive repeat purchases.  
2. **Boost Robusta Sales:** Consider marketing campaigns or loyalty offers to increase its visibility.  
3. **Seasonal Strategy:** Since sales peak around March–May, stock management and targeted advertising should align with this period.  
4. **Track Long-Term Growth:** Introduce dashboards to monitor yearly performance and emerging trends.  
5. **Diversify Offerings:** Introduce flavored or limited-edition variants of Arabica and Excelsa during off-peak months.

---

## Conclusion
The coffee sales analysis reveals that **Excelsa and Liberica** are the most profitable and consistent coffee types, contributing significantly to overall revenue.  
**Arabica** maintains a stable demand, while **Robusta**, though less popular, holds potential for targeted marketing.  
Seasonal variations suggest that demand spikes during **early summer**, emphasizing the need for better stock planning and strategic promotional activities.  
Overall, the dataset highlights valuable opportunities for **product focus, marketing timing, and inventory optimization** to improve business performance.

