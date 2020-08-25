# Loan Data Exploration

## Dataset
- Name: prosperLoanData.csv
- Definition: Loan Data from Prosper
- Source: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv
- Detail: This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate),current loan status, borrower income, and many others<br>

## Summary of Findings

In the exploration, I found the following under Univariate, Bivariate and Multivariate Exploration:-
### 1. Univariate Exploration
-Loan status of maximum people is "current".
-Loan amount is usually between 0-15000. Maximum no. of people have loan amount in the range (approx) 4000-7500.
- The borrower percentage rate varies most commonly between 0.12 -036. The most common rate being 0.35-0.36.
- Frequent value Borrower Debt to Income Ratio lies in 0.1-0.3.
- The borrowers interest rate varies mostly between 0.7-0.32
- The borrowers are almost equally distributed, having both high as well as low risk borrowers.
- The common prosper ratings are C,B and A respectively which is quite good. But HR also has reasonable number which cannot be ignored
- The most common prosper rating is 4. But even borrowers with rating 1 are present.
- Most of the people who took loans are employed.
- More people are houseowners.
- Most of the borrowers have income in the range 50,000-74,999 and 25,000-49,999 respectively
- Monthly Income is right skewed. The common range is 1000-7000 approximately.
- Monthly loan payment is right skewed,common range lies in 0-400.


### 2. Bivariate Exploration
- Postitive correlation is between Loanoriginalamount and monthlyloanpayment.Negative correaltion is between borrowerrate and loanoriginalamount, borrowerrate and prosper score.
Borrowers with high prosper score get loan at lower annual percentage rate.Also loans of lesser amount is given at low annual percentage rate. 
- Borrower Interest Rate and Prosper score are inversely related to each other
- Loan Amount and Borrower Interest Rate are negatively correlated.
- Self employed have least prosper rating with some outliners present. Full time, part time and retired have high prosper rating. So full time employees get loan at a lesser rate as compared to others.Self-employed have to pay a high annual rate.Also full time employees gets loan easily whereas self-employed do not get loan easily.
- Prosper score affects the loan original amount.People with less prosper score have lesser loan amount than people with higher prosper score. Therefore it's easier to get high amount loan with higher prosper score
- People with income range 75,000-99,999 and 100,000+ have high prosper score.
People with income > 75,000 get loan easily. 
- Therefore people with higher income have higher prosper score and thereby they get high amount loans at a lower borrowerARP.



### 3. Multivariate Exploration
- High prosper rating has lesser Borrower rate and lesser borrower ARP.So borrowers with high prosper rating get loans at a lesser rate and borrowerAPR
- Income range 100,000 + take loans with high original amount and have most common loan status as current.
- Income range 1-24,9999 takes low amount loans.Income Range 50,000-74,999 have most number of past due(>120 days) as status.Income range 1-24,999 has large number of prosper rating as HR compared to the total borrowers in that range.So employees having income in this range have lesser chance of getting loans of high amount.
- Employees with status 'Employed' and 'self-employed' take loans of larger amount.
Employess with less income take loans of lesser total amount(Around 3000-5000) and their prosper score i lesser than others therefore it's not easy for them to get high loan.


## Key Insights for Presentation

- Higher income earning borrowers have high propsper score and thereby they can get loan easily, whereas borrowers having income <=49,999 have low prosper score and do not get loan easily.
- Borrower Interest Rate and Prosper score are negatively correlated to each other.Similarly BorrowerAPR and Prosper score are also negatively correlated to each other.High prosper rating has lesser Borrower rate and lesser borrower APR.Borrowers with high prosper score get loan at lower interest rate and lower APR and those with lesser prosper score need to pay a higher interest rate and higher APR.
- Therefore borrowers with higher income get loans easily and at a less interest rate and lesser APR whereas borrowers with low income face difficulty in getting loans and need to pay a higher interest rate and higher APR.
- Self employed have least prosper rating with some outliners present. Full time, part time and retired have high prosper rating.Full time employees gets loan easily whereas self-employed do not get loan easily.
- So full time employees get loan at a lesser interest rate ,lesser APR and more easily as compared to others.Self-employed have to pay a high interest rate,high APR and face difficulty in getting a loan.
- Borrowers with less prosper score have lesser loan amount than those with higher prosper score.It's easier to get high amount loan for borrowers with high prosper score.
- Borrowers with higher income get loans of higher amount easily and those with lesser income do not get high amount loans easily.
- Loan Amount andBorrower Interest Rate are negatively correlated to each other.Loans with larger amount are provided at lesser interest rate and those with lesser amount are provided at higher interest rate.