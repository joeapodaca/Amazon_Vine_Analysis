# Amazon_Vine_Analysis

## Overview
Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Is there is any bias toward favorable reviews from Vine members?


## Results
Reviews from both Vine reviewers and non-Vine reviewers were analyzed to see what percentage of reviewers are leaving 5-star reviews.

First the data was retrieved and filtered on total vote counts equal to or greater than 20.
![total_votes](https://github.com/joeapodaca/Amazon_Vine_Analysis/blob/main/total_vote_counts.JPG)

Next the data was filtered to find the helpful votes great than 50%.
![Helpful_Votes ](https://github.com/joeapodaca/Amazon_Vine_Analysis/blob/main/helpful_votes.JPG)

Then the Vine paid reviews were filter out.
![Vine Paid ](https://github.com/joeapodaca/Amazon_Vine_Analysis/blob/main/vine_reviews.JPG)

Then the unpaid reviews were filtered out.
![Unpaid ](https://github.com/joeapodaca/Amazon_Vine_Analysis/blob/main/non_vine_reviews.JPG)

Finally, the total of 5 star reviews were counted for each paid and unpaid review. 
The total 5-star Vine reviews was 51%.  While the total for non-Vine reviewers was only 39%.  
![percentage](https://github.com/joeapodaca/Amazon_Vine_Analysis/blob/main/5_star_reviews.JPG)

# Summary
The number of 5-star reviews is higher when the review is paid.  This supports the bias towards favorable reviews from Vine members.  Although this does support the bias the total number of Vine reviews is low compared to the non-Vine reviews.  Another analysis could be done on an item that has more paid Vine members.
