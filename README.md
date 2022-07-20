# Amazon_Vine_Analysis
## Introduction
### Big Data
![image](https://user-images.githubusercontent.com/89704371/179875419-cd4aa444-83da-4bbc-9bdf-dd3b9c2da6b7.png)

According to Oracle The definition of big data is data that contains greater variety, arriving in increasing volumes and with more velocity. This is also known as the three Vs.
Put simply, big data is larger, more complex data sets, especially from new data sources. These data sets are so voluminous that traditional data processing software just can’t manage them. But these massive volumes of data can be used to address business problems you wouldn’t have been able to tackle before.

## The purpose of this analysis

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project,we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, we will write a summary of the analysis to submit to the stakeholders.

### Deliverables
* Deliverable 1: Perform ETL on Amazon Product Reviews
* Deliverable 2: Determine Bias of Vine Reviews
