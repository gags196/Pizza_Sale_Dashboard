# 🍕 Pizza Sales Revenue Dashboard (SQL + Power BI)

## 📊 Project Overview

An end-to-end KPI dashboard built using **SQL Server and Power BI** to analyze pizza sales data and generate actionable business insights. This project supports decision-making by surfacing trends in revenue, product performance, and customer behavior.

---

## 🔧 Tech Stack

- **SQL Server**: Data cleaning, transformation, and KPI computation
- **Power BI**: Data modeling, visualization, and dashboarding
- **DAX**: For dynamic visuals and calculations
- **Power Query**: Minimal post-load transformations

---

## 📁 Dataset

- **File**: `pizza_sales.csv` (loaded to SQL Server)
- **Records**: 48,620 rows
- **Source Fields**:
  - `order_id`, `order_date`, `pizza_name`, `pizza_size`, `pizza_category`
  - `unit_price`, `quantity`, `total_price`

---

## 📈 KPIs and Insights

Key metrics (calculated in SQL):
- **Total Revenue**
- **Total Pizzas Sold**
- **Average Revenue per Order**
- **Top 5 / Bottom 5 Selling Pizzas**
- **Revenue by Size, Category, and Time of Day**

Visual insights in Power BI:
- **Daily & Monthly Revenue Trends**
- **Sales by Pizza Category & Size**
- **Hourly Sales Heatmap**

---

## 🚀 How to Run

1. Load `pizza_sales.csv` into SQL Server.
2. Run the SQL script (included in the repo) to generate KPIs and final tables.
3. Open `Revenue Dashboard.pbix` in Power BI Desktop.
4. Connect Power BI to your SQL Server instance to refresh visuals.

---

## 💡 Business Value

- Identify best & worst performing pizzas to guide promotions
- Discover peak sales hours and high-performing categories
- Optimize inventory and staffing using trend analysis

---

## 👤 Author

**Gagan Negi**  
Power BI | SQL | Data Analysis | Python  
🔗 [LinkedIn]([https://www.linkedin.com](https://www.linkedin.com/in/gagan-negi-0122a6186/))

---

## 📌 License

Free to use under the [MIT License](LICENSE).
