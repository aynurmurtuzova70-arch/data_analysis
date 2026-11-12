# Online Retail Analysis

This notebook explores an online retail sales dataset and performs a small business-intelligence style analysis using Python, pandas, and matplotlib.

## Project purpose

The analysis focuses on understanding:

- sales volume and revenue trends over time
- customer purchasing patterns
- top-selling products and countries
- order and pricing behavior
- key business insights from transaction-level data

## Dataset

The notebook expects a file named `04_online_retail.csv` in the same directory as the notebook.

It loads the CSV with `latin-1` encoding and analyzes transaction records such as:

- `Quantity`
- `UnitPrice`
- `CustomerID`
- `Country`
- `InvoiceNo`
- derived fields like `TotalPrice`, `invoice_year`, `invoice_month`, and `invoice_weekday`

## Notebook workflow

The notebook includes steps for:

1. Loading the retail dataset
2. Cleaning incomplete records (`CustomerID` nulls)
3. Calculating `TotalPrice` for each transaction
4. Identifying return items and negative quantities
5. Finding top countries, customers, and products by sales volume/revenue
6. Analyzing monthly and yearly revenue patterns
7. Visualizing business trends and distribution relationships with charts

## Required dependencies

Install the following packages before running the notebook:

```bash
pip install pandas matplotlib jupyter
```

## Run the notebook

From the project folder:

```bash
jupyter notebook online_retail_analysis.ipynb
```

## Notes

- The notebook is designed for exploratory data analysis rather than production-ready reporting.
- Some plots and labels are in Turkish, reflecting the original notebook context.
- Data quality checks and business assumptions should be reviewed before using the findings for operational decisions.
