# 📊 Agricultural Sales Performance Dashboard

## 🌾 Project Overview

This project presents a comprehensive sales performance analysis of agricultural products using a custom-excel-built dashboard. 
The goal is to evaluate how effectively various agricultural products performed in terms of revenue generation, cost-efficiency, and market potential from 2022 to 2023. 
The dashboard offers valuable insights for stakeholders such as suppliers, farm managers, and agribusiness analysts to identify high-performing products, 
understand quarterly trends, and optimize inventory and sales strategies.

---

## 📁 Dataset Description

The dataset contains detailed transactional and logistical data on agricultural products shipped and sold between 2022 and 2023. 
It includes information such as product IDs, categories, prices, units sold/shipped, suppliers, and farm locations.

### Columns Included:

- `product_id`: Unique identifier for each product  
- `product_name`: Name of the agricultural product  
- `category`: Type/category of the product (e.g., grains, vegetables, fruits)  
- `price_per_kg(company)`: Company’s selling price per kg  
- `units_shipped_kg`: Quantity of product shipped (in kg)  
- `sale_date`: Date of sale  
- `units_sold_kg`: Quantity sold (in kg)  
- `units_on_hand_kg`: Remaining stock (in kg)  
- `supplier`: Supplier name  
- `farm_location`: Source farm location  
- `Actual revenue`: Computed as `price_per_kg * units_sold_kg`  
- `cost_per_kg (assumed 70%)`: Assumed to be 70% of selling price  
- `cost`: Total cost (`cost_per_kg * units_sold_kg`)  
- `profit`: Revenue - Cost  
- `efficiency`: Ratio of actual revenue to potential revenue  
- `unsold`: Quantity shipped but not sold  
- `Potential Revenue`: `price_per_kg * units_shipped_kg`  

---

## 📌 Key Performance Indicators (KPIs)

The dashboard tracks the following KPIs to provide insights into sales performance:

1. **Total Revenue from Agricultural Categories**  
   - Sum of all actual revenues across all product categories.

2. **Total Profit Margin**  
   - Aggregate profit across all product categories (Actual Revenue - Cost).

3. **Sales Efficiency**  
   - Percentage ratio of actual revenue to potential revenue.

4. **Total Revenue Potential**  
   - Maximum possible revenue if all units shipped were sold.

5. **Revenue vs. Potential Revenue (Category-wise)**  
   - Side-by-side comparison of actual revenue against potential revenue for each category.

6. **Average Selling Prices (Category-wise)**  
   - Average `price_per_kg` per product category.

7. **Quarterly Sales Performance (2022–2023)**  
   - Time-series breakdown of revenue across quarters.

8. **Top Performing Products/Categories**  
   - Products/categories with the highest actual revenue relative to potential.

---

## 🧰 Tools & Technologies

- **Excel / Dashboard** – for data transformation and visualization  
- **Power Query / DAX** – for calculated fields in BI tools  
- **Git/GitHub** – for version control and collaboration  

---

## 🚀 Getting Started
To explore or extend this project:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/agriculture-sales-dashboard.git
2. Open the dashboard file in your preferred BI tool or view the exported visualizations.
3. Review the data/ folder for the cleaned dataset and calculated columns.
4. Check out the notebooks/ folder (if applicable) for exploratory analysis.

## 📈 Sample Visuals
(![Screenshot 2025-05-21 092734](https://github.com/user-attachments/assets/e6709f9b-f0e4-4e3f-a969-6fd92d3cab89)
![Screenshot 2025-05-21 092433](https://github.com/user-attachments/assets/65350859-e839-4dcb-bb12-b62eb665f08f)

## 🧠 Insights & Observations
- Categories like livestock & diary outperformed others in actual revenue.
- Certain products consistently showed high efficiency, indicating good market fit and minimal wastage.
- Quarterly analysis revealed a revenue spike in Q3 for both year [2023 & 2024] due to harvest season.

## 📬 Contact
- [Email](adewaleabdulmuiz75@gmail.com)

👉 For detailed KPI analysis, visit the [Project Wiki](https://github.com/DevMuzee/Agricultural_revenue_performance/wiki)
