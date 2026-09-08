# E-Commerce Executive Performance Dashboard
## Project Description
I developed a comprehensive project in Excel, creating multiple dashboards and tables to analyze data. This process involved several stages including data preprocessing, data cleaning, and data visualization using the Excel Data Model.
## Project Objective
The objective is to provide executives with an interactive view of business health to optimize pricing strategies. The dashboard tracks gross vs. net revenue, category-level discount leakage, order volumes and payment gateway trends.
## Dataset used
-<a href="https://github.com/morara26/Data-Analysis-Dashboard/blob/main/ecommerce_dataset_updated.csv">Dataset</a>

##  Questions (KPIs)
* **Revenue Health:** What is the Total Gross Revenue compared to Total Net Revenue?
* **Margin Leakage:** Which product categories lose the most revenue to discounts?
* **Time-Series Trends:** How does revenue fluctuate month-over-month?
* **Transaction Preferences:** What are the most popular payment gateways by volume?
  
- Dashboard Interaction <a href="https://github.com/morara26/Data-Analysis-Dashboard/blob/main/E-commerce.png">View Dashboard</a>
## Process
1. **Data Preprocessing & Cleaning:** Handled missing values and standardized categorical variables.
2. **Data Modeling:** Loaded cleaned data into the Excel Data Model (Power Pivot) to connect multiple tables.
3. **Metric Calculation:** Created dynamic Pivot Caches to aggregate Revenue, Discount Loss and Average Discount.
4. **Data Visualization:** Engineered a modern interface with floating KPI cards, clean charts and interactive slicers.

## Dashboard
<img width="905" height="734" alt="E-commerce" src="https://github.com/user-attachments/assets/730b2d3a-faed-4b4b-ae48-44bd78c95a00" />

## Project Insights
* **Overall Performance:** The store generated **$757,278 Net Revenue** ($932,570 Gross) across 3,660 total orders.
* **Discount Impact:** A flat ~18.8% discount rate resulted in **$175,292 lost** to discounts.
* **Top Categories:** **Clothing** ($115k) and **Books** ($111k) drove the highest net revenue.
* **Payment Preferences:** **Credit Cards** and **UPI** are the top gateways, indicating a mobile-first customer base.
* **Seasonality:** Revenue peaked in **October** ($76k) but dropped sharply in **November** ($51k).

## Final Conclusion
While the store maintains healthy transaction volumes, the universal ~18-19% discount rate is causing significant margin leakage, particularly in "Books" and "Home & Kitchen." Transitioning from a flat store-wide discount strategy to targeted promotions will optimize profitability and reclaim gross margin.
