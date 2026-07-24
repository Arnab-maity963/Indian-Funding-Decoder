# Indian-Funding-Decoder
# Project Overvies 
Indian-Startups-Funding-Analysis/
│
├── data/
│   └── indian_startups_funding.csv
│
├── notebooks/
│   └── startup_analysis.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── data_analysis.py
│   └── business_insights.py
│
├── outputs/
│   ├── cleaned_data.csv
│   ├── industry_summary.csv
│   ├── city_summary.csv
│   └── charts/
│
├── requirements.txt
├── README.md
└── LICENSE


This project analyzes a real-world dataset containing funding information for Indian startups. The dataset contains inconsistent city names, industry labels, funding stages, different date formats, duplicate records, and funding amounts stored as strings.

The project demonstrates a complete Data Analysis Pipeline, from cleaning raw data to generating business insights using Python and Pandas.

Objectives
Clean messy real-world startup funding data.
Standardize categorical values.
Convert data into proper formats.
Perform Exploratory Data Analysis (EDA).
Solve business-related analytical questions.
Generate useful insights for investors and founders.
Technologies Used
Python
Pandas
NumPy
Jupyter Notebook
Workflow
Step 1 — Data Loading
Load CSV file
Check dataset shape
Inspect missing values
Detect duplicate rows
Step 2 — Data Cleaning
Rename columns
Remove whitespace
Convert text to title case
Standardize city names
Standardize industries
Standardize funding stages
Convert funding amount to numeric
Convert dates to datetime
Remove duplicates
Step 3 — Data Exploration
Industry distribution
City distribution
Funding statistics
Funding year analysis
Step 4 — Data Filtering

Examples:

Bengaluru startups with funding >100 Cr
Fintech startups
Startups founded between 2015–2020
Startup names containing "pay"
Step 5 — Feature Engineering

New columns created:

funding_efficiency
funding_tier
investor_count
era
Step 6 — Aggregation

Business summaries using:

groupby()
agg()
value_counts()
crosstab()
Step 7 — Business Insights

Examples:

Which city receives the highest funding?
Which industry has the highest average investment?
Which startups are emerging unicorns?
Which city–industry combinations are most competitive?
What does this project actually do?

Imagine you're working for a venture capital (VC) firm.

Every day, thousands of startups receive funding.

The raw data is messy and difficult to understand.

This project transforms that messy data into meaningful information that helps investors answer questions like:

Which industries are growing the fastest?
Which cities attract the most investment?
Which startups are likely future unicorns?
Where is competition highest?
Which sectors should investors focus on?
Real-world Applications

This project can be used by:

Venture Capital firms
Angel Investors
Startup Founders
Business Analysts
Market Researchers
Investment Companies
Skills Demonstrated
Data Cleaning
Data Wrangling
Exploratory Data Analysis (EDA)
Feature Engineering
Data Aggregation
Business Intelligence
Pandas Programming
Python
Final Outcome

The project converts raw startup funding records into clean, structured data and generates actionable business insights that support investment and strategic decision-making.
