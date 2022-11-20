# Amazon_Vine_Analysis

## Overview of the Analysis
- The overview of this analysis is to perform the ETL process completely in the cloud and upload a data frame to the RDS instance and use spark to perform a statistical analysis of selected data. 

- The purpose of this analysis is as of the majority of shoppers, Amazon shoppers depend on product reviews to make personal decisions.
 
Amazon makes their vine review datasets policy available. Vine reviews are the great degree of large and can exceed the capacity of local machines to handle them because we are using spark and AWS 
I use different natural language processing skills-  AWS, RDS,s3, Python, and pyspark google collab notebooks were explored to prepare the review analysis for a client interested in personal care products.

## Results

   - How many Vine reviews and non-Vine reviews were there?
The dataset shows 85981 reviews. only revies with 20 or more votes were considered for the rest of the analysis leaving 3414 reviews. Helpful votes were defined as 50 or greater than the total votes slightly attenuating the list to 3097 reviews.
	

   - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
   As 5 star vine paid review, there were 3 paid vine reviews and 2 paid 5 star rating reviews. 
   And thre were 3094 unpaid vine reviews  and 1704 unpaid 5 star rating reviews.
   
   ![paid vine reviews](https://user-images.githubusercontent.com/107454933/202919535-ddf6ebc8-c109-49ee-b267-7c34e47986e4.png)
   ![piad star rating](https://user-images.githubusercontent.com/107454933/202919554-fb1962f5-1ce0-4928-bd76-954445380e61.png)
   
   ![unpaid vine reviews](https://user-images.githubusercontent.com/107454933/202919581-50ebb8c6-76a0-4ebc-b337-d9e5c34fc8df.png)
   ![unpaid star rating](https://user-images.githubusercontent.com/107454933/202919599-54f3a644-785f-4e3e-88cf-0d0154ef5b48.png)






   
   - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   The percentage of 5 star reviews for paid vine program was: 66.666667%
   And the percentage of 5 star reviews for unpaid vine program was: 55.074337%
   ![percentage](https://user-images.githubusercontent.com/107454933/202920097-25c436f2-9fc7-46c8-837f-ebaf8e8694f8.png)
   
  ## Summary
  Based on the result the percentage of paid 5 star rating was higher than the percentage of unpaid 5 star rating reviews.tahis discribe a positivity bias for reviews in the vine program. 
  Additionaly we could analysis the statistical distribution of a star rating for the vine and non vine revaiews.  

   


