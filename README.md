# Prosper Loan Dataset Exploration
## By Fidel Ejakait


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be download here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000. With feature documentation available here https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000

## Summary of Findings

> The plot shows that more than 50,000 individuals has a loan with Prosper, and quite a number has completed the loan. The number of past due and cancelled are quite low

>Looks like most borrower are given with low score. The lower the score, the higher borrower counts it has.

>Top 10 Occupations Count: most borrowers enter their occupations as "others" or "professional" because they might not want to share this information. The rest of the occupations do not show big increase compare to others.

>it is rare that unemployed individual can obtain a loan from Prosper.

>It is interesting to find out who the top occupations are. But all these occupations have about same BorrowerAPR values. Therefore occupation is not the best factor to analyze the BorrowerAPR because it is unclear and many other reasons should also be considers to be analyzed.

>People who are employed don't necessarily have lower rate. But unemployment does have a higher median rate and higher concentrate of frequency are above the median. Looking at the income range plot, there is a slight trend that median rate is lower, the higher the income range is. It seems like income range is part of a determining factor for the rate a borrower will get.

>it seems like occupation a factor in the borrower's rate. I notice that occupation will lower average salary such as clerical, nurse's aid, bus driver and teacher's aide all have higher median rate.

>BorrowerAPR vs. CreditScoreRangeUpper: even though the the pts are all over the plot. with the help of alpha feature, we can still see the trend that the higher the CreditScore leads to lower APR percentage. The heatmap on the same variables helps to make this point more clear.

> Borrower rate:the higher the income, the lower the rate will be. As for those unemployed, the rate will be signficantly higher than those who are employed

## Key Insights for Presentation

> First, histogram plot were created to visualize the distribution on borrower's APR percentage. After exploring all possible variables related to BorrowerAPR. ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). Scatter plot and Heatmap were also created to find out that ProsperScore and BorrowerAPR were negatively correlated. The third plot created multiple scatter plots (BorrowerAPR vs ProsperScore) on different letter ratings. The plots showed the lowerest rating(HR) of borrowers received the highest APR percentage, and borrowers with highest rating (AA) received the lowerst APR percentage.
