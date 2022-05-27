# fake_news_detection
Project description
The purpose of this project is to build a classification model that would analyze a piece of news and classify it as fake or as real. Categorizing the news articles and visualizing the type of news which are labeled fake or real will also be done. 

Data
The main data we will use to build our model is from Kaggle (https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).
This dataset contains labeled news: approximately 17000 fake news and 20000 true stories. The data contains the following variables:
Title: the title of the news
Text: the text of the news
Subject: which category it belongs to (ex. Politics, Sports,...)
Date: the date the news was published

Cleaning & Exploration
For starters we must clean our dataset handling duplicates, missing values and so on. In order to gain insight from our data we would conduct an initial visualization of, for instance,  distribution of subjects, posts distribution over time and some Worldclouds with the post's contents.

Then, we’ll put into practice our model. We’ll scrape several news from multiple sources and see which provider is trustworthy and which you are better doubting and in which categories.

Method
We’ll build different classification models and compare the results using stratified accuracy. In addition, we’ll try a rule-based approach to see if it might work better than a machine learning model.
Moreover, we’ll build a scraper to get modern news to apply our model and see what kind of source is reliable and in which category.

Evaluation process
While training our models, we’ll split our data into 70% training and 30% testing and perform stratified accuracy, giving more importance to the news wrongly classified as fake, since this type of error is costlier in our case as we will be hurting the reputation of the publisher more with a false fake news.

