# 22-Big-Data
NW Data Camp Homework Week 22 Homework: “Alexa, Can You Handle Big Data?”

About HW Submission
The purpose of this homework is to utilize the Extract, Transform, Load (ETL) skills by creating AWS RDS database and S3 bucket. 
Data was extracted from amazon sql server and post to PgAdmin.

Approach taken
  1. Create RDS database and S3 bucket in AWS
  2. Add new server in PgAdmin and use Schema to create tables with no value
  3. Use Colab to clean up the amazon SQL data and create dataframe for each PgAdmin table 
  4. Use Colab to write dataframe to upload data to PgAdmin databse through AWS connection

Technology used
PgAdmin, Sparks, DataFrame, AWS RDS, S3

Two datasets selected to complete Level-1 homework
  1. https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Beauty_v1_00.tsv.gz
  2. https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Kitchen_v1_00.tsv.gz
  
 Corresponding colab file used for the above datasets
  1. HW22_s3_rds_us_Beauty.ipynb
  2. HW22_s3_rds_us_Kitchen.ipynb
  
  
