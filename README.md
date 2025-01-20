# Online Retail II Dataset Analysis

## Project Overview
This project involves the analysis and exploration of the **Online Retail II** dataset, which contains transactional data from a UK-based online retailer. The retailer specializes in unique all-occasion giftware and primarily serves both individual customers and wholesalers. The dataset spans transactions from **December 1, 2009, to December 9, 2011**.

The goal of this project is to clean, explore, and analyze the data to uncover insights about customer behavior trough customer segmentation techniques.

---

## Dataset Description
The dataset includes the following fields:
- **InvoiceNo**: Unique number assigned to each transaction. If it starts with "C," it indicates a cancellation.
- **StockCode**: Unique identifier for each product.
- **Description**: Product name.
- **Quantity**: The number of units of the product sold (can be negative for returns).
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit of the product (in GBP).
- **CustomerID**: Unique identifier for each customer (missing for some transactions).
- **Country**: The country where the customer resides.

---

## Project Goals
1. **Data Cleaning**:
   - Handle missing values in the `CustomerID` field.
   - Remove transactions with negative `Quantity` or `UnitPrice` values.
2. **Exploratory Data Analysis (EDA)**:
   - Analyze sales trends across time.
   - Identify top-performing products and countries.
3. **Visualization**:
   - Create informative visualizations for insights.
4. **Feature Engineering**:
   - Add calculated fields like `TotalPrice` (Quantity × UnitPrice).
5. **Customer Segmentation**:
   - Perform **RFM Analysis** to segment customers:
     - **Recency**: Days since the last purchase.
     - **Frequency**: Number of transactions.
     - **Monetary**: Total spending.

---

## Tools and Libraries Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: Data manipulation.
  - `numpy`: Numerical computations.
  - `matplotlib` and `seaborn`: Data visualization.
  -  `scikit-learn`: Clustering

---

## Acknowledgments
The dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). Special thanks to the contributors for making this dataset publicly available.
