# Amazon_Vine_Analysis
## Overview
The purpose of this project is to analyze Amazon Vine program and to determine if there is bias towards reviews that were written as part of the Vine program.
This analysis is focused on US reviews for toys and uses PySpark to perform ETL process to extract the dataset, transform the data , and calculate different metrics.

## Results
### How many Vine reviews and non-Vine reviews were there?
* Vine reviews

 ![TotalPaidReviews](https://user-images.githubusercontent.com/76926148/205463831-3481e976-1447-4589-b77a-7dc35e90f8fd.PNG)


* Non-Vine reviews

 ![TotalUnPaidReviews](https://user-images.githubusercontent.com/76926148/205463841-de64cc59-406f-4adf-abcc-3ddfb14a6b31.PNG)


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* Vine 5 star reviews

 ![TotalPaid5StarReviews](https://user-images.githubusercontent.com/76926148/205463847-e5205753-e803-4279-8e08-fbbfde59522b.PNG)


* Non-Vine 5 star reviews

![TotalUnPaid5StarReviews](https://user-images.githubusercontent.com/76926148/205463854-b91dd0d6-dde4-4a04-b781-fe25473203c7.PNG)


### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* Vine 5 star reviews percentage

 ![TotalPaid5StarReviewPercentage](https://user-images.githubusercontent.com/76926148/205463860-fdcaec84-2b1c-443b-93e8-cc6c3b56487d.PNG)


* Non-Vine 5 star reviews percentage

 ![TotalUnPaid5StarReviewPercentage](https://user-images.githubusercontent.com/76926148/205463868-b793a031-4c17-4ba9-b631-f73b2153f216.PNG)

## Summary
The review percent of paid five star reviews is lower compared to the percent of nonpaid five star reviews among the total reviewers which indicates that there is no bias.
Additionally, we may need to perform statistical analysis to understand if the differences we see are statistically significant for the given sample size.


