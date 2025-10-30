# Coffee-Shop-Sales
Data analysis of coffee shop chains — locations, distribution, and growth trends


## 🎯 Project Goal
The goal of this project is to analyze the sales data of a coffee shop chain, 
identify key trends and factors influencing revenue.  
The analysis will help answer the following questions:
- Which products and categories are the most popular
- What is the sales dynamics over the entire period
- How sales change throughout the day, week, and time of day
- Which locations generate the highest revenue
- What is the average ticket and how many items are usually purchased per transaction

The insights will be visualized in an interactive Tableau dashboard.

## 🧩 Dataset Description
The dataset contains coffee shop transactions with the following variables:
- `transaction_id` — unique transaction identifier
- `transaction_date` — date of purchase
- `transaction_time` — time of purchase
- `transaction_qty` — number of items in the transaction
- `store_id` — store ID
- `store_location` — city/store location
- `product_id` — product ID
- `unit_price` — unit price
- `product_category` — product category (coffee, tea, pastry, etc.)
- `product_type` — product subcategory
- `product_detail` — detailed product description

## 📚 Data Source
Data obtained from [Kaggle: Coffee Shop Sales Dataset](https://www.kaggle.com/code/ahmedabbas757/coffee-shop-sales/input)  
The dataset contains 149,116 rows and 11 columns.  

## 🔍 Analysis / Workflow
The analysis followed these main steps:
1. **Data Preparation** – load dataset, inspect structure, handle missing values and duplicates  
2. **EDA** – explore basic stats, visualize distributions, detect outliers  
3. **Data Transformation** – adjust data types, add features (weekday, month, hour)  
4. **Sales Analysis** – review total sales, average check, and key time-based trends

## 💡 Key Insights
- **Overall Performance:** Sales across the coffee shop network are generally stable, with only minor drops around holidays (e.g., Memorial Day).  
- **Hourly Trends:** Peak activity occurs between **7:00–10:00 AM**, driven by morning visitors.  
- **Location Patterns:**  
  - *Astoria* – strong morning and evening sales, typical of residential areas.  
  - *Hell’s Kitchen* – highest sales from **8:00–11:00 AM**, consistent with office-dense districts.  
  - *Lower Manhattan* – morning-dominated activity (peak at **7:00 AM**), minimal evening demand.  
- **Average Check:** Stable across all days; *Lower Manhattan* slightly leads in average order value.  
- **Product Mix:** Coffee and tea generate the majority of sales, followed by bakery. Secondary categories, though smaller in share, enhance variety and help boost the average check.

## 📊 Tableau Dashboards  
Here are a few screenshots of the Tableau dashboards.  
You can explore the interactive versions via the links below.
<img width="1759" height="1046" alt="image" src="https://github.com/user-attachments/assets/bb0f8efd-ad47-4e02-976d-cfa2c1148fcb" />  

<img width="1759" height="1039" alt="image" src="https://github.com/user-attachments/assets/216d2920-7edb-42c5-8c68-076ab8f9c27f" />


[Coffee Shop Sales Dashboard](https://public.tableau.com/app/profile/iryna.kucheruk/viz/CoffeeShopSalesDashboard_17602039776290/SalesbyStore)  
[Product Category Analysis](https://public.tableau.com/app/profile/iryna.kucheruk/viz/ProductCategoryAnalysis_17602038496790/ProductCategoryAnalysis)
