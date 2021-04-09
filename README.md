# Decision Trees and Random Forerests Project

For this project I will be exploring publicly available data from LendingClub.com.  


# Brief background:
Lending Club connects people who need money (borrowers) with people who have money (investors). Investor want to invest in people who showed a profile of having a high probability of paying the loan back. 

# Columns    
Column Name | Description
------------ | -------------
credit.policy | 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
purpose | The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other")
int.rate | The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
installment | The monthly installments owed by the borrower if the loan is funded.
log.annual.inc | The natural log of the self-reported annual income of the borrower.
dti | The debt-to-income ratio of the borrower (amount of debt divided by annual income).
fico | The FICO credit score of the borrower.
days.with.cr.line | The number of days the borrower has had a credit line.
revol.bal | The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
revol.util | The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
inq.last.6mths | The borrower's number of inquiries by creditors in the last 6 months.
delinq.2yrs | The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
pub.rec | The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
not.fully.paid | whether the loan was fully paid or not

# Problem:  
Which borrower have high probability of paying back the loan in full?

# Goal:
Create a deascion tree model that will help predict wether or not the borrower will pay back the loan in full.

# Summary of the solution:
1. Data overview:
  * Data type
  * Number of columns
  * Numbers of rows
  * Data description and statiscal summary
2. Data Analysis Exploration (EDA)
3. Setting up the data for machine learning
  1. Categorical features engineering
  2. Data train test split
  3. Model train
    1. Decision tree model
    2. Random forest model
  4. Model predection
  5. Model evaluations
