# E-Commerce-clients-clustering

## 📚 Project Overview
This project explores the **Online Retail II dataset**, which contains transactions from a UK-based non-store online retail business between **December 1, 2009, and December 9, 2011**. The company specializes in unique all-occasion giftware, and many customers are wholesalers.  
Through this analysis, we aim to uncover insights into customer behavior, predict future demand, and develop strategies to enhance business performance.

---

## 🎯 Objectives
1. **Exploratory Data Analysis (EDA)**:
   - Understand customer purchasing patterns and sales trends.
   - Identify seasonality, top-performing products, and high-value customers.

2. **Customer Segmentation**:
   - Segment customers using RFM (Recency, Frequency, Monetary) analysis.
   - Define actionable customer groups and recommend tailored strategies.

---

## 📊 Dataset Description
The **Online Retail II dataset** contains:
- **Invoice**: Transaction identifier.
- **StockCode**: Product code.
- **Description**: Product description.
- **Quantity**: Number of items purchased.
- **InvoiceDate**: Date and time of the transaction.
- **Price**: Unit price in GBP.
- **Customer ID**: Unique customer identifier (nullable for some rows).
- **Country**: Customer's country.
- **SalesTotal**: Calculated as `Quantity * Price`.

---

## 🛠️ Methods and Techniques
### 1. **Exploratory Data Analysis**
   - Time-series analysis of monthly, seasonal, and daily sales trends.
   - Identification of top-performing products and customer segments.
   - Analysis of outliers in sales and demand.

### 2. **Customer Segmentation**
   - Clustering customers based on RFM analysis:
     - **Recency**: Days since the last purchase.
     - **Frequency**: Number of purchases.
     - **Monetary**: Total spending.
   - Actionable customer groups:
     - **New Shoppers**: Recent, infrequent buyers.
     - **Loyal Customers**: Regular, high-value purchasers.
     - **Re-engage**: Previously active customers with reduced activity.
     - **Upsell**: Frequent buyers with low average spending.
     - **Delight**: High-frequency, high-spending VIPs.

### 3. **Demand Prediction**
   - Target: Predict the `Quantity` of items sold.
   - Features: Price, time-based features (month, day), and product-level attributes.
   - Models: Linear regression and Random Forest Regressor.

### 4. **Customer Behavior Prediction**
   - Target: Predict customer `SalesTotal`.
   - Features: Aggregated metrics like total spending, recency, and frequency.

### 5. **Visualization**
   - Temporal trends and sales seasonality.
   - Predicted vs. actual sales and demand.
   - Residual analysis and customer segmentation plots.

---

## 🔧 Tools and Technologies
- **Programming**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **Notebook**: Jupyter for running the analyses and models.

---

## 📈 Key Results
1. **Customer Segmentation**:
   - Identified actionable customer segments with clear strategies for each group.
2. **Demand Prediction**:
   - Successfully predicted item demand to improve inventory management.
3. **Customer Spending**:
   - Modeled and forecasted customer spending patterns, providing actionable insights for marketing and retention.

---
