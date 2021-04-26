# Amazon_Vine_Analysis
Using PySpark to perform the ETL process and determine if there is any bias in the dataset.

## Overview of Project

### Purpose

### Resources
- Software: Spark, PySpark, Google Colab, PG Admin, PostgreSQL, VS Code 
- Data: [US Amazon Reviews for Major Appliances](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Major_Appliances_v1_00.tsv.gz)

## Project Results 
Code for the analysis can be found in the [Vine_Review_Analysis.ipynb](Vine_Review_Analysis.ipynb).

### Vine Reviews

- <strong>How many total Vine reviews were there?</strong> There were 35 total Vine reviews.
- <strong>How many 5-star Vine reviews were there?</strong> 18 of the Vine reviews were 5-star reviews.
- <strong>What percentage of Vine reviews were 5 stars?</strong> 51% of Vine reviews gave 5 stars. 

###### DataFrame of Results:
<img src='images/vine_reviews.png'>


### Non-Vine Reviews

- <strong>How many total non-Vine reviews were there?</strong> There were 4957 total non-Vine reviews.
- <strong>How many 5-star non-Vine reviews were there?</strong> 1963 of the non-Vine reviews were 5-star reviews.
- <strong>What percentage of non-Vine reviews were 5 stars?</strong> 40% of non-Vine reviews gave 5 stars. 

###### DataFrame of Results:
<img src='images/non-vine_reviews.png'>

## Summary

### Conclusion

There does appear to positivity bias for reviews in the Vine program. This conclusion is derived from the fact that 51% of major appliance reviews in the Vine program had a 5-star rating compared to 40% of the non-Vine reviews. 

### Additional Analysis

