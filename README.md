# Retail Store Analytics

## 1. Project Overview

Retail Store Analytics is a Python-based data analytics project that analyzes retail business data to identify sales trends, customer behavior, product performance, inventory status, discount effectiveness, and profitability.

The project generates data visualizations, business insights, and downloadable Excel reports to support data-driven decision-making.

## 2. Project Objectives

- Analyze store-wise sales and performance.
- Identify top-selling products and categories.
- Understand customer purchasing patterns.
- Monitor inventory and stock levels.
- Evaluate the impact of discounts on sales and profit.
- Analyze monthly, quarterly, and seasonal sales trends.
- Calculate profitability and profit margins.
- Compare the performance of different stores.
- Perform exploratory data analysis (EDA).
- Analyze relationships between numerical variables.
- Generate charts and Excel reports.

## 3. Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **OpenPyXL** — Excel report generation

## 4. Project Modules

1. Store Performance Analysis
2. Product Analytics
3. Customer Analytics
4. Inventory Analysis
5. Discount Analysis
6. Seasonal Sales Analysis
7. Profitability Analysis
8. Store Comparison
9. Exploratory Data Analysis
10. Correlation Analysis
11. Payment Method Analysis
12. Day-wise Sales Analysis

## 5. Project Structure

```text
Retail_Store_Analytics/
│
├── retail_store_analytics.py
├── requirements.txt
├── README.md
│
├── data/
│   └── retail_store_analytics_complete_dataset.csv
│
└── outputs/
    ├── Sales and Profit Charts
    ├── Product and Customer Charts
    ├── Inventory and Discount Charts
    ├── Seasonal Analysis Charts
    ├── Correlation Heatmap
    └── Retail_Store_Analytics_Report.xlsx
```

## 6. Dataset Description

The dataset contains retail transaction details, store information, customer demographics, product information, sales, costs, discounts, inventory, and seasonal attributes.

Key columns include:

- Transaction ID
- Date
- Store ID and Store Name
- City and State
- Customer ID, Gender, and Age
- Product ID, Product Name, and Product Category
- Quantity and Price per Unit
- Gross Sales and Total Amount
- Discount Percentage and Discount Amount
- Total Cost, Profit, and Profit Margin
- Opening Stock and Stock After Sale
- Reorder Level and Stock Status
- Year, Month, Quarter, Season, and Payment Method

## 7. Installation and Setup

### Step 1: Install Python

Install Python and verify the installation:

```bash
python --version
```

On Windows, you can also run:

```bash
py --version
```

### Step 2: Open the Project Folder

Open the project directory in VS Code or your terminal.

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

If required, use this command on Windows:

```bash
py -m pip install -r requirements.txt
```

### Step 4: Run the Project

```bash
python retail_store_analytics.py
```

On Windows:

```bash
py retail_store_analytics.py
```

## 8. Generated Outputs

After successful execution, the project saves visualizations and an Excel report in the `outputs/` directory.

Expected outputs include:

- Store-wise sales and profit analysis
- Top-selling products analysis
- Product category sales analysis
- Customer gender and age-group analysis
- Inventory status visualization
- Discount versus sales and profit analysis
- Monthly and seasonal sales trends
- Category-wise profitability
- Store comparison charts
- Payment method analysis
- Day-wise sales analysis
- Correlation heatmap
- Excel report containing analytical results

## 9. Business Applications

This project helps businesses:

- Identify high-performing stores and products.
- Understand customer purchasing behavior.
- Monitor inventory and stock availability.
- Evaluate discount strategies.
- Identify seasonal demand patterns.
- Analyze business profitability.
- Make informed business decisions using data.

## 10. Troubleshooting

**ModuleNotFoundError:** Install the required libraries using `pip install -r requirements.txt`.

**FileNotFoundError:** Verify that the dataset exists in the `data/` directory and that its filename matches the Python code.

**KeyError:** Check whether the dataset column names match those expected by the script.

**Missing outputs:** Review terminal errors and verify that the program can write files to the project directory.

## 11. Conclusion

Retail Store Analytics demonstrates the practical application of Python in retail data analysis. It converts raw transaction data into useful insights through sales analysis, customer analytics, inventory monitoring, discount evaluation, seasonal analysis, and profitability reporting.

The project showcases essential data analytics skills, including data preprocessing, exploratory data analysis, visualization, and report generation.

## 12. Project Information

- **Project Name:** Retail Store Analytics
- **Domain:** Data Analytics
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, OpenPyXL
- **Output:** Data visualizations and Excel reports
