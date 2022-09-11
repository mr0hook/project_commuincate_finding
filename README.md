# Prosper Loan Data Exploration
## by Omar Soliman


## Dataset

> This data set contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 loans with 81 variables. For the purpose of this investigation I've taken the following variables: Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate, Recommendations and Investors.

## Summary of Findings

- Most of the loans in the data set are actually current loans. Past due loans are split in several groups based on the length of payment delay. Other big part is completed loans,    defaulted loans compromise a minority, however chargedoff loans also comporomise a substanial amount.
- The majority of borrowers are employed and all other categories as small part of borrowers. In small Group full time has highest, after that self empolyed are there and so on.
- With a boundary of mean and 3 times standard deviations distribution of monthly income still has noticeable right skew but now we can see that mode is about 5000.
- The most frequent rating among defaulted loans is actually D. And the most frequent rating among Completed is alsoDand second highest is A and so on in Status and Prosper Rating.
- In both of them Credit Start with Listing Category Graphs of the debt Consolidation have most frequency among all of them.
- Lower ratings seem to have greater proportions of individuals with employment status Not Employed, Self-employed, Retired and Part-Time.
- Except for the lowest ratings defaulted credits tend to be larger than completed. Most of the defaulted credits comes from individuals with low Prosper rating.
- Except for Auto, Business and Home Improvemrnt dont have nearly equal mean amoong all of them. Business category tend to have larger amount.
 
## Key Insights for Presentation

> I've chosen key plots with high data-to-ink ratio for the presentation. The plots I've chosen shows distribution of main variables, Loan status, monthly income, Prosper rating and I've tried to tell a story what are major predictors for loan status and Prosper rating variables.