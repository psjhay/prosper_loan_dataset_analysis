# prosper_loan_dataset_analysis

## Dataset

> The prosper dataset provided initially contained 113,937 loans with 81 variables. After performing cleaning operations, i was left with 82,708 unique loan listings and 15 variables that characterize each given loan. 

>The dataset used can be downloaded from [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)

>The feature documentation of the dataset can be found at [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)

## Summary of Findings

> At the onset of my analysis, i encountered the presence of duplicate values within my dataset which i dropped (This was made possible through the listing key). 

> Also, i decided to pick the prosper rating as one of my major features to inspect; This led to my dropping of every loan listing without a value for prosper rating.

> I discovered a high positive correlation between the borrower APR and borrower rate, as well as between prosper rating and prosper score.

> In my investigation on how some variables (employment status, occupation, income range and available bank card credit) impacted the borrower APR; I found (surprisingly) a negative correlation existing between each of these variables and the borrower APR. This suggests that borrowers who earn less are most likely going to have a higher borrower APR and rate.

> I also found that the prosper rating classified loans with high borrower APR as high risk loans. To check that prosper rating classifier was accurate enough, i explored the relationship between prosper Loan status and borrower APR. I discovered that lower borrower APR loans which prosper rating associated as low risk loans are the major constituents of the 'completed' and 'final payment in progress' loan status classes; while the charged off, defaulted and delinquent loan classes have relatively high borrower APR.

