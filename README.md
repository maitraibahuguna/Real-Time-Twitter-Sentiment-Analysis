# Problem Statement
Build a system for realtime twitter sentiment analysis to analyze the emotions of the crowd about a particular topic.

# Real_time_Twitter_Sentiment_Analysis
Sentiment analysis refers to the application for processing natural language, text analysis, computational linguistics, and biometrics to methodically recognize, extract, quantify, and learn affective states and subjective information.<br>
Twitter, being one among several popular social media platforms, is a place where people often choose to express their emotions and sentiments about a brand, a product or a service. Analyzing sentiments for tweets is very helpful in determining people's opinion as positive, negative or neutral. This project evaluates the people's sentiment about a person, trend, product or brand.<br>
Twitter API is used to access the tweets directly from twitter and build a sentiment classification for the tweets. The outcome of the analysis is depicted for positive, negative and neutral remarks about their opinions using visualization techniques such as histogram and Pie chart.<br>

In this project, we use twitter data for Narendra Modi and Rahul Gandhi. Since COVID-19 pandemic is going we analyze how people of india feel about these two personalities. The sentiments of people are being analyzed in realtime. There are two files, one for extracting the tweets in real time(Real-time Twitter Sentiment Analsis .ipynb) and analyzing them. Then in another file (Real-TimePlot with Matplot lib for Twitter Sentiment.ipynb), the sentiment.csv in being read in realtime and then finally plotting them in form of matplot lib.

# Conclusion
The tweets are extracted from the twitter account using consumer key, consumer secret key, access token and access token secret. We authorize tweepy to access twitter account and hence get the information from the timeline. After extracting the twitter information about Narendra Modi and Rahul Modi and analyzing the sentiments by realtime plot by matplot lib, it has been noticed that people have positive sentiments about both the politicians but people and talking and thinking more positive about Rahul Gandhi.
