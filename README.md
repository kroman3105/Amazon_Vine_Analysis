# Amazon_Vine_Analysis

## Overview
Using PySpark and the Google Colab Notebook, an analysis was performed on review data obtained for Amazon luggage purchases.  This data included an indicator of whether or not the review was a paid Vine review. An analysis was performed to see if having a paid Vine reviewer influenced the number of 5 star reviews given.

## Results

#Vine Reviews
![Vine](https://github.com/kroman3105/Amazon_Vine_Analysis/blob/main/Images/Paid_Reviews.PNG)

#Non-Vine Reviews
![NonVine](https://github.com/kroman3105/Amazon_Vine_Analysis/blob/main/Images/Unpaid_Reviews.PNG)

 - There were 21 total Vine reviews on luggage, compared to 6,690 non-Vine reviews
 - Vine reviewers gave 10 5-star reviews, while non-Vine reviewers gave 3,448 5-star reviews
 - 47.6% of Vine reviews were 5-star, while 51.5% of non-Vine reviews were 5-star

## Summary
Based on the results of our analysis, it does not appear there is any real bias for reviews in the Vine program.  There was a less than 4% difference in the percentage of 5-star reviews between paid and unpaid which does not indicate a signifant bias between the two types.  That being said, with only 21 total Vine reviews, it's not a very large dataset to draw too many definite conclusions.  One additional analysis I would run is to run the same calculation, but do it without filtering the data on those reviews where helpful_votes was greater than 50%.  This would both increase the sample size of the Vine reviews, and it would also remove any skew that may be in the data of those reviews that are deemed "helpful".
