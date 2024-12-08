# Retail Sales Analysis Project

## Overview
The **Retail Sales Analysis Project** explores customer purchasing behaviors and sales trends to provide actionable insights for business improvement. The analysis focuses on transaction data to highlight customer segmentation, sales patterns, and key metrics.

---

## Key Objectives
- Understand sales trends over time.
- Perform RFM (Recency, Frequency, and Monetary) analysis for customer segmentation.
- Analyze category and gender-based purchasing patterns.
- Provide actionable recommendations for business growth.

---

## Dataset Description
The dataset contains the following columns:
- `transaction_id`: Unique identifier for each transaction.
- `sale_date`: The date of the transaction.
- `sale_time`: The time of the transaction.
- `customer_id`: Unique identifier for customers.
- `gender`: Gender of the customer.
- `age`: Age of the customer.
- `category`: Product category purchased.
- `quantity`: Quantity of items purchased.
- `price_per_unit`: Price per unit of the product.
- `COGS`: Cost of Goods Sold.
- `total_sale`: Total sale amount for each transaction.

---

## Key Insights
- **Top-performing categories**: Clothing showed the highest customer visits across all genders, with electronics trailing closely.
- **Gender-based analysis**: Both genders exhibit similar interest in electronics and clothing; however, females had higher activity in beauty products.
- **RFM Analysis**:
  - Cluster 1 (High-value customers): Small segment but highly frequent and profitable.
  - Cluster 3 (Low-value customers): Largest group but low monetary and frequency values.
- **Sales Trends**: Sales significantly increase in the final quarter, indicating seasonal trends.
- **Top Customers**:
  - By total spending: Customer 3 leads with a total expenditure of $38,440.
  - By average spending: Customer 34 tops with an average transaction value of $1,366.

---

## Tools and Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

---

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```

2. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

4. Run the analysis in the notebook `Retail_Sales_Analysis.ipynb`.

