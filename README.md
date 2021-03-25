# Amazon Reviews Analysis #

## Overview of the Analysis ##
Using Google Colab notebook, pyspark, and sample reviews from an Amazon S3 database the purpose of this project was to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews for video games. 

## Results ##

The results can be reviewed in the ipynp file located [link to results](https://github.com/AsaHolley/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_Vine_Analysis.ipynb) 

* **How many Vine reviews and non-Vine reviews were there?** A total of 40,471 unpaid reviews for video games were in the sample set and 94 paid Vines were in the sample.

* **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?** A total of 15,663 unpaid 5 star reviews were in the sample database and only 48 paid  5 star reviews were in the data.

* **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**  The percentage of Vine 5 star reviews that were paid was 0.12% of total reviews (both paid and unpaid). This is significantly less than the unpaid 5 stars reviews which equated to 38.61% of total unpaid reviews. 


## Summary ##
Given the significantly larger percentage of 5-star reviews in the unpaid population vs. the paid population it is clear that the paid Vine reviews, and 5-star reviews in particular, would not have a significant impact on the overall bias. What is not clear, however, is if that small percentage of paid  5 star reviews had an impact on those who submitted positive unpaid reviews. An additional analysis that could explore whether the paid reviews had an influence over the positively of the unpaid reviews is to look at the date and time when the paid 5-star reviews were posted vs. the unpaid positive reviews.

