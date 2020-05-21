# Sentiment_analysis_demonetization

the objective is to identify the various narratives given a certain topic and to label the narratives using some characteristic words/phrases. 

 

The process we will follow is summarised below:

Getting tweets talking about a certain topic
Cleaning the tweets (removing stop words etc.) 
Computing embeddings of tweets using pre-trained word embeddings (such as wor2vec)
Computing tweet embeddings with sentiment by appending a 'sentiment score' to the 'tweet embeddings'
Clustering the tweet-sentiment embeddings (each cluster representing a 'narrative')
Identifying key characteristic phrases of each narrative using TF-IDF frequencies of commonly occurring phrases 
