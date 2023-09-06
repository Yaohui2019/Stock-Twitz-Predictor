# Stock-Twitz-Predictor

## Introduction
When deciding the value of a company, it's important to follow the news. For example, a product recall or natural disaster in a company's product chain. You want to be able to turn this information into a signal. Currently, the best tool for the job is a Neural Network. 

For this project, I'll use posts from the social media site [StockTwits](https://en.wikipedia.org/wiki/StockTwits). The community on StockTwits is full of investors, traders, and entrepreneurs. Each message posted is called a Twit. This is similar to Twitter's version of a post, called a Tweet. I'll build a model around these twits that generate a sentiment score.


## Data
The dataset is provided by a Udacity project which contains a bunch of twits with a labeled sentiment of each. The labels will be using a five-point scale: very negative, negative neutral, positive, very positive. Each twits is labelled -2 to 2 in steps of 1, from very negative to very positive respectively. 
