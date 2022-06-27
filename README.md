# Amazon_Vine_Analysis

## Overview of the analysis:

The purpose of this project was to use pick one of many datasets related to different products and analyze the reviews submitted by Amazon Vine program customers. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We are tasked by using PySpark and perform the ETL process on one dataset to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results:

![](https://github.com/kbehyar/Amazon_Vine_Analysis/blob/main/Images/vine_review_analysis.PNG)


- How many Vine reviews and non-Vine reviews were there?

261 reviews were Vine program related and 24040 were non-vine program related.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

106 of the Vine reviews were Five star and 10899 of the non-vine reviews were Five star.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

%40.61 of the Vine reviews were Five star and %45.37 of the non-vine reviews were Five star. 



## Summary:

- Reviews produced by the non-Vine showed a slightly higher tendancy to positive reviews than Paid reviews indicating a bias towards giving higher ratings.
- For the filtered sample, there was a 40.61% of 5-Star reviews given by Vine versus a 45.37% of 5-Star reviews by non-Vine members.
- 106 / 261 ratings by Vine were 5-Stars
- 10899 / 24040 ratings by others were 5-Stars
- Total sample of Vine Reviews were much smaller than the population (Less than 0.011%), but out of this sample there was a stronger inclination to give higher ratings.
- Further analysis can be done using other datasets to indicate which products have stronger bias than others.
