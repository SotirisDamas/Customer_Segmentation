# Customer Segmentation using RFM Analysis and K-Means Clustering

## Project Overview
This project focuses on segmenting customers based on their purchasing behavior to gain actionable insights and optimize marketing strategies. By leveraging **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering**, we identified distinct customer segments, each with unique characteristics. 

These insights enable data-driven decision-making for:
- Personalized marketing campaigns
- Customer retention
- Revenue growth

---
# **[Online Retail Dataset](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset/data)**

This dataset contains transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered online retailer. Below is the description of the columns in the dataset:

- **InvoiceNo**: 
  - Invoice number. 
  - *Nominal*, a 6-digit integral number uniquely assigned to each transaction.
  - If this code starts with the letter `'C'`, it indicates a **cancellation**.

- **StockCode**: 
  - Product (item) code. 
  - *Nominal*, a 5-digit integral number uniquely assigned to each distinct product.

- **Description**: 
  - Product (item) name. 
  - *Nominal*.

- **Quantity**: 
  - The quantities of each product (item) per transaction. 
  - *Numeric*.

- **InvoiceDate**: 
  - Invoice date and time. 
  - *Numeric*, the day and time when each transaction was generated.

- **UnitPrice**: 
  - Unit price. 
  - *Numeric*, product price per unit in sterling.

- **CustomerID**: 
  - Customer number. 
  - *Nominal*, a 5-digit integral number uniquely assigned to each customer.

- **Country**: 
  - Country name. 
  - *Nominal*, the name of the country where each customer resides.
