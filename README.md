#  Paid Vs. Unpaid Amazon Vine Review Analysis
## Overview
Using Amazon AWS, PySpark, PostgresSQL, and Pandas, perform an analysis of product reviews from the ‘Wireless’ category of purchases. Then, examine the positive review percentages for participants and non-participants in the paid program. 

## Results
### Total Vine Reviews
- **Total**: 613

![totalvine.png](Analysis/totalvine.png)
### Total Non-Vine Reviews
- **Total**: 64,968

![totalnotvine.png](Analysis/totalnotvine.png)

### Total 5-Star Vine Reviews
- **Total**: 222

![totalvine5star.png](Analysis/totalvine5star.png)
### Total 5-Star Non-Vine Reviews
- **Total**: 30,543

![totalnotvine5star.png](Analysis/totalnotvine5star.png)

### Percentage of 5-Star Vine Reviews
- **Total**: 36.21%

![totalvine5starpercent.png](Analysis/totalvine5star.png)
### Percentage of 5-Star Non-Vine Reviews
- **Total**: 47.01%

![totalnotvine5starpercent.png](Analysis/totalnotvine5starpercent.png)

## Summary
Based on my analysis, I do believe there is a small amount positivity bias in this sample of reviews. Looking at the percentages of *’perfect’* scores, however, it seems like paid participants were more likely to be thoughtful about their reviews and give specific items truly-reflective ratings, rather than offer five stars in exchange for a payout. 

Further examination of *helpful votes* vs *total votes* would be a good second step in this analysis. For example, ‘Did paid participants receive more helpful votes than non-paid participants?’ Or ‘Were average consumers more likely to trust those who hadn’t been paid to review an item?’ The mid-range [between 2 and 4] star ratings could be an interesting slice of this data on which to perform this analysis. 

