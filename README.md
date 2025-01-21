# Online Retail II Dataset Analysis

## Project Overview
This project involves the analysis and exploration of the **Online Retail II** dataset, which contains transactional data from a UK-based online retailer. The retailer specializes in unique all-occasion giftware and primarily serves both individual customers and wholesalers. The dataset spans transactions from **December 1, 2009, to December 9, 2011**.

The goal is to analyze customer data, group clients into meaningful segments, and suggest tailored business strategies for each group. The project uses K-Means clustering for segmentation and handles outliers as a separate category.
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

### Workflow
1. **Data Cleaning**:
   - Handled missing values, errors, and inconsistencies in invoice and stock codes.
   - Removed irrelevant records using regex and excluded rows with missing `Customer ID`.

2. **Outlier Analysis**:
   - Identified and separated high-value clients for specific analysis.

3. **Clustering**:
   - Applied K-Means clustering to non-outlier data and validated with the silhouette score.
   - Labeled clusters: **New Shoppers**, **Re-engage**, and **Reward**.

4. **Outlier Segmentation**:
   - Grouped high-value clients manually and suggested tailored strategies.

5. **Visualization**:
   - Displayed client group distributions and key segmentation metrics.

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
