# 🛒 E-Commerce Business Intelligence Dashboard

![Executive Overview](Screenshots/Executive%20Overview.png)

## 📌 Project Overview
An end-to-end Power BI Business Intelligence Dashboard designed to analyze the performance of a Brazilian E-Commerce store. This project features a custom-built Star Schema data model, advanced DAX measures, and a highly accessible, premium minimalist "Neomorphic" UI design. 

The dashboard provides actionable insights into revenue, customer behavior, product performance, logistics, and seller analytics to drive strategic business decisions.

## 📊 Dashboard Previews

### Customer & Satisfaction Analytics
![Customer Analytics](Screenshots/Customer%20Analytics.png)
![Customer Satisfaction](Screenshots/Customer%20Satisfaction%20Analytics.png)

### Logistics, Product & Seller Performance
![Logistics & Delivery](Screenshots/Logistics%20&%20Delivery%20Analytics.png)
![Product Analytics](Screenshots/Product%20Analytics.png)
![Seller Performance](Screenshots/Seller%20Performance%20Analytics.png)

## 📂 Dataset Information

**Dataset Name:** Brazilian E-Commerce Public Dataset by Olist  
**Source:** Kaggle  
**Dataset Link:** [Olist E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

### Description
The dataset contains approximately 100,000 e-commerce orders placed on the Olist Store between 2016 and 2018. It includes customer information, order details, products, sellers, payments, reviews, and geolocation data. This dataset was used to perform end-to-end business intelligence analysis, build a star schema data model, create DAX measures, and develop interactive Power BI dashboards.

### Dataset Tables Used:
* `olist_customers_dataset.csv`
* `olist_orders_dataset.csv`
* `olist_order_items_dataset.csv`
* `olist_order_payments_dataset.csv`
* `olist_order_reviews_dataset.csv`
* `olist_products_dataset.csv`
* `olist_sellers_dataset.csv`
* `product_category_name_translation.csv`

*(Note: Raw dataset files are ignored via `.gitignore` due to size limitations, but can be downloaded from the Kaggle link above).*

## 🎨 Custom Theme
The dashboard utilizes a custom JSON theme (`Theme/Color_Theme.json`) featuring a **Premium Minimalist** aesthetic. It incorporates clean whitespace, soft drop shadows (neomorphism), and striking Indigo (`#6366F1`) KPIs with perfectly contrasted typography for maximum accessibility.

## 🚀 How to Use
1. Clone this repository.
2. Download the raw CSV datasets from Kaggle and place them in the `Dataset/` folder.
3. Open `Dashboard/Dashboard File.pbix` in **Power BI Desktop**.
4. If necessary, refresh the data source paths in Power Query to point to your local `Dataset/` folder.
