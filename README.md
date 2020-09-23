# Analyzing 10GB of Yelp Data

This project is to analyze Yelp’s Reviews, Businesses and Users dataset. This dataset is from [kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset), which is pulled into a public s3 bucket: s3://yelp-reviews-businesses-datasets/yelp_academic_dataset_business.json

**Create a Cluster on AWS EMR**  
  * Provision the hardware  
  * Configure Jupyter Notebook connected to the cluster
  
**Run Spark Cluster Tasks via Jupyter Notebook**  

## Analysis
  Part I: Installation and Initial Setup   
  
  Part II: Analyzing Categories (Business dataset)    
  - how many unique categories are represented in this dataset?  
  - What are the top 20 most popular business categories?  
  
  Part III:  Do Yelp Reviews biased from the average rating? (Review dataset)  
  - Is it true that people who write a review are those who are more dissatisfied or more satisfied with the service received？
    
  Part IV: Analzing Users (User dataset)
  - What is the number of users by years？
  - What are the states with the most reviewers? 


## Cluster and Notebook Configurations

![ScreenShot](https://github.com/xianchen2/Analyzing_10Gb_of_Yelp_Reviews_Data/blob/master/Cluster%20Configuration.png)

![ScreenShot](https://github.com/xianchen2/Analyzing_10Gb_of_Yelp_Reviews_Data/blob/master/Notebook%20Configuration.png)
