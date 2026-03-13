# Olist E-commerce  Analytics Dashboard

This project analyzes e-commerce sales and delivery performance using the Olist Brazilian E-commerce dataset. The workflow includes Python-based data preprocessing, feature engineering, and the development of an interactive business intelligence dashboard in Power BI.

The objective is to transform raw transactional data into meaningful insights that support decision-making related to logistics performance, product sales trends, and operational efficiency.

---

## Project Overview

Modern organizations rely heavily on data visualization and business intelligence to understand operational performance and identify patterns in large datasets. In this project, the Olist Brazilian E-commerce dataset was used to explore sales performance, delivery efficiency, and logistics patterns.

The project consists of three major stages:

1. Data preprocessing and feature engineering using Python
2. Exploratory data analysis and metric creation
3. Interactive dashboard development using Power BI

The final dashboard enables stakeholders to monitor key performance indicators such as revenue trends, delivery delays, freight costs, and product category performance.

---

## Dataset

The dataset used in this project is the **Brazilian E-commerce Public Dataset by Olist**, available on **Kaggle**.

Source:  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains multiple tables including:

- Orders
- Order items
- Products
- Customers
- Payments
- Reviews
- Geolocation data

These tables were merged and processed to create a unified dataset for analysis.

---

## Data Processing

Data preprocessing and feature engineering were performed using Python.

Key steps included:

- Loading and inspecting datasets using Pandas
- Converting timestamp columns into datetime format
- Filtering delivered orders
- Handling missing values
- Creating new analytical features such as:

    - Actual delivery time
    - Estimated delivery time
    - Delivery delay
    - Late delivery flag
    - Total revenue (product price + freight cost)
    - Order year and month

These transformations allowed the dataset to support meaningful business metrics used in the dashboard.

---

## Dashboard Features

The interactive dashboard built using **Power BI** provides several analytical views:

### Executive Sales Overview
Displays high-level KPIs including:

- Total revenue
- Total orders
- Average delivery time
- Late delivery rate

### Revenue and Order Trends
Time-series analysis of:

- Monthly order volume
- Monthly revenue performance

### Product Category Performance
Identifies top-performing product categories based on revenue and order volume.

### Logistics Performance
Analyzes delivery performance including:

- Delivery time distribution
- Late vs on-time deliveries
- Geographic distribution of orders

### Freight Cost Analysis
Explores relationships between product price and shipping costs to identify potential inefficiencies.

The dashboard supports interactivity through filters, slicers, and drill-down functionality, allowing users to explore patterns across time, location, and product categories.

---

## Technologies Used

This project was implemented using the following technologies:

- Python
- Pandas
- Jupyter Notebook / VS Code Notebook
- Power BI
- Data Visualization
- Business Intelligence

---


---

## Dashboard Preview

A preview of the Power BI dashboard is shown below.

<img width="1298" height="741" alt="Screenshot 2026-03-13 193430" src="https://github.com/user-attachments/assets/86690061-be18-4b83-97eb-b2536b1e9233" />
<img width="1300" height="744" alt="Screenshot 2026-03-13 193442" src="https://github.com/user-attachments/assets/824b7a93-169f-4ec8-8565-486197e91fb1" />
<img width="1302" height="777" alt="Screenshot 2026-03-13 193453" src="https://github.com/user-attachments/assets/9eed4600-b5d5-4c54-934d-6489034dedab" />
<img width="1300" height="740" alt="Screenshot 2026-03-13 193507" src="https://github.com/user-attachments/assets/47c4ab7b-1e71-4d5e-bb75-85ebbe340dbf" />


---

## Key Insights

The analysis reveals several operational insights:

- Certain product categories generate significantly higher revenue.
- Delivery delays vary across regions, indicating logistics inefficiencies.
- Freight costs represent a noticeable portion of total revenue for lower-priced items.
- Monthly trends reveal fluctuations in order volume and sales.

These insights demonstrate how data visualization can help businesses identify operational bottlenecks and optimize logistics performance.

---

## Future Improvements

Potential improvements to this project include:

- Integration of machine learning models to predict delivery delays
- Real-time dashboard updates using streaming data
- More advanced geographic analysis using city-level geolocation
- Automated data pipelines for continuous data refresh

---

## License

This project is for academic and educational purposes.  
The dataset used is publicly available through the Kaggle Olist dataset.
