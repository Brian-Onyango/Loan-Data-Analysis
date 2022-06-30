# Loan Data from Prosper Data Exploration
## by Brian Onyango


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. A more detailed description of the data set can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

The dataset can be found from this link:
* [Dataset](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)

The following Steps were Used in Data Preparation:

* Reading the Data
* Checking the Data
* Data Validation
* Checking for Completeness
* Checking for Consistency
* Checking for Uniformity
* Checking for Outliers
* Checking for Anomalies

Analysis Steps

* Univariate Exploration: Categorical Analysis and Numerical Analysis
* Bivariate Exploration
* Multivariate Exploration


## Summary of Findings

> Summary of the Findings:

* Majority of the Loans are Current (>50000), followed by Completed (>30000) and Chargedoff (>10000) caps off top three.
* CA (California) has the highest number of borrowers whereas ND (Nevada) has the least number of borrowers.
* Eliminating the "Other" and "Proffesional" categories (undefined), majority of the borrowers are Computer Programmers, followed by Executives then Teachers. The least borrowers are Student- Technical School.
* Majority of the borrowers are Employed. Full-time employees makes the biggest percentage of the employed borrowes. At the bottom, the Retired tends to borrow less.
* Majority of the borrowers takes loans to settle Debts while the least amount of debt are taken for RV
* The average amount of theh loan given to the borrowers is 8587.75 and the average monthly income of the borrowers is 5694.34
* Monthly loan payment is positively correlated to loan original amount.
* Loan original amount is positively correlated to Term of loans duration.
* Stated monthly income is positively correlated to loan original amount
* Stated monthly income is positively correlated to monthly loan payment
* Number of Investors is positively correlated to Loan original amount.
* Number of Investors is positively correlated to monthly loan payment.
* As much as the monthly loan paymnet is positively correlated to the loan original amount, it is interesting to note that there is a variance as per the steepness of the correlation. Loans with term limits of 12 tends to get lower loan original amount with a higher repayment amount compared to long term loans (60 months) which has a higher loan original amount with a lower monthly repayment amount.



## Key Insights for Presentation

> In Conclusion;


From this analysis, we can conclude that:

* Majority of the borrowers are from CA (California)
* Majority of the borrowers are Computer Programers
* Majority of the borrowers are Employed
* Majority of the borrowers are taking loans for Debt Consolidation
* The median term for loans is 36 months
* Majority of the borrowers are home owners
* The average monthly income of the borrowers is 5694.34
* The average amount of the loan given to the borrowers is 8587.75
* The average monthly loan repayment is 279.58
From the above insights, we can therefore profile an ideal candidate for a loan as:

An employed Computer Programer from Californian who owns a home and has debts to consolidate and earns a monthly salary of $5694.34.
