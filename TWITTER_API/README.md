# Twitter Sentimental Analysis

This is the code for the Twitter Sentiment Analyzer. The code uses the tweepy library to access the Twitter API and the TextBlob library to perform Sentiment Analysis on each Tweet. We'll be able to see how positive, neutral or negative each tweet is as well as download the data as a csv file with polarity and subjectivity and tweets shown.
Various graphs are made for making comparisons.

##  Main Dependencies

- tweepy ( `pip install tweepy` )
- textblob (`pip install textblob`)

Other libraries used
- `import sys,tweepy,csv,re`
- `from textblob import TextBlob`
- `from wordcloud import WordCloud`
- `import pandas as pd`
- `import numpy as np`

### Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

## Steps for getting twitter API:
1) [Go to](https://developer.twitter.com/en/apply-for-access) and sign for an account.
2) After making the account,
    - Get the ConsumerKey, consumerSecret, accessToken & accessTokenSecret  
    - Then follow the code for help
    - Put your ConsumerKey, consumerSecret, accessToken & accessTokenSecret in the code.

### Talking about the CSV files:

There are 2 CSV files which were made during the process:

1) [Final.csv](https://github.com/Garvit-01/Data-Science/blob/main/TWITTER_API/Final.csv) - Contains all the tweets but not in an ___**organized**___ manner.
2) [RESULT.csv](https://github.com/Garvit-01/Data-Science/blob/main/TWITTER_API/result.csv) - It is same as Final.csv but in an ***organized*** manner.

I created RESULT.csv because to learn about the reading data from an existing file in this case ([Final.csv](https://github.com/Garvit-01/Data-Science/blob/main/TWITTER_API/Final.csv))

Link to the [code](https://github.com/Garvit-01/Data-Science/blob/main/TWITTER_API/Twitter%20Sentimental%20Analysis.ipynb) 
