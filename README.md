**🏦 Bank Transaction Monitoring System**

**📘 Overview**

The Bank Transaction Monitoring System is a Python and SQL-based project designed to simulate and analyze core banking operations such as customer management, account linking, and transaction tracking.
This project focuses on building a relational database for a bank and executing SQL queries through Python to perform real-time transaction analysis, detect anomalies, and generate meaningful insights.

The system integrates SQLite3 for database operations and Pandas with Tabulate for displaying and analyzing data in a structured, readable format using Google Colab.


**🚀 Key Features**

🧾 Customer and Account Management:
Create and maintain detailed customer profiles and associated bank accounts.

💳 Linked Account Relationship Tracking:
Connect and monitor relationships between primary accounts, savings accounts, and credit cards.

💰 Transaction Management:
Record, track, and analyze deposits, withdrawals, and online transactions.

📊 SQL Query-Based Analytics:
Execute advanced SQL operations such as joins, aggregates, and subqueries to analyze banking data.

🧠 Automated Data Retrieval with Python:
Integrate Python scripts to run parameterized SQL queries and visualize results in tabular format.

🧩 Error Handling and Data Integrity:
Use COALESCE, GROUP BY, and LEFT JOIN for clean data analysis and NULL-safe reporting.


**🛠️ Technologies Used**

Programming Language: Python

Database: SQLite3

Libraries: Pandas, Tabulate

Environment: Google Colab / Jupyter Notebook

Concepts: SQL Joins, Aggregations, Subqueries, COALESCE, Data Normalization


**📂 Database Design**

The project contains the following key tables:

**Table Name	Description**
BANK_CUST	Stores customer information
BANK_ACCOU	Maintains account details and balances
BANK_ACC_TRAN	Tracks all transactions and amounts
Bank_Account_Relationship_Details	Links primary, savings, and credit card accounts
BANK_CUSTOMER_MSG	Contains customer event messages
BANK_INTEREST_RATE	Stores interest rate information for account types


**🧮 Sample Queries Implemented**

Average balance maintained by each customer

Savings accounts linked with credit cards

Quarterly transaction analysis (Q1, Q2, etc.)

Exclusion of specific month transactions (e.g., March 2020)

Total balance deduction based on debit transactions

Relationship-wise balance and transaction summaries


**🧰 Setup Instructions**

Clone this repository:

git clone https://github.com/<your-username>/Bank-Transaction-Monitoring-System.git


Open the project in Google Colab or Jupyter Notebook.

Install dependencies:

pip install pandas tabulate

Run the Python file or notebook cells sequentially.

Check the database output in tabulated format.



**📈 Future Enhancements**

Add a GUI interface using Tkinter or Streamlit.

Integrate machine learning for fraud detection and behavior analytics.

Enable CSV import/export for transaction logs.

Visualize trends using Matplotlib or Power BI.
