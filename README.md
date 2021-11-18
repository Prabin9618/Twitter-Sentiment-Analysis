# Twitter Sentiment Analysis

### Problem Background:
Sentiment analysis refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics. For any products launched by companies, it is very important that it is consumer facing and end user is satisfied with the product. Hence, sentiment analysis is performed to gather opinions and contribute towards improvement of the product.

### Objective:
Perform sentiment analysis on real time twitter data(Data is obtained via API call with search term entered by user)

### Steps performed:
1. A sample US Airline sentiment tweets data is taken as a dataset and pre processing, cleaning, wrangling performed
2. As we are dealing with text data, nltk library(used for Natural Language Processing) is used
3. Text is cleaned of numbers, punctuations and stemming/lemmatization as well as vectorization(Tf-idf) is performed on the text
4. A model is built using KNN classifier and accuracy tested. The model and vectorizer are saved in a pickle file for using it in real-time analysis
5. Usage of tweepy module is done providing the access token, secret and api key, secret to connect to twitter API and extract latest tweets related to a specific text
6. The tweets are cleaned, vectorized and fed to the model to do a sentiment analysis and predict the sentiments
7. Negative tweets can be skimmed over to look for the reasons of dissatisfaction. Accordingly, improvements are made

### Industrial Use case:
Let's say you are going to launch a product and made a public announcement revealing few of the features of the product. Twitter is a place where whole world is connected and people can express their views on your product tagging your product(# tags). You can do a sentiment analysis to get all the negative tweets and look for areas of improvement. Afterall, the product success depends on consumer opinion and public use.

Sentiment analysis is extremely useful in social media monitoring as it allows us to gain an overview of the wider public opinion behind certain topics. Being able to quickly see the sentiment behind everything from forum posts to news articles means being better able to strategise and plan for the future.
