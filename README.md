# Amazon_Vine_Analysis

## Introduction
### Big Data

According to Oracle,  big data is data that contains greater variety, arriving in increasing volumes and with more velocity. This is also known as the three Vs.
Put simply, big data is larger, more complex data sets, especially from new data sources. These data sets are so voluminous that traditional data processing software just can’t manage them. But these massive volumes of data can be used to address business problems you wouldn’t have been able to tackle before.

## The purpose of this analysis

![image](https://user-images.githubusercontent.com/89704371/179875419-cd4aa444-83da-4bbc-9bdf-dd3b9c2da6b7.png)

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project,we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, we will write a summary of the analysis to submit to the stakeholders.

### Deliverables

* Deliverable 1: Perform ETL on Amazon Product Reviews
* Deliverable 2: Determine Bias of Vine Reviews

### Tools used

* PostgresSQL
* Google Colab
* GitHub
* GitBash
* Python Programming Languauge
* Amazon AWS(S3 & RDS )

### Data sources

https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Ebook_Purchase_v1_00.tsv.gz

## Results

### How many Vine reviews and non-Vine reviews were there?

![image](https://user-images.githubusercontent.com/89704371/180047532-961bff0f-386d-493d-bde8-70bf1623d211.png)

Above snapshot dispalys the count for each kind of review after a filtered dataframe.  Most of the reviews were no-vine reviews. And from the image it can be noted that for this review dataset there were no vines.


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![image](https://user-images.githubusercontent.com/89704371/180048458-d2e32e8f-b909-4edd-a55b-c389c431bc5a.png)

There were  24673 no vine reviews and almost zero vine reviews with 5 stars.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![image](https://user-images.githubusercontent.com/89704371/180049099-f93cc77f-9501-444c-b8b2-3e3142d0e1e8.png)

Non vine reviews had a percentage of 0.13 % while the rest had a close to none percentage.

## Summary

The data is biased. The reviews are mostly non-vine reviews. This is biased sice we dont get to analyze with the vine reviews and make quality comparisons.

## Recommendations

The study would need to redesigned to products that have a specific threshhold of reviews . The best way to adjust this is to use a data set that is less bised and includes both vine reviews and non vine reviews.



