# Covid-19-NLP-text-classification

## Description
Classifying tweets about Covid-19 into 5 Sentiment groups; Extremely Negative, Negative, Neutral, Positive, Extremely Positive
The tweets were pulled from twitter and names are usernames were given codes to avoid any privacy concerns 

The process it took to create this notebook is as follows:

## 1. Analysing the Data
The are 44955 tweets in the data.

After looking through both the train and test data, i saw that the two datasets where gotten from the same distribution; so I Decided to concatenate both of them to make preprocessing and visualization easier.
Some observations I made from the visualisations and analysis include:
### Distribution of Classes 
The classes were distributed as follows: Extremely Negative: 14%, Negative: 24%, Neutral: 19%, Positive: 28%, Extremely Positive: 16%. Therefore the data is quite unbalanced
### Average words in the tweets
Neutral sentiments have the fewest words, the more extreme the sentiments get in both the positive and negative sense, the more words are used.
### Common Stop Words 
The tweets have a lot of stop words, needs to be removed
### Hashtags 
The most used hashtags in the tweets include: coronavirus, Covid_19, Coranavirus, COVID2019, coronavirus COVID19, COVID19, etc.
### Mentions 
The twitter accounts mention the most include: realDonaldTrump, YouTube, amazon, Tesco, BorisJohnson, FTC, sainsbury, McKinsey, piersmorgan, narendramodi, etc. 

## 2. Preprocessing the Data 
