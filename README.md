# Analysis of Amazon reviews

## About the data
The data set which is over 32G includes over 130+ million customer reviews available in TSV files in the amazon-reviews-pds S3 bucket in AWS US East Region. This dataset was constructed to represent a sample of customer evaluations and opinions, variation in the perception of a product across geographical regions, and promotional intent or bias in reviews. 

## Method
● Basic data prep: Tidy and Clean in general; Drop records with missing or abnormal values     
● Query and EDA: Spark DataFrames, SparkSQL, MapReduce  
● Data visualization: matplotlib, wordcloud packages  
● Sentiment Analysis: Sentiment Lexicon  
● Modeling: logistic regression  

## Exploratory Data Analysis
● Customer tends to express strong feelings when it comes to product reviews  
  ◎ lower star rating tend to be more helpful for customer  
● Vine membership plays an important role among Amazon customer reviews  
  ◎ Vine member's review is more helpful  
  ◎ Vine member tends to give objective opinion  
● Star rating is in consistent with sentiment preference  

## Model finding
● Review sentiment, Star rating score and vine membership is the top three important features that influence the helpfulness of a review

## Advice
For merchant, they should mananage review that gives low star rating and take measures to prevent low star rating in advance. Furthermore, they could invite vine member to try presell product and write product reviews.   
For Amazon, customer review could rank by helpfulness in default, so that customer would see reviews that help they make better decision first.
