E-Commerce Data Analysis (PostgreSQL, Pandas, Jupyter Notebook)
Overview
This project explores e-commerce sales data from Kaggle, spanning April 2018 to March 2019. We use Python, Pandas, Jupyter Lab, and PostgreSQL to dig into what sells, which regions perform best, and how close sales came to monthly targets.

Dataset
Order Details.csv: Order ID, Amount, Profit, Quantity, Category, Sub-Category

List of Orders.csv: Order ID, Order Date, CustomerName, State, City

Sales Target.csv: Month of Order Date, Category, Target

All data is available from:
https://www.kaggle.com/datasets/benroshan/ecommerce-data?select=Sales+target.csv

What We Did
Cleaned and imported the CSV data using pandas (handled blanks, fixed date formats, and removed duplicates), then stored the results in PostgreSQL tables.

Wrote and ran SQL queries for key business questions:

Sales and profit by category/sub-category: Groups products to find out which are top-sellers or loss-makers.

Sales targets vs. actual performance: Compares what was sold each month, in each category, to what was forecasted, calculating achievement ratios and gaps.

Top customers, cities, and states: Ranks where most sales came from and who made the biggest purchases by joining orders with sales details.

Monthly and yearly trend analysis: Tracks how sales totals and profits changed over time.

Regional breakdown by category: Looks at which states perform best for particular kinds of products and visualizes these as heatmaps.

Used the results to build a series of graphs:

Bar charts (top states, customers, profit by category)

Line and scatter plots (sales trends, profit vs. quantity)

Pie charts (sub-category share)

Heatmaps (for comparing performance across categories and regions)

Getting Started
Clone the repository:

bash
git clone https://github.com/pramodkumarpodila-source/E-Commerce-Data-Analysis-PostgreSQL-psycopg2-and-JupyterLab.git
Install requirements:
Python, Jupyter Notebook or Lab, Pandas, Matplotlib, Seaborn, Psycopg2, and PostgreSQL

Download the Kaggle CSV files into your repo folder

Open and run the notebook:
Open the file named

text
analysis.ipynb
using Jupyter Notebook or Jupyter Lab.

Run each cell in order. The notebook will prompt you for database info and walk you through creating tables, importing data, analyzing results, and building all visualizations step by step.

Team
Sai Pramod, Genny, Majid

License
Public Domain
Feel free to use, share, or modify any part of this project.