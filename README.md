# Sentimental-analysis-using-twitter-dataset-in-apache-pyspark

## Requirements 

1. Google colab or Pyspark
2. PostgreSQL
3. Tweepy Acoount (for extracting live tweets)

## Libraries Required

1. psycopg2
2. tweepy
3. json
4. sqlalchemy
5. pyspark
6. langid
7. nltk
8. re
9. string
10. HashingTF
11. IDF
12. Tokenizer
13. Pipeline
14. NaiveBayes
15. MulticlassClassificationEvaluator

## Steps to run project

1. Run streamingtweets
2. Run removing_retweets
3. Then extract raw tweets from postgresql 
4. Download 'Sentiment140 dataset with 1.6 million tweets' from the kaggle
5. Run big_dataJcomponent

## Description of Project

In this project I have performed sentimental analysis using Machine learning model (NaiveBayes) in Apache pyspark. In first step I have extracted live tweets regarding topic "trump" and storing it into postgresql. Then extracted the raw tweets from the postgresql , and dowloaded dataset from kaggle of labelled tweets (1.6 million) in order to train and test my machine learning model 'NaiveBayes'.

My idea behind doing project was to train machine learning model using 1.6 million tweets and then use the same model to get the sentiments from the raw tweets of Donald trump.
