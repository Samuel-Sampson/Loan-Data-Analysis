# Loan-Data-Analysis

## Dataset
The data consists of information regarding 113,937 different loans with data on many factors regarding the loan (such as interest rate and length of the loan), as well as information on the borrower (such as occupation and employment status) from Prosper loan data: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1595887334960000&usg=AOvVaw2rktKMrqe-gI4dFaHpRt4q


## Summary of Findings

In the exploration, I found a significant relationship between Borrower APR and status of the loan. The short term loans among those that defaulted especially tended to have a high APR. But regardless of the term of the loan, the defaulted loans (on average) showed a higher APR across the board.

One surprising thing that was seen in the data is that Prosper Score didn't seem to have much affect on the status of long term loans. Though there was a degree of variability, on average 60 month loans on average had a Prosper Score around six regardless of the loan status (whether it was completed, current or defaulted).


## Key Insights for Presentation

For this presentation, I focused on primarily the influence of Borrower APR, Prosper Score, and Term on the status of the loan. Due to the fact that there are many loan statuses in the data set, I wanted to narrow the scope and focus on loans that have either a completed, current, or defaulted loan status.  I start by introducing the loan status variable, followed by the pattern in Borrower APR distribution, then plot both on a violin plot.

Afterwards, I used a pointplot to observe the relationship between Borrower APR and Prosper Score across completed, current, or defaulted loan statuses. Then I introduce the variable for Term of the loan and create a bar plot to observe the relationship between Borrower APR and Loan Term across the different loan statuses listed above.
