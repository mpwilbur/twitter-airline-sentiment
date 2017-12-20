# twitter-airline-sentiment
This is a short project on classifying the sentiment of Tweets

In this project I create a neural network model and a linear classifier model for classifying the sentiment of Airline Tweets into Positive/Neutral/Negative using pretrained GloVe vector embeddings

Main concepts - Twitter sentiment analysis, GloVe vector embeddings, Neural Network, Linear Classifier, Python, Tensorflow

Packages and data
+ Python 3
+ Tensorflow 1.4.0

Structure
+ airline_sentiment_notebook.ipynb = main Python Notebook, follow notes in notebook
+ airline_sentiment_notebook_results.ipynb = main Python Notebook after running it
+ Tweets.csv = twitter data, from https://www.kaggle.com/crowdflower/twitter-airline-sentiment/data
+ Uses Twitter GloVe vectors, 50 dimension vectors - https://nlp.stanford.edu/projects/glove/
  + Save in untrained folder as glove_twitter_27B_50d.txt - see Usage below
+ Results - this folder includes PDF and HTML of my results
+ Trained - this folder contains all results after running airline_sentiment_notebook.ipynb, see full description of this folder below

Results Folder
+ Results in PDF and HTML formats, and notebook after analysis is completed

Usage
+ Tweets.csv = twitter data, from https://www.kaggle.com/crowdflower/twitter-airline-sentiment/data
+ Must download Twitter GloVe vectors, use 50 dimension vectors - https://nlp.stanford.edu/projects/glove/
  + Save in untrained folder as glove_twitter_27B_50d.txt
+ run the airline_sentiment_notebook.ipynb notebook, will create directories for Neural Network and Linear Classifier models and will compare the accuracy of both models
