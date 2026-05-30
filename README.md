# E-Commerce Sales Analysis & Business Intelligence Dashboard
<div class='tableauPlaceholder' id='viz1780166956157' style='position: relative'><noscript><a href='#'><img alt='Dashboard 3 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;YT&#47;YTTNBH29W&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;YTTNBH29W' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;YT&#47;YTTNBH29W&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1780166956157');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='2227px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

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
