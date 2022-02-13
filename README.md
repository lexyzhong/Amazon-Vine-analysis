# Amazon Vine Analysis
## Overview
In this project, we will analyze the Amazon Vine review dataset for cameras. We will use PySpark to extract the data via ETL, transform the data, connect to an AWS RDS instance, and load the data into pgAdmin. We will also use PySpark to determine if there is a bias towards favorable reviews from Vine members for this dataset.

## Results
How many Vine reviews and non-Vine reviews were there?
- Vine reviews: 580
- non-Vine reviews: 47,703 

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine reviews: 246
- non-Vine reviews: 23,837 

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine reviews: 42.41%
- non-Vine reviews: 49.97%

See below image for reference:
![Summary.png](https://github.com/lexyzhong/Amazon-Vine-analysis/blob/main/Resources/Summary.png)

## Summary
Of the Vine (i.e. paid) reviews, 42.41% are 5 Star. Of the non-Vine (i.e. unpaid) reviews,  49.97% are 5 Star. This suggests that there is no positivity bias for reviews in the Vine program. To determine if there is a slight negativity bias present, additional statistical analyses (such as t-tests) are required.
