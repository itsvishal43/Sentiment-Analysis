# Sentiment-Analysis
The task is to predict the sentiment of a news article based on its title and headline.

# Dataset

This is a large data set of news items and their respective social feedback on multiple platforms: Facebook, Google+ and LinkedIn.

The collected data relates to a period of 8 months, between November 2015 and July 2016, accounting for about 100,000 news items on four different topics: economy, microsoft, obama and palestine.

This data set is tailored for evaluative comparisons in predictive analytics tasks, although allowing for tasks in other research areas such as topic detection and tracking, sentiment analysis in short text, first story detection or news recommendation.

The dataset contains news headlines and their respective information. They include

Facebook news
Google+ news
Linkedln news
The attributes for each of the tables are :

IDLink (numeric): Unique identifier of news items
Title (string): Title of the news item according to the official media sources
Headline (string): Headline of the news item according to the official media sources
Source (string): Original news outlet that published the news item
Topic (string): Query topic used to obtain the items in the official media sources
Publish-Date (timestamp): Date and time of the news items' publication
Sentiment-Title (numeric): Sentiment score of the text in the news items' title
Sentiment-Headline (numeric): Sentiment score of the text in the news items' headline
Facebook (numeric): Final value of the news items' popularity according to the social media source Facebook
Google-Plus (numeric): Final value of the news items' popularity according to the social media source Google+
LinkedIn (numeric): Final value of the news items' popularity according to the social media source LinkedIn
SentimentTitle: Sentiment score of the title, Higher the score, better is the impact or +ve sentiment and vice-versa. (Target Variable 1)
SentimentHeadline: Sentiment score of the text in the news items' headline. Higher the score, better is the impact or +ve sentiment. (Target Variable 2)
