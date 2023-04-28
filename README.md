# Sentiment Analysis.Classification

![image](https://user-images.githubusercontent.com/131600014/235051213-1b1bd346-aed4-44e3-b3c0-0b1ff592d0b0.png)

In this project we have done sentiment analysis of covid 19 tweets for the year 2020.Familiarized and cleaned the data by doing preliminary analysis, and dealt with null values performed EDA.Removed html tags and unwanted words from the text data. Tokenization and stemming functions are applied. Extracted hashtags belonging to different classes. Used count vectorization for vectorizing the tweet text. Implemented multiple classification models for multi class classification.

## Problem Objective
This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then. The names and usernames have been given codes to avoid any privacy concerns. You are given the following information: Location, Tweet At, Original Tweet, Label

## EDA Insights
- Maximum percentage of tweets is positive tweets with 27.97% whereas lowest is extremely negative tweets 13.05%.
- Maximum number of tweets happened on 19th and 20th march. This may be because on 19th march lockdown was announced worldwide.
- Around 8000 people have tweeted of length more than 250 words.
- Most number of tweets has been done from London followed by New york.
- Coronavirus,covid,grocery store,supermarket,retail are the main words which is used more frequently in tweets whose sentiment is neutral. People were worried about their groceries because everything was closed.
- Coronavirus,price,help,thank,covid,supermarket,grocery store,people,need,hand sanit,good food are the words which is used most no of times in tweets whose sentiments are positive. May be this was done for the frontliners people who were providing aids to the citizens.
- Covid,coronavirus,supermarket,toilet paper,panic,need,stock,crisis,food,buy are the words which is most used in the tweets whose sentiments are negative. May be these tweet are done by the people where the help didn't reached and their stocks got over.

## Data Preprocessing
- The preprocessing of the text data is an essential step as it makes the raw text ready for mining.
- The objective of this step is to clean noise those are less relevant to find the sentiment of tweets such as punctuation, special characters, numbers, and terms which don’t carry much weightage in context to the text.
- Stop words are those words in natural language that have a very little meaning, such as "is", "an", "the", etc.To remove stop words from a sentence, you can divide your text into words and then remove the word if it exits in the list of stop words provided by NLTK.
- Stemming is a rule-based process of stripping the suffixes (“ing”, “ly”, “es”, “ed”, “s” etc) from a word. For example – “play”, “player”, “played”, “plays” and “playing” are the different variations of the word – “play”.
- In tokenization we convert group of sentence into token . It is also called text segmentation or lexical analysis. It is basically splitting data into small chunk of words. Tokenization in python can be done by python NLTK library’s word_tokenize() function

## Machine Learning Models
We have applied Logistic Regression, Passive Active Classifier, Support Vector Classification, Random Forest Classifier, Decision Tree Classifier, Knn classifier.

<img width="494" alt="image" src="https://user-images.githubusercontent.com/131600014/235054540-a6aad023-b913-46cc-8c0e-dff20c4732a7.png">

## Result
We can conclude that Logistic Regression is the best model for our dataset with an accuracy of 79%.
