# Sentiment-Analysis
Sentiment Analysis is one of the problems of NLP where models can detect opinion out of text. The text may be tweets about a business, product reviews by various users etc. and the opinion could be positive, negative or neutral.

This repo includes Sentiment Analysis on [US Airline Twitter Dataset](https://www.kaggle.com/crowdflower/twitter-airline-sentiment#Tweets.csv) using ULMFiT.

[SentimentAnalysis_EDA_lstm.ipynb](https://github.com/as2092/Sentiment-Analysis/blob/master/SentimentAnalysis_EDA_lstm.ipynb)
has EDA of the dataset and Sentiment Analysis using different models.
  1. Bi-directional LSTM with custom embeddings
  2. Bi-directional LSTM with pre-trained embeddings(Glove)
  3. Bi-directional LSTM with pre-trained embeddings(Glove) on cleaned data (removing special chars, twitter handles etc.)
  
[SentimentAnalysis_ULMFiT.ipynb](https://github.com/as2092/Sentiment-Analysis/blob/master/SentimentAnalysis_ULMFiT.ipynb)
has the Sentiment Analysis using [ULMFiT](https://arxiv.org/abs/1801.06146) which has the transfer learning as its core.
