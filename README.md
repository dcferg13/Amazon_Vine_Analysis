# Amazon_Vine_Analysis
Analyzing Amazon reviews written by members of the paid Amazon Vine program
Tools used for this analysis include AWS, ETL, pgAdmin and Jupyter Notebook.
## Overview
  The purpose of this analysis is to look at a dataset of reviews on Amazon. Then analyze how the Vine program reviews compare to reviews not a part of the vine program.
  In this analysis we used the Musical Instruments Dataset from the Amazon REview datasetsLinks. To complete the analysis we extracted the dataset into a DataFrame, transformed the DataFrame into four separate DataFrames that match the table schema we made in pgAdmin using an ETL. Then, we uploadedcthe transformed data into the appropriate tables and ran queries in pgAdmin to confirm that the data has been uploaded.
## Results
Analysis of the dataset results is below:

- How many Vine reviews and non-Vine reviews were there?
  - There is a total number of 60 paid Vine Reviews
  - There is a total number of 14,477 non-Vine reviews

![total_number](https://user-images.githubusercontent.com/107289345/194428502-66e4b719-d553-43ca-834b-f877c95371b5.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There are 34 five-star Vine reviews
  - There are 8,212 five-star non-Vine reviews
  
 ![five_star](https://user-images.githubusercontent.com/107289345/194428530-4cc367a4-a671-4efb-bf6d-b6a37947d469.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 56.7% of Vine reviews were 5-stars
  - 56.7% of non-Vine reviews were 5-stars
  
![percentage](https://user-images.githubusercontent.com/107289345/194428554-35168978-ca2a-4d64-8bb8-8501d6c65d27.png)

## Summary
  In summary, I do not believe there is any positivity bias for the reviews in the Vine program. There was a total number of 60 Vine program reviews and 34 of those reviews were 5 stars, which means about 56 percent of the reviews in the Vine program are 5 stars. An additional analysis that I would do with this dataset is to compare how many of those Vine program reviews were 2-star reviews or below. Then compare those lower star reviews to the five star reviews. However, since more than half of the vine reviews are 5 stars maybe a better comparison would be 4 star reviews to the lower star reviews. Lastly, the vine reviews share the same percentage of 5 star reviews to non-vine reviews. 
