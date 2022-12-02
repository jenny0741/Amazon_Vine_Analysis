# Amazon Vine Analysis

## Purpose
Data analysis of written reviews was conducted using the ETL process to extract, transform, and load the data into pgAdmin. Google Colab, Amazon Web Services, pgAdmin, and PySpark (Spark Files) were used to conduct the data.

## Results
Reviews for video games was the dataset used.

Based on the table below the top 20 rows indicate there are only non-Vine reviews. 

Of all non-Vine reviews, 9 out of 20 reviews were 5-stars.

45% of non-Vine reviews were 5-stars.

![Resources/vine_df](Resources/vine_df.png)

## Summary
Based on the table in the results section, there is no positivity bias for reviews because none of the reviews were written by members of the Vine program. 

Another analysis that can be conducted would be to view if the customers that wrote reviews for certain video games have previously reviewed other games. This analysis could be used to determine how many video games customers have purchased vs. how many times they have left a review. This could be useful information that can be used to find incentives for customers to pay to become a member of the Vine program or to understand why they are not currently a customer.
