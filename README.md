# Big Data 

## Overview of the Analysis
### Purpose
A hypothetical company, BigMarket, helps businesses optimize their marketing efforts. Their client needs help analyzing Amazon reviews written by members of the paid Amazon Vine program. Using PySpark, I determined if there is any bias towards favorable reviews from Vine members in my dataset. The goal was to figure out if having a paid Vine review makes a difference in the percentage of 5 star reviews.

## Results
### DataFrames from Google Colaboratory
- There were 2,106 Vine reviews and 703,783 non-Vine reviews. 
- 854 Vine reviews were 5 stars and 373,134 non-Vine reviews were 5 stars.
- 40.55% of Vine reviews were 5 stars and 53.02% of non-Vine reviews were 5 stars. <br>
Below are screenshots of the DataFrames with Vine and non-Vine reviews with at least 20 votes and at least 50% of the votes were helpful. <br>
<kbd> <img src='https://github.com/npantfoerder/amazon-vine-analysis/blob/master/Images/vine_reviews.png' width=900> </kbd> <br>
<kbd> <img src='https://github.com/npantfoerder/amazon-vine-analysis/blob/master/Images/not_vine_reviews.png' width=900> </kbd> 

## Summary
According to the results, there is no positivity bias for reviews in the Vine program because there were less 5 star Vine reviews than 5 star non-Vine reviews. One additional analysis that I could do with the dataset to support this is finding ...

#### Resources
- Data Sources:
- Software: Python 3.7.3, PySpark 3.0.1
