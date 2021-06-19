# Amazon_Vine_Analysis
## Project Overview
In the following project, we extracted Amazon product reviews from a dataset stored on Amazon S3. We then leveraged the cloud to streamline the ETL process with AWS, Apache Spark, and PostgreSQL. 
We used the relational database service provided by AWS to create a cloud-hosted server in pgAdmin. From there, we used Google Colab to harness the computing power of Apache Spark to extract, transform, and load the dataset containing the product reviews into our newly created cloud database in pgAdmin. There were a variety of product datasets to choose from, ranging from apparel to consumer electronics. However, in our analysis, we are focusing on software product reviews. The purpose of our project is to determine if there is any bias in the reviews coming from members that are part of the Amazon Vine program and to explore the efficacy of big data technologies coupled with cloud computing resources. 
## Resources
- Google Colab
- Apache Spark & PySpark
- pgAdmin & PostgreSQL 
- AWS
## Results
The following queries highlight the successful ETL process:

<p align = "center">
<img src="images/customers.png" width=450>
<img src="images/products.png" width=450>
</p>          

<p align = "center">
<img src="images/review.png" width=400>
<img src="images/vine.png" width=450>
</p> 

- There are a total of 248 reviews from products included in the vine program.
  - Of those 248 reviews, 102 are five-star reviews, which amounts to roughly 41 % of total reviews.

- There are a total of 17,514 reviews from products that are not part of the vine program.
  - Of those 17,514 reviews, 5,154 are five-star reviews, which amounts to roughly 29 % of total reviews.
## Summary
