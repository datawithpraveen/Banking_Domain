📊 Banking Risk Analytics Dashboard in Power BI
Welcome to the Banking Risk Analytics Dashboard project! This repository demonstrates how a data analyst can leverage data from banking and financial services to identify risks and make data-driven decisions—ultimately helping to minimize the risk of loan defaults and improve lending strategies.

🧠 Problem Statement
Objective: Develop a basic understanding of risk analytics in the banking and financial services sector and explore how data can be utilized to reduce the risk of financial loss during customer lending.

This project focuses on exploring and analyzing real-world banking data to identify meaningful insights that help risk analysts and financial decision-makers take proactive steps.

📁 Project Structure
.
├── data/
│   └── *.csv                 # Banking datasets used for analysis
├── notebooks/
│   └── EDA.ipynb             # Jupyter Notebook with full EDA process
├── dashboard/
│   └── PowerBI.pbix          # Power BI dashboard file
├── README.md                 # Project documentation (this file)

🔍 Exploratory Data Analysis (EDA)
Performed in Jupyter Notebook, the EDA involved:

📌 Univariate Analysis: Distribution of key variables (e.g. loan amount, income, deposits)

📌 Numerical Summary Statistics

📌 Bivariate Analysis: Comparison between loan status and financial behaviors

📌 Heatmap Correlation Matrix: Understanding interrelationships among numerical features

✅ Key Insight
Strongest positive correlation was found between:

Bank Deposits and Checking Accounts

Bank Deposits and Foreign Currency Accounts

This suggests that customers maintaining high balances in one account type often have substantial funds across multiple accounts, indicating lower credit risk.

🗄️ Data Source
Raw CSV files containing customer-level banking information

Connected to MySQL for structured querying and integration with Power BI

📊 Dashboard Overview (Power BI)
The final Power BI dashboard is structured into four pages, each focusing on different aspects of banking operations and risk:

🏠 Home Page: Overview of KPIs and business summary

💸 Loan Analysis: Visual insights into loan amounts, approval rates, risk segments

🏦 Deposit Analysis: Patterns in deposit types and account behavior

📈 Summary: Final takeaways, correlations, and customer segmentation

⚙️ Tools & Technologies
📘 Jupyter Notebook – for data cleaning, EDA, and visualization

🐬 MySQL – for relational data handling and integration

📊 Power BI – for dashboard development and storytelling

🐍 Python (Pandas, Matplotlib, Seaborn) – for EDA and plots




📊 Visualization: Histograms, box plots, correlation heatmaps, and bar charts
