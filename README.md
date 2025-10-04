# 🛒 E-Commerce Sales & Profit Analysis Dashboard  

### Created by **Vaibhav Kumar Bajpai**

---

## 📘 Overview  
This project presents a detailed **E-Commerce Sales and Profit Analysis Dashboard** built in **Microsoft Power BI**.  
The dashboard is powered by an Excel dataset and provides **KPIs, interactive charts, and drill-down features** to analyze sales, profit, cost, and customer insights.  

---

## 📁 Project Files  
| File Name | Description |
|------------|-------------|
| **Ecommerce.pbix** | Power BI dashboard file containing all reports and visualizations. |
| **Ecommerce.xlsx** | Dataset used as a data source for the dashboard. |

---

## 📊 Key KPIs (Measures Created)  
The following **measures** were created in Power BI using **DAX**:  
- **Total Sales** → `SUM(Sales)`  
- **Total Profit** → `SUM(Profit)`  
- **Total Orders** → `DISTINCTCOUNT(Order ID)`  
- **Total Customers** → `DISTINCTCOUNT(Customer Name)`  
- **Profit Margin %** → `DIVIDE(SUM(Profit), SUM(Sales))`  
- **Total Cost** → `SUM(Cost)`  
- **Sales vs Cost Difference** → `SUM(Sales) - SUM(Cost)`  

These KPIs are displayed in **cards** at the top of the dashboard for quick overview.  

---

## 📊 Visualizations Used  

### 1. **KPI Cards**
- Displaying **Total Sales, Profit, Orders, and Customers** in a summarized view.  

### 2. **Donut Charts**
- **Profit Margin by Product Category** – shows contribution of categories like Classic Cars, Vintage Cars, Trains, etc.  
- **Sales by Region** – compares East, West, North, South performance.  

### 3. **Bar/Column Charts**
- **Sales by City** – highlights top performing cities (Madrid, San Rafael, NYC).  
- **Total Cost by Product Line** – identifies cost-heavy product lines.  
- **Sales vs Cost by Product** – side-by-side comparison of profitability.  

### 4. **Line Chart**
- **Month-wise Sales & Profit Trend** – tracks performance and seasonal trends throughout the year.  

### 5. **Map Visualization**
- **Regional Sales Distribution** – shows sales on a geographical map for quick location insights.  

---

## 🎯 Objective  
The dashboard aims to:  
- Track **overall sales and profit performance**.  
- Identify **high-profit products** and **loss-making items**.  
- Compare **regional and city-based sales**.  
- Provide actionable insights for **business decision-making**.  

---

## 🧠 Insights Derived  
- **Classic Cars** and **Vintage Cars** are top-performing categories in sales but also incur high costs.  
- **Madrid** and **San Rafael** emerge as leading cities by total sales.  
- Seasonal sales trends indicate **month-on-month fluctuations**, useful for forecasting.  
- The **East region** has higher sales compared to other regions.  
- Clear identification of **high-margin products** vs **low-margin products**.  

---

## ⚙️ Tools & Technologies Used  
- **Microsoft Power BI** – For creating interactive reports & dashboards.  
- **Microsoft Excel** – Dataset preparation and data cleaning.  
- **DAX (Data Analysis Expressions)** – For calculated measures and KPIs.  

---

## 👨‍💻 Author  
**Vaibhav Kumar Bajpai**  
📧 [vaibhavbajpai102@gmail.com](mailto:vaibhavbajpai102@gmail.com)  



---

## 🏷️ GitHub Tags  
`#PowerBI` `#DataVisualization` `#ECommerceDashboard` `#SalesAnalysis` `#ProfitAnalysis` `#VaibhavKumarBajpai`

---

## 📂 Repository Structure  
