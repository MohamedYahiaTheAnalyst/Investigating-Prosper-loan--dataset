# Investigating Prosper loan dataset
Investigation Prosper loan dataset. This project is a part of Udacity data analyst nanodegree. 
## Prosper Loan Data

> Prosper loan dataset contains data of about 113937 loans and 81 features for these lonas. Some of these features are catigorical. For example, whether or not the Borrower was in a group or whether or not the Borrower is a Homeowner, and some features are numarical. For example, number of delinquent days , monthly income , interest rate and so on.\

## Summary of Findings

> Explorating the deta reveals some intersting finding:\
- Most of loand are goos loans(completed or current) with no days in delinquent.About 10% of the loans cahrged off.
- Good loans have no delinquent days. Past Due loans has the smallest delinquent days average because as delinquent days exceeds 120 it considered a Defaulted loan. Charged off loans have the most delinquent days as they do not have limit.
- Surpricingly, LongTerm loans have the lowest average delinquent days and Medterm loans have the highest. Shortterm loans have low average but it make scence because thier short period decreace dafault chances.
- loans with problems( past due , defaulted and chargedoff) have higher average interest rate than good loans.
- Barrowers in good loans have higher monthly income than barrowers in other loans.
- In group borrowers have higher average delinquent days than out of group borrowers.
- Delinquent days have strong positive relation with priciple loss and have postive relationship with loan months since orgination of the loan.
- In charged off loans as months past it increases days in delinquent because the chances for repay the the loan are very low.
- in group and out of group borrowers have very close average delinquent days in good past due and defaulted loans. on contrary , borrorews in group have higher average delinquent days than indvidual borrowers


## Key Insights for Presentation

> In group borrowers loans consider more safer.They have higher score rate and higher recomediations.
- Surpricingly, in group borrowers' loans have higher average delinquent days.
- by investigating this further, in group borrowers have higher average delinquent days in charged off loans.  
- In group borrowers' need recomediations reconsideration.
