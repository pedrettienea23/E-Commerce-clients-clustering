# Online Retail II Dataset Analysis

## Project Overview
This project involves the analysis and exploration of the **Online Retail II** dataset, which contains transactional data from a UK-based online retailer. The retailer specializes in unique all-occasion giftware and primarily serves both individual customers and wholesalers. The dataset spans transactions from **December 1, 2009, to December 9, 2011**.

The goal of this project is to clean, explore, and analyze the data to uncover insights about customer behavior, sales trends, and business performance. Additionally, customer segmentation techniques are applied to derive actionable insights for business strategies.

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

## Key Insights
1. **Sales Concentration**:
   - The majority of sales occur in the UK.
   - Wholesalers are a significant customer base.
2. **Seasonal Trends**:
   - Monthly sales exhibit seasonality, with peaks during specific months.
3. **Customer Behavior**:
   - A small group of loyal customers contributes significantly to revenue.
4. **Product Performance**:
   - Certain products drive the majority of sales.

---

## Tools and Libraries Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: Data manipulation.
  - `numpy`: Numerical computations.
  - `matplotlib` and `seaborn`: Data visualization.

---

## Visualizations
The project includes visualizations such as:
- Bar charts showing top countries by sales.
- Line charts displaying monthly sales trends.
- Histograms of customer purchase distributions.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-retail-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the analysis:
   ```bash
   jupyter notebook Online_Retail_Analysis.ipynb
   ```

---

## Future Work
- Investigate reasons for returns and negative values in transactions.
- Implement machine learning techniques for advanced customer segmentation.
- Explore sales forecasting models using time-series analysis.

---

## Acknowledgments
The dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). Special thanks to the contributors for making this dataset publicly available.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to contribute to the project or suggest improvements by opening an issue or submitting a pull request!
