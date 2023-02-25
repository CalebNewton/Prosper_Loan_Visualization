## Prosper Loan Data Exploration


### by Caleb Henry

### Dataset

Each loan in the prosper loan dataset has 81 variable, including the loan amount, borrower rate (or interest rate), loan status, borrower income, borrower employment status, borrower credit history, and the most recent payment information. The dataset has 113,937 loans in total.

### Summary of Findings

I discovered that the borrower APR and original loan amount were negatively associated, which means that the greater the loan, the lower the APR, during my bivariate study and from one of the visualisations. Another adversely linked with stated monthly income is the debt-to-income ratio. Also, I discovered that there is a positive association between the initial loan amount and the declared monthly income, with a correlation coefficient of 0.183. This makes logical because you should be able to get a bigger loan if your salary is larger.

The matrices show that the APR increases with term length, although the average APR for terms of 36 and 60 months appears to be around the same. It's crucial to remember that, despite the possibility of a similar mean, the 36-month APR range is substantially wider. Moving on to "Employment Status," we can see that people who are "not employed" have the highest average APR, while people who work "full-time," "part-time," and "retired" have some of the lowest average APRs. I then want to look at how the loan status and APR are related. The less desirable statuses (Past Due) all appear to have higher average APRs. Finally, it is clear that the APR significantly decreases when a borrower's credit rating rises. So, it is clear that the rating has a significant impact on the APR. The aforementioned plots lead to the same conclusion. The annual cost of a loan to a borrower and their employment, prosper rating, and credit score are all strongly correlated.

The higher the Income Range, the more likelihood for an individual to receive a Loan. In the plot to the right, "part-time," "not employed," and "retired" don't provide much information, but we may infer that the majority of the present loans are issued to people who are regarded as employed. The most loans have been repaid by those who are deemed to be "full-time." Next, we can observe that the vast majority of the loans have 36 terms in the bottom left corner. Of all the loan categories, it appears that 36-month holds the most loans.

For the multivariate plot, while investigating the impact of ratings on the link between loan amount and APR, one unexpected conclusion is the progressive shift from a negative to a positive association. We observe a negative association between rating HR and B. As we continue to grow, it becomes better. Another intriguing conclusion is that while APR grows with term length for individuals with ratings B-AA, it decreases for those with ratings HR-C. . Only a small number of borrowers having loans with Prosper Ratings of AA have defaulted, as seen on the plot.

### Key Insights for Presentation

* Connection between the two key characteristics (BorrowerAPR and Loan Amount): A borrower can estimate the exact cost of the loan with the help of the borrowerAPR. According to the investigation, there was a negative link, which suggests that one variable usually tends to make another one go down. Your BorrowerAPR decreases the more money you borrow.

* BorrowerAPR across LoanStatus and LoanOriginalAmount: The higher the borrowerAPR, the lesser the original amount collected for all the above loan status and Vice versa.

* BorrowerAPR across Term and IncomeRange: The APR rises as the income range narrows for each particular period across each bracket. Usually, the APR goes down as the period lengthens, however in this case, it goes up when the income range drops from 100,000 to zero.
