# Credit-Risk-EDA
Exploratory Data Analysis (EDA) on banking loan data to identify high-risk applicant profiles and default patterns using Python

#Credit Risk & Loan Default Analysis

#Project Overview
This project performs an Exploratory Data Analysis (EDA) on banking loan data to identify behavioral patterns that distinguish between loan defaulters and non-defaulters. The goal was to uncover key risk indicators that allow financial institutions to make more informed, data-backed lending decisions.

#Business Problem
Loan providers face a critical balancing act: minimizing losses from defaulters while maximizing revenue from capable applicants. This analysis focuses on identifying high-risk segments to reduce financial loss and prevent the rejection of creditworthy customers.

#Key Insights & Findings
Default Risk: Approximately 9% of loan applicants demonstrate payment difficulties.

Demographic Patterns: Applicants aged 35–45 make up the largest user segment. Interestingly, while secondary education holders apply most frequently, those with Higher Education demonstrate a significantly lower default rate (5% vs. 10% for other groups).

Occupation Risk: The top five occupations (Laborers, Sales Staff, Core Staff, Managers, Drivers) account for 72% of all loan applications, highlighting a concentrated risk profile.

Loan Behavior: Cash and Consumer loans dominate the market (89% combined), while Revolving loans see limited adoption (12%).

#Methodology
Data Cleaning: Handled missing values using a 40% threshold to ensure data integrity before analysis.

Exploratory Analysis: Conducted Univariate, Bivariate, and Multivariate analysis to map relationships between customer attributes (income, age, education) and loan outcomes.

Correlation Mapping: Utilized heatmaps to identify strong correlations between variables like AMT_CREDIT, AMT_GOODS_PRICE, and DAYS_EMPLOYED.

Tools Used: Python (Pandas, NumPy, Matplotlib, Seaborn).

#Conclusion
The analysis provides actionable segments for credit teams to refine their risk models. By focusing on specific education levels and occupation types, firms can adjust their approval strategies to minimize exposure to high-risk applicants while maintaining steady revenue flow.
