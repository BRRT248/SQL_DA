# SQL Data Analysis – Fintech Transactions

This project explores a synthetic financial transactions database using SQL queries and Python visualizations. It demonstrates how SQL and Python can be combined for data analysis.

## Dataset

A SQLite database (`transactions.db`) containing a `transactions` table with:
- `transaction_id`: Unique transaction ID
- `customer_id`: Customer identifier
- `amount`: Transaction amount in dollars
- `transaction_date`: Date of the transaction
- `category`: Transaction type (deposit, withdrawal, payment, refund)

## Workflow

- Queried total transaction amount per category
- Identified top 5 customers by average transaction amount
- Calculated daily total transaction amounts
- Visualized results using bar and line plots

## Key Visualizations

- Bar chart: Total transaction amount per category
- Line chart: Daily transaction totals over time (including missing dates filled with 0)

## Tools Used

- SQLite
- SQL
- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## Next Steps

- Explore seasonal patterns or weekly trends
- Join with customer demographic data for deeper analysis
- Build a dashboard to display these insights
