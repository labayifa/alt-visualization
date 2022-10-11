# Prosper Loan DataSet Visualization Exploration

### Presentation
>   I choosed to work with Prosper Loan Data. This dataset contain __113 937__ *loans with* __81__  *variables* to describe each observation. Inside the dataset we have information about the borrower, the loan status, the loan amount, the income for each employee, among others. Our Exploration was first about understanding each variables, after that check relation between some of these to answers some questions about the work done by this company employes.


## Exploration
#### Prosper Loan DataSet

> Prosper Loan Data set contain 113 937 loan with 81 variables to describe each observation about the borrower, the loan. Because of the large number of variable that we have, my first thougth was to sort the relation between all varaible to see if we are in case of merged dataset or informatio from different source. By following this exploration I found that we some variables have more thant __25%__ of their values null.
###  Exploratory Goal
> At first Step we have tried to understand the dataset then :
>   - Selected [feature(s) of interest](#markdown-header-features-of-interest) for the vizualization process:
       
>   - Select  features in the dataset that will help support our investigation into your feature(s) of interest

> Our goal with this current work is to discover and explain
>   - If Borrowers have been selected following right criteria, 
>   - And also being able to tell which group of people are holding the high risk by getting more loan.
>   - If there is any other insight about a particular case of situation with borrower
>   - If people really attend the payment of the loan

#### Exploratory And Conclusion:
> Second step we remove theses unuseful variables, then explore again variables type by type and choosed now 12 variables from all the dataset.

> Now we have proceed with univariate, bivariate and multivariate exploration and finally get:
    - which group of people demanding the most and highest loans, and also what is their salary range.
    - why people without income veriable have gotten loan
    - Is the loan attribute following correct choice ?
    
### Features of interest

> __IsBorrowerHomeowner__ : A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.

> __IncomeVerifiable__ : The borrower indicated they have the required documentation to support their income.

> __IncomeRange__ : The income range of the borrower at the time the listing was created.

> __LoanStatus__ : The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.

> __Occupation__ : The Occupation selected by the Borrower at the time they created the listing.

> __EmploymentStatus__ : The employment status of the borrower at the time they posted the listing.

> __LoanOriginalAmount__ : The origination amount of the loan.

> __BorrowerRate__ : The Borrower's interest rate for this loan. 

> __EmploymentStatusDuration__ : EmploymentStatusDuration

> __DebtToIncomeRatio__ : The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001%).

> __MonthlyLoanPayment__ : The scheduled monthly loan payment.

> __TotalCreditLinespast7years__ : Number of credit lines in the past seven years at the time the credit profile was pulled.

> __DelinquenciesLast7Years__ : Number of delinquencies in the past 7 years at the time the credit profile was pulled.

### What features in the dataset do you think will help support your investigation into your feature(s) of interest?

> __LoanStatus__ : The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.

> __Occupation__ : The Occupation selected by the Borrower at the time they created the listing.

> __LoanOriginalAmount__ : The origination amount of the loan.

> __MonthlyLoanPayment__ : The scheduled monthly loan payment.

