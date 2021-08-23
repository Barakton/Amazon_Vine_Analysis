# Amazon_Vine_Analysis
## Overview
The purpose of this analysis was to pick a dataset from amazon and transform and load the data to pgAdmin. After that, we are trying to find out if there is any bias towards favorable reviews from Vine members.

## Results
We are trying to answer the following questions.
- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

For the first point, as you can see below, there are 285 Vine reviews, and 31,545 non-Vine reviews
![vinereviews](https://user-images.githubusercontent.com/83259639/130390091-2d2fa156-dbd4-4a01-89f7-7bea709c4f20.PNG)
![non-vinereviews](https://user-images.githubusercontent.com/83259639/130390097-5c78266a-e302-428c-9099-a2095b709366.PNG)

For the second point, there were 163 paid 5 star reviews and 14614 unpaid reviews, as shown below.
![paid_vine](https://user-images.githubusercontent.com/83259639/130390284-f9d20972-f776-4895-ac82-6f4003a71f8f.PNG)
![unpaid_vine](https://user-images.githubusercontent.com/83259639/130390287-728e402e-26db-4d55-80cb-6c56ccff852a.PNG)

Lastly, here are the percentages for paid and non-paid 5 star reviews.
57% for paid reviews and 46% for non-paid reviews.
![paid_percent](https://user-images.githubusercontent.com/83259639/130390398-a7d03d21-0e1b-4859-8b30-26fa2fc0cb28.PNG)
![unpaid_percent](https://user-images.githubusercontent.com/83259639/130390402-af928622-6d0a-4136-bad2-3915b92789ad.PNG)

## Summary
As you can see from the points above, there is a slight bias towards the paid reviews over the non paid reviews. It is about an 11% difference overall. One way we could further prove bias is by verifying that both paid and unpaid reviewers actually purchased their product! This would be pretty simple since this is already provided by Amazon!
