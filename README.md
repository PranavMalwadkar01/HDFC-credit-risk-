This project demonstrates a complete risk analytics workflow using Python and Tableau to analyze synthetic HDFC retail loan data. The goal is to identify customer risk patterns, understand default behavior, and create an interactive dashboard that reflects real-world banking risk analytics.

🚀 Project Overview

The project covers:

Data cleaning and preprocessing in Python

Feature engineering (credit buckets, high utilization flags, ratios)

Building multiple Tableau visualizations

Creating a fully interactive dashboard with filters

Extracting actionable insights and recommendations

This project simulates how credit risk teams at banks (HDFC, JPMC, ICICI) analyze loan portfolios.

📁 Dataset Summary

Synthetic dataset of 1,200 customers, containing:

Customer ID

Region & Branch

Income

Loan Amount

Credit Score

Utilization Ratio

High Utilization Flag

Credit Score Bucket

Default Flag

Python was used to engineer features like:

credit_bucket (score ranges)

high_util (utilization > 65%)

income_to_loan ratio

📊 Visualizations Included
1. Default Rate by Region

Shows average default trends across cities such as Mumbai, Delhi, Pune, Bengaluru, Chennai.

2. Branch Performance

Identifies high-risk branches (e.g., HDFC-M2) with elevated default percentages.

3. Credit Score × Utilization Segmentation

Most important visualization — highlights how both credit score and utilization jointly influence default risk.

4. Income vs Loan Amount Scatterplot

Shows borrower behavior patterns; defaulters cluster in mid-income and mid-loan segments.

5. Credit Score Distribution with Default Overlay

Displays how defaulters are concentrated in 580–640 credit score bins.

🎨 Dashboard Features

Interactive Tableau Dashboard includes filters for:

Region

Branch

Credit Score Bucket

High Util Flag

Default Status

All filters update every sheet using Apply to Worksheets → All Using This Data Source.
