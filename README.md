# Power BI Sales & Profit Analysis Dashboard

This repository contains an interactive Power BI report and SQL scripts used to analyze revenue, sales quantity, and profit metrics across different cities, markets, products, and customers. The dashboard provides insights to support data-driven business decisions.

---

## 📊 Dashboard Overview

### ✨ Key Highlights

- **Total Sales Revenue:** ₹985M
- **Total Sales Quantity:** 2M Units
- **Total Profit Margin:** ₹2.1M (varies by year)

---

## 🔍 Key Insights Dashboard

- **Revenue by Markets**
  - Delhi NCR leads with ₹520M
  - Followed by Mumbai, Ahmedabad, Bhopal

- **Sales Qty by Markets**
  - Highest quantity sold in Delhi NCR

- **Revenue Trend Over Time**
  - Visualizes revenue fluctuations from 2017 to 2020
  - Peaks observed around mid-2018

- **Top 5 Customers**
  - Electricalsara Stores: ₹413M
  - Electricalsytical: ₹50M
  - Excel Stores, Premium Stores, Nixon follow

- **Top 5 Products**
  - Top product contributes ₹469M

---

## 📈 Profit Analysis Dashboard

- **Revenue Contribution % by Market**
  - Delhi NCR: 54.7%
  - Mumbai: 14.2%
  - Ahmedabad: 12.7%

- **Profit Contribution % by Market**
  - Highest profit contribution from Mumbai and Delhi NCR
  - Negative profit contributions seen in Lucknow and Hyderabad

- **Profit % by Market**
  - Hyderabad and Lucknow display negative profit margins
  - Bhubaneswar shows significant positive margin (10.5%)

- **Revenue Trend**
  - Declining trend noted in 2020

- **Customer-wise Revenue & Profit Analysis**
  - Electricalsara Stores contributes ~46.2% of total revenue
  - Profit Margin % varies from negative to over 11

---

## 📊 Performance Insights Dashboard

- **Revenue Contribution % by Market**
  - Patna and Bhubaneswar contribute ~26% each
  - Negative contributions observed from Hyderabad and Lucknow

- **Revenue Trend**
  - Sharp drop in revenue in mid-2020

- **Detailed Customer Table**
  - Includes:
    - Revenue
    - Revenue Contribution %
    - Profit Margin Contribution %
    - Profit Margin %

- **Profit Target**
  - Adjustable target to analyze impact on profitability


---


---

## 🗄️ SQL Scripts

This repository includes SQL scripts used to generate the datasets for Power BI visuals:

- `revenue_analysis.sql` – extracts revenue by month and market.
- `top_customers.sql` – retrieves top customers based on total revenue.
- `top_products.sql` – retrieves top products based on sales value.
- `market_contribution.sql` – calculates revenue and profit contributions by market.
- `profit_analysis.sql` – computes profit margin metrics by market and customer.

You can run these SQL scripts against the data warehouse to reproduce the same datasets for Power BI.

---

## 🛠️ Tools Used

- **Power BI Desktop**
- **SQL Server** (or your preferred database)
- **DAX** for custom measures and calculations
- **Excel/CSV Data Sources**

---

## 🚀 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/Praveenkumar-p-git/powerbi-sales-dashboard.git
    ```
2. Run the SQL scripts in the `/sql` folder to create or extract the datasets.
3. Load the datasets into Power BI Desktop.
4. Open the `.pbix` file in Power BI Desktop.
5. Explore interactive visuals and filters to derive insights.

---

## 💡 Insights

- Delhi NCR dominates both revenue and sales volume.
- Some markets are underperforming and causing negative profit margins.
- Significant fluctuations in revenue trend from 2018 to 2020.
- Electricalsara Stores is the top customer by revenue contribution.

---

## 👤 Author

  **[Praveen kumar]**  
🔗 [LinkedIn](https://linkedin.com/in/itzpraveen)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📷 Dashboard Screenshots

### Key Insights
![Key Insights](./Key%20Insights.png)

### Profit Analysis
![Profit Analysis](./Profit%20Analysis.png)

### Performance Insights
![Performance Insights](./Performance%20Insights.png)



