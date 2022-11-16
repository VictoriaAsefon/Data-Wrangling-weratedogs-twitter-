# We Rate Dogs Twitter Analysis


## Overview

[WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs) is a Twitter account that rates people's dogs with humorous comments about the dog. These ratings almost always have a denominator of 10, while the numerators can be greater than 10. Sometimes, they mention the breed of the dog in their tweets, and other times, they don’t.

The main objective of this project is to gather data from 3 different sources, perform data wrangling on provided data sets, store and analyze the wrangled data and also Reporting on the data wrangling efforts, analysis and visualizations.


## Data Wrangling Process

The data wrangling process involved 3 stages:

- Data Gathering
- Data Assessing (Quality & tidiness issues)
- Data Cleaning


## Data Source
The dataset used in this project is an archive of all tweets from the Twitter account @dog_rates which was provided by Udacity. This archive contains basic tweet data for over 2000 tweets up till August 1, 2017. The Data Gathering process is comprises of 3 methods of gathering data:

- WeRateDogs Twitter archive: This 'twitter-archive-enhanced.csv' data was downloaded manually and loaded into a dataframe.
- Tweet image predictions: The ‘image_predictions.tsv’ was downloaded programmatically using Python Requests library.
- Additional data from the Twitter API: Each tweet's retweet count and favorites count was queried from Twitter's API into a ‘tweet_json.txt’ file.


## Research Questions

- What are the top 10 most mentioned dog_breed?
- Which dog stage gets retweeted and favorited the most?
- What is the most rated dog breed?
- What is the most popular tweet source?


## Insights

- Golden retriever is the most mentioned dog breed.It appeared 158 times in the data.
- Pupper is the most retweeted and most favoritedog_stage with values at 401,865 and 1,253,624 respectively.
- Clumber is the most rated dog breed.
- 98% of the tweets were made from an iPhone.


```python

```
