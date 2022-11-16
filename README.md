# Prosper Loan Data exploration
## by Nonso Udechukwu


## Introduction to the Prosper Loan Dataset

This dataset is from Prosper, a top marketplace lending platform in the United States. It contains 113,937 loan listings with 81 features, including loan data (e.g. loan amount, borrower rate, current loan status), borrower data (e.g. borrower income, employment status, and credit history), and credit risk data (e.g. ProsperScore).

The dataset can be found <a href='https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv'>here</a> and the feature dictionary can be found <a href='https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0'>here</a>


## Summary of Findings

> During my investigation of this Prosper Loan dataset, I narrowed down my exploration to 20 variables, given that I was primarily interested in BorrowerAPR and features influencing it.
>
>I discovered that the BorrowerAPR (the total fees the borrower pays annually) is negatively correlated with loan original amount, borrower's Prosper rating, employment status, stated monthly income, and income range. I also noted that, across the years, BorrowerAPR is generally lower for home owners than for non-homeowners.
>
> Interestingly, while 75% of borrowers earning $50,000 and above had BorrowerAPR less than 0.3, borrowers earning $100,000+ paid slightly higher APR on their loans than borrowers earning $75,000 to $99,999.
>
> Also interesting was the finding borrowers are likelier to pay more BorrowerAPR for short-term loans than longer-term loans UNLESS they are rated B and above. In which case, longer-term loans become costlier than shorter-term loans. 
>
> Outside of the main focus, I found that the more a borrower earns, the larger the loan amount they request for or are able to get, with LoanOriginalAmount being moderately positively correlated (0.413) with StatedMonthlyIncome.


## Key Insights for Presentation

> To get a favourable BorrowerAPR on your loan, it is advisable to be an employed homeowner earning between $50,000 and $99,999 and seeking a large loan. 