# Portfolio-Management
Team10

We are submitting 3 Python notebooks.

Pre-requisites:

Python 3
Google Cola or Jupyter


Modules to import:
tensorflow-gpu==1.15.0
gym-anytrading
stable-baselines
gym
Pandas
numpy
tweepy
textblob


How to run modules:

1. twitterData: 
In this notebook we have gotten the tweets, and calculated the TS polarity using text blob, and also compute the positive, negative and neutral sentiments from nltk library.

To run this notebook add your twitter API tokens and Keys as required and run all the cells.

As the getting of data will take a lot of time, we have attached the processed csv for ease to run the other notebooks

2. LSTM
In this notebook we are using LSTM model to predict the stock price

To run this notebook, open it google colab or Jupyter notebook, and run all the cells. 

3. A2cwithoutsentiment

Here, we are using the a2c model,only using historic data
To run this notebook, open it google colab or Jupyter notebook, and run all the cells. 

4. A2c
Use the csv file for the sentimental analysis part.
Here, we are using the a2c model, with technical indicators, with OHLC, and sentimental analysis
To run this notebook, open it google colab or Jupyter notebook, and run all the cells. 






