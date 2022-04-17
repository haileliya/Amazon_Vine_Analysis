# Amazon_Vine_Analysis
Used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Overview of the analysis: 

The purpose of this analysis was to analyze data from Amazon's Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. I chose a pet products Amazon dataset to conduct my analyses using PySpark, AWS RDS instance, Pandas, and Colab. 

## How many Vine reviews and non-Vine reviews were there?

- In this dataset, there are 37993 total vine reviews. This can be further broken down by paid and unpaid reviews. There were 37823 unpaid reviews, and 170 paid reviews. 

## How many Vine reviews were 5 stars? 

- There are 20,670 5-star reviews, which is 54.4% of the total reviews.

## How many non-Vine reviews were 5 stars?

- There were 20,605 5-star unpaid reviews and 65 5-star paid reviews.

## What percentage of Vine reviews were 5 stars? 

- 38.2% of paid vine reviews were 5-stars. 

## What percentage of non-Vine reviews were 5 stars?

-54.5% of unpaid vine reviews were 5-stars. 

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
