# E-Commerce Sales Performance Dashboard

## OVERVIEW  
This project analyzes e-commerce transaction data to uncover sales performance, customer value, order behavior, and revenue trends across time, products, countries, and transaction status.

The project demonstrates how **Power BI** can be used to transform raw e-commerce data into an interactive, insight-driven dashboard for business decision-making.

## 📁 DATA SOURCE  
This project uses the **E-Commerce Data** dataset from Kaggle:

[https://www.kaggle.com/datasets/carrie1/ecommerce-dat]
The dataset contains transactional-level e-commerce data with the following fields:

- **InvoiceNo** – Unique identifier for each transaction  
- **StockCode** – Unique product code  
- **Description** – Product name/description  
- **Quantity** – Number of items purchased per transaction  
- **InvoiceDate** – Date and time of the transaction  
- **UnitPrice** – Price per unit of product  
- **CustomerID** – Unique identifier for each customer  
- **Country** – Customer’s country of purchase  

## BUSINESS PROBLEM  
E-commerce businesses often struggle to quickly understand what drives revenue, who their best customers are, and when sales peak. Without a clear performance view, it’s difficult to optimize marketing, inventory, and customer experience.

This project addresses these challenges by analyzing:
- Revenue growth over time  
- Top-performing products and customers  
- Order behavior by time and location  
- Completion vs cancellation patterns  

## BUSINESS QUESTIONS & KPIs  

### KPIs
- Total Revenue  
- Total Orders  
- Total Customers  
- Average Order Value (AOV)  

### Business Questions
- How does revenue trend over time (monthly/seasonally)?  
- Which days of the week generate the most revenue?  
- What time of day drives the highest sales?  
- Which products are top sellers?  
- Who are the highest-value customers?  
- Which countries contribute the most to total revenue?  
- What percentage of transactions are completed vs cancelled?  

## TOOLS & TECHNOLOGIES  
- Power BI Desktop  
- DAX Measures  
- Power Query (Data Cleaning & Transformation)  
- Interactive Slicers 
- Data Modeling (Star Schema approach)  

## POWER BI DATA PREPARATION & MODELING  
Power BI was used as the main tool for data transformation, modeling, and visualization.
### Key Steps Included:  
- Cleaned missing and inconsistent values  
- Converted **InvoiceDate** to proper Date/Time format  
- Created calculated columns for:
  - Year  
  - Month  
  - Day of Week  
  - Time of Day (Morning / Afternoon / Evening)  
- Created DAX measures:
  - `Total Revenue = Quantity × UnitPrice`  
  - `Total Orders`  
  - `Total Customers`  
  - `Average Order Value (AOV)`  

## DASHBOARD  
<img width="1340" height="745" alt="Ecommerce Dashboard" src="https://github.com/user-attachments/assets/2ef29aee-5b0a-479d-8410-5c8324c36b2d" />

## PROJECT INSIGHTS  

- Revenue shows a **clear upward trend over time**, indicating growth and seasonal spikes.  
- The **Afternoon time period** generates the highest revenue compared to Morning and Evening.  
- Certain **products dominate total sales**, making them core revenue drivers.  
- A small group of **high-value customers contributes significantly** to total revenue.  
- The **United Kingdom** accounts for the largest share of total revenue among all countries.  
- Over **98% of transactions are completed**, showing strong checkout success with low cancellation risk.  
- The dashboard enables fast comparison across **time, geography, and customer segments**.

---

## CONCLUSION & BUSINESS IMPROVEMENT SUMMARY (RECOMMENDATIONS)

To improve e-commerce performance, the business should:
- Focus marketing efforts on **peak sales times (Afternoons & high-revenue days)**  
- Prioritize inventory for **top-selling products and key countries**  
- Create loyalty strategies for **high-value customers**  
- Monitor cancellations and improve checkout experience to sustain high completion rates  

This Power BI dashboard provides a strong foundation for **data-driven growth**, operational efficiency, and strategic planning in an e-commerce environment.
