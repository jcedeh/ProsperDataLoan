# ProsperDataLoan
## by Edeh, Chinonso James


## Dataset

> This dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), curent loan status, borrower income, and many others. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=drivesdk).


## Summary of Findings

I got my findings through the use of univariate, bivariate and multivariate plots. At the end of this investigation, my findings are:

- State with the name CA has the highest number of borrowers
- There are more borrowers with StatedMonthlyIncome between 4000 to 6500
- The LoanOriginalAmount are more of 5000, 10000, 15000
- There are more of borrower with EmploymentStatus of Employed and Full-time
- The LoanStatus is high on Current and Completed
- More borrowers at Term 36
- The borrowers occupation indicated more as 'Other' or 'Professional'

Afterwards, I answered the proposed reasearch questions;
- What factors affect a loan's outcome status?

The IncomeRange and EmploymentStatus are strong factors that affects the outcome of loans. It is observed that IncomeRange of 25,000 - 49,999 and 50,000 - 74,9999 varies mostly with the LoanStatus. Also, the EmploymentStatus of Employed and Full-time show strong variation with the LoanStatus, especially in the category of completed loans and current loans.
 These findings were resolved using both univariate and bivariate plot.(Univariate subplot of EmploymentStatus for the different LoanStatus category datasets and bivariate barplot of LoanStatus and IncomeRange)
 
 
- Are there differences between loans depending on how large the original loan amount was?

 There exists a difference in LoanOriginalAmount depending on the size. for large size loans, the Term for the loan is always high (Term 60). The LoanStatus for this large loans is more on the current LoanStatus.
The findings were discovered from the bivariate violinplot of LoanOriginalAmount and Term, and also the bivariate boxplot of LoanOriginalAmount and LoanStatus.

## Key Insights for Presentation
For the presentation, I focus on answering the research questions that was proposed at the begining of the analysis;
- What factors affect a loan's outcome status?
- Are there differences between loans depending on how large the original loan amount was?

Then, the list of findings I got from my investigation were presented.

 
