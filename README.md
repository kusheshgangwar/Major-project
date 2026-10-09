# Major_project

# 🛍️ Retail Store Analytics

## Technology Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Streamlit
- OpenPyXL

## Modules
1. Executive Dashboard
2. Store Performance
3. Product Analytics
4. Customer Analytics
5. Inventory
6. Discount Analysis
7. Seasonal Sales
8. Profitability
9. Store Comparison
10. EDA & Correlation
11. ML Sales Prediction

## Dataset
The included dataset contains 5,000 transactions, 5 stores, 20 products,
1,200 customers and 35 columns covering sales, discounts, costs, profits,
inventory, customers, stores and seasonal features.

## Run the project

Open a terminal in this folder:

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Project presentation points

### Problem
Retail businesses generate large amounts of transaction data. Manual analysis
makes it difficult to identify high-performing stores, products, customer
segments, inventory risks, discount effects, seasonal patterns and profitability.

### Objective
Build an interactive analytics system that converts retail transaction data
into KPIs, visual insights, comparisons and a machine-learning sales forecast.

### ML
Random Forest Regression is used for daily sales prediction. The dashboard
reports MAE, RMSE and R² and shows a 30-day forecast.

### Note
The dataset is synthetic and intended for academic/demo use.
