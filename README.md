## Part II - Effects of Loan Characteristics on Borrower's APR
## by Hatif Naqvi


## Dataset

> The dataset consisted of borrower APRs and attributes of 2,765 loans. The attributes included in my analysis are: Employment Status, Income_Range, Term, LoanOriginalAmount, DebtToIncomeRatio, 'ProsperRating (Alpha)'.

## Summary of Findings

> In my analysis, the correlation the BorrowerAPR has a very weak correlation with each other variable. It's influence in a sense is negligible. The Loan amount has a negative correlation of -0.313 which still weak but indicates that the higher the loan amount the lower in the Borrower APR. Overall there aren't any linear relationships between the feature of interest vs other feature. The highest BorrowerAPR by prosper rating was Rating E.

> The loan original amount is positively correlated with the stated monthly income but is of a medium strength ~0.4, which understandabley makes sense because those with more money can borrow more since they have the ability to pay back compared to those making less. When the loan term increased we saw that that the median loan amount increase significantly from shorter term periods. The median Borrower APR for part-time employees is the lowest of all the employement statuses. The 100k+ Income Range Group was able to get the highest loan amounts compared to any other group while also having the lowest median BorrowerAPR.

> The multivariate exploration showed that the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings increased from HR to AA. The amplitude of the poorer rated loans was slightly larger compared to the better ratings.

> In my multivariate analysis I began to look at some more variables that may impact the BorrowerAPR such as Proper Rating and the DebtToIncomeRatio. In my exploration, the increase in terms and loan amount didn't play a significant factor on overall APR. It's not surprising to see that a higher loan rating led to a higher loan amount. This is visbile in ratings AA, A, and B.The APR increases for those in higher ProsperRating as they try to borrow more which makes sense because its a way to defer people from borrow to much. It is also more beneficial for those in higher loan ratings to borrow in shorter terms because the ARR is actually much lower on average. The overall loan amount is influenced significantly by the length of terms and ratings. While, the DebtToIncomeRatio has a very minimal influence from the terms and ratings.


## Key Insights for Presentation

> In my presentation I focus on variables that influence the value of the BorrowerAPR which I found to be the Loan Amount, and the Prosper Rating. I follow a chronological order of my analysis starting with univariate, then bivariate, and finally multivariate analysis on the variables I explored. We explore the distributions of the Borrower APR, Loan Amount, and the Proper Rating. We Followed by the analysis of the correlation between Borrower APR and Loan Amount, and Borrower APR & Proper Rating via heatmap. Then we look specifically at the relationship between Borrower APR and Loan Amount, and Borrower APR & Proper Rating. Lastly, we look at the Borrower vs Loan Amount vs Term and Borrower vs Loan Amount vs Prosper Rating relationships.

