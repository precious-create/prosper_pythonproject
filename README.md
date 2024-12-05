# prosper_python_project
The Prosper Loan dataset gives comprehensive details concerning the loans of the instituitions and its customers, including their characetristics as part of the financial lending platform's operations. this data properly captures the different dimensions of borrowers profiles, characteristics, credit details and it has been designed to give support to analysis related to status of the loans, creditworthiness, this makes it an ideal dataset for exploring the various factors that can influence loan decisions and outcomes.

# Data Assessing-
i will be assessing my data imported above using the programatic assessment. i will do these using three methods; Info() method to show me all the information , columns() to show me all the column names in the dataset, Describe() method to give me an aggregation of the numerical columns.

# Structure of the dataset - 
The dataset is a loan-related dataset that started off with 80 columns, through data cleaning by dropping unnecessary columns, it has been reduced to 63. these remaining columns give full details about the financial instituitions' borrowers, loan statuses, employment details and different calculated metrics. the dataset is made up of numerical, categorical and data-based data and will be used for both univariate and bivariate analysis.

# Main features of interest in the dataset
The main features that i am looking to analyze from this data set include;
Distribution of borrower APR
Distribution of income range
Employment status of borrowers
Percentage of borrowers who are also homeowners
Distribution of loan terms
what is the correlation between loan status and loan term?
the relationship between debt-to-income ratio and loan amount
Does the credit score range have any effect on loam amount given?
what is the average borrower APR by employment status?
what is the average loan amount by prosper rating?

# Features in the dataset that will support investigation into feature(s) of interest
There are several eatures within the dataset that will help our investigation and these include;
Loan original amount - this is the amount of the loan initially granted
loan status- current status of the loan
Borrower APR- this is the annual percentage rate (APR) for the borrower
Is Borrower home owner - whether borrower already owns a home
credit score range- this is the credit score range of the borrower
employment status- employment status of the borrower
income range- income range of the borrower
prosper rating - this is the creditworthiness rating assigned to the borrower
Debt to income ratio - this is the ratio of debt to income of the borrower
loan terms- duration in months of the loan

# Conclusions
# Key Findings
Borrower APR Distribution: The distribution of Borrower APR is right-skewed, which shows that most borrowers are charged moderate to high APRs, with fewer benefiting from lower rates. Borrowers with better Prosper Ratings enjoy more favorable APRs.

Income Range Distribution: A majority of borrowers fall into mid-income brackets. Borrowers with the lowest or unreported income ranges are less represented, which shows limited access to loans and lending practices for these groups.

Employment Status: Borrowers who are employed full-time constitute the majority, indicating that lenders prefer extending credit to borrowers with stable income sources. Unemployed and retired individuals have lower representation.

Homeownership: A higher percentage of borrowers are not homeowners, this suggests that Prosper loans might cater to individuals looking for financial flexibility rather than property-backed credit options.

Loan Terms: The 36-month term is the most common, followed by 60-month loans. Shorter terms may appeal to borrowers seeking quicker repayment, while longer terms cater to larger financial needs.

Loan Status by Term: Most loans are either current or fully paid, this shows a healthy loan repayment behavior. Longer-term loans tend to have a higher proportion of defaults in repayment, reflecting the added risk of extended repayment periods.

Debt-to-Income Ratio and Loan Amount: Borrowers with moderate debt-to-income ratios tend to secure larger loans. Extremely high ratios limit borrowing capacity, showing lender caution.

Credit Score and Loan Amount: Higher credit scores have a relationship with larger loan amounts, this highlights the importance of strong credit profiles in accessing greater financial resources.

Borrower APR and Employment Status: Borrowers with stable employment (full-time, part-time) receive lower APRs compared to unemployed borrowers, reflecting lender confidence in income stability.

Loan Original Amount and Prosper Rating: Borrowers with better Prosper Ratings secure significantly larger loans, this shows the role of creditworthiness in loan approvals.

# Insights
Creditworthiness Matters: Features like Prosper Ratings, credit scores, and debt-to-income ratios consistently show a strong influence on loan terms, amounts, and APRs.
Stable Income is Key: Employment status plays an important role in both loan access and affordability, with full-time employed borrowers havng the best benefits.
Risk Management: Lenders manage risk by limiting loans to high-risk borrowers (e.g., lower Prosper Ratings, high debt-to-income ratios) and adjusting APRs according to those features.

# Data Exploration and Outcomes
Data Cleaning: I addressed missing values, columns with excessive nulls were dropped, and data types were standardized into dates and numeric values.
Column(Feature) Selection: Irrelevant columns were dropped, and i focused on features most impactful for analysis.
Visualization: i performed a mix of univariate and bivariate analysis to uncover patterns, correlations, and trends.
The exploration provided insights into borrower behavior, lender preferences, and loan features and characteristics.
