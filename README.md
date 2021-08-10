# Amazon_Vine_Analysis
Analysis on Amazon's Vine Program

## Analysis Overview
This project runs an analysis on Amazon's Vine program to determine if there is any type of bias from the Vine members. The dataset selected from Amazon reviews contains kitchen reviews. Pyspark will be used to perform the ETL process by:
- Extracting the data
- Transforming the data
- Connecting to the database (generated through AWS websever)


## Results
### How many Vine reviews and Non-Vine reviews were there?
- Vine Reviews: 1,207
- Non-Vine Reviews: 97,837

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- 5-Star Vine Reviews: 46,367
- 5-Star Non-Vine Reviews: 45,828

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 5-Star Vine Reviews: 48.44%
- 5-Star Non-Vine Reviews: 44.79%

## Summary
After conductin my analysis, it appears there is not a posivity bias in the vine program. Both review percentages range from 44% - 48% which are close in range. 
