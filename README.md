# E-Commerce Sales Analysis & Business Intelligence Dashboard

## Project Overview

This project presents an end-to-end analysis of an e-commerce sales dataset using Python and Tableau. The objective was to identify key business trends, uncover operational inefficiencies, and provide actionable recommendations that support sustainable business growth.

The analysis focuses on revenue performance, customer behaviour, fulfilment efficiency, cancellation patterns, return analysis, and inventory-related insights.

---

## Business Problem

The e-commerce company faces several operational challenges:

* Revenue leakage due to cancelled and returned orders
* Inefficient fulfillment processes
* High-risk product categories
* Regional variations in customer behaviour
* Inventory optimization challenges

The goal of this project is to leverage data analytics to identify opportunities for improving profitability, customer satisfaction, and operational efficiency.

---

## Dataset Information

The dataset contains order-level transactional information, including:

* Order Details
* Product Categories
* Quantity Sold
* Revenue
* Fulfilment Type
* Shipping Service Level
* Customer Type (B2B/B2C)
* Location Information
* Order Status
* Promotion Information

---

## Data Cleaning & Preparation

The following preprocessing steps were performed:

* Missing value treatment
* Null value replacement in the Amount column using the median
* Date feature engineering
* Creation of Year, Month, Week, Quarter dimensions
* Revenue and cancellation metrics generation
* Business KPI calculations

---

## Key Performance Indicators (KPIs)

The dashboard includes:

* Total Revenue
* Net Revenue
* Total Orders
* Average Order Value (AOV)
* Cancellation Rate
* Success Rate
* Revenue at Risk
* Revenue Leakage

---

## Tableau Dashboard Analysis

### Financial Performance

* Revenue Performance
* Net Revenue Tracking
* Revenue by Category
* Revenue by Day of Week

### Customer Insights

* Sales by State
* Top 10 Cities
* B2B vs B2C Growth Analysis

### Logistics & Fulfillment

* Fulfilment Performance
* Shipping Service Impact

### Risk & Returns Analysis

* Revenue Leakage
* Revenue at Risk
* Return by State
* Product Concentration vs Return

### Product Insights

* Category Performance
* Size Distribution Analysis

---

## Key Insights

* Revenue generation is concentrated within a limited number of product categories.
* Certain states contribute significantly more revenue than others.
* Cancellation and return rates create measurable revenue leakage.
* B2B and B2C customers exhibit different purchasing patterns.
* Fulfillment methods impact order success and customer experience.
* Specific products contribute disproportionately to return-related losses.

---

## Business Recommendations

### Revenue Growth

* Focus marketing efforts on high-performing categories.
* Expand sales initiatives in top-performing states.

### Customer Retention

* Improve customer experience in regions with high cancellation rates.
* Design targeted campaigns for B2B customers.

### Fulfillment Optimization

* Prioritize fulfillment channels with higher success rates.
* Improve shipping processes in underperforming regions.

### Inventory Management

* Maintain inventory for high-demand products.
* Reduce stock exposure for low-performing categories.

### Risk Reduction

* Investigate products with high return rates.
* Monitor revenue leakage and cancellation patterns continuously.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Tableau Public
* Jupyter Notebook

---

## Project Structure

```text
ecommerce-sales-analysis/
│
├── notebook/
│   └── Ecommerce_EDA.ipynb
│
├── tableau/
│   └── Ecommerce_Dashboard.twbx
│
├── images/
│   ├── dashboard_overview.png
│   ├── revenue_analysis.png
│   └── customer_analysis.png
│
├── data/
│   └── sales_dataset.csv
│
└── README.md
```

---

## Interactive Dashboard

View the interactive Tableau dashboard here:

https://public.tableau.com/shared/YTTNBH29W?:display_count=n&:origin=viz_share_link

---

## Future Improvements

* Predictive sales forecasting
* Customer segmentation models
* Product recommendation systems
* Return prediction analytics
* Inventory optimization models

---

## Author

Divyam Deep

Data Science | Analytics | Business Intelligence
