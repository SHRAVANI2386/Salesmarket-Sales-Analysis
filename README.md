Supermarket Sales Analysis
This project explores a supermarket sales dataset using Python to understand sales patterns, customer behavior, product performance, and payment trends through exploratory data analysis and visualization. The dataset is widely used for analysis practice and contains transaction records from three supermarket branches over a three-month period.

Objective
The objective of this project is to perform Exploratory Data Analysis (EDA) on supermarket sales data and extract meaningful business insights from transaction-level records. The analysis focuses on revenue trends, branch performance, product line performance, customer segments, payment methods, and ratings.

Dataset
Dataset name: Supermarket Sales Dataset

Source: 
Kaggle Supermarket Sales Dataset

The dataset contains supermarket transaction details including branch, city, customer type, product line, quantity, payment method, revenue, gross income, and rating.

Columns Used
The main columns used in this project are:

invoice_id

branch

city

customer_type

gender_customer

product_line

unit_cost

quantity

5pct_markup

revenue

date

time

payment_method

cogs

gm_pct

gross_income

rating

month

day

These columns were used after cleaning and renaming for easier analysis in Python.

Tools and Libraries
This project was completed using:

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Analysis Performed
The following analysis was carried out in this project:

Data loading and inspection

Data cleaning and column renaming

Revenue analysis by branch

Revenue analysis by city

Revenue analysis by product line

Payment method distribution

Revenue analysis by customer gender

Revenue trends by day and month

Customer rating analysis

Key Insights
Some of the major insights from the analysis include:

Revenue varies across branches and cities, showing differences in store performance.

Some product lines contribute more revenue than others, helping identify strong-performing categories.

Payment methods show customer preference patterns during transactions.

Customer ratings help evaluate shopping experience and satisfaction levels.

Daily or monthly revenue trends reveal changes in shopping behavior over time.

Project Structure
text
Supermarket-Sales-Analysis/
│
├── data/
│   └── supermarket_sales.csv
├── notebooks/
│   └── supermarket_sales_analysis.ipynb
├── images/
│   └── charts/
├── README.md
├── requirements.txt
└── .gitignore
How to Run
Clone this repository.

Open the project folder in Jupyter Notebook or VS Code.

Install the required libraries:

bash
pip install -r requirements.txt
Place the dataset file inside the project folder.

Open the notebook and run all cells.

Sample Visualizations
This project includes visualizations for:

Payment Method Distribution

Total Revenue by Branch

Total Revenue by City

Total Revenue by Product Line

Revenue by Gender

Revenue by Day

Rating Distribution

Conclusion
This project provides a clear overview of supermarket transaction data through visualization and EDA. It helps identify revenue-driving branches, popular product lines, customer preferences, and operational patterns that can support better business decisions.

Author
Shravani

