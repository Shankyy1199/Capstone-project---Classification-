# Coronavirus_Tweet_Sentiment_Analysis_Capstone_Project
![image](https://github.com/Shankyy1199/Capstone-project---Classification-/assets/128234439/a6d0c8fc-65e0-486c-aa1a-a450504e2b46)

Summary - The project examines the variation tweet posting locations, period of posting tweets, tweet lengths and predicts the sentiments of tweets using machine learning models. It involves the application of six different machine learning models, including Logistic Regression with Grid Search CV, Decision Tree Classifier, KNN, SVM Classifier, and SGD Classifier, using Count Vectorization techniques. The conclusion highlights that the SGD Classifier model produced the best results with an accuracy score of 80.69%. This suggests that it is the most effective model for the task at hand. Also it observes that there is no overfitting in the data, which is a positive finding, as it indicates that the model generalizes well. The project suggests that the trained model can be deployed for predicting the sentiments of future tweets, implying its potential utility for sentiment analysis tasks.

In brief, the project involves analyzing Twitter data, identifying key trends and patterns, building machine learning models, and selecting the most effective model for sentiment analysis, with potential applications in predicting sentiments for future tweets.

Problem Statement - Our task is to develop a classification model to predict the sentiment of COVID-19 related tweets. These tweets have been collected from Twitter and have been manually tagged with sentiment labels. The dataset provides the following information for each tweet:

1. Location: The geographical location (if available) associated with the tweet.
2. Tweet At: The date and time when the tweet was posted.
3. Original Tweet: The actual content of the tweet related to COVID-19.
4. Label: The sentiment label assigned to the tweet, indicating whether it expresses a positive, negative, or neutral sentiment towards the topic of COVID-19.
Our goal is to create a machine learning model that can accurately classify the sentiment of these tweets into one of the following categories:

Positive Sentiment: Tweets expressing a positive sentiment towards COVID-19 (e.g., support, optimism).
Negative Sentiment: Tweets expressing a negative sentiment towards COVID-19 (e.g., fear, criticism).
Neutral Sentiment: Tweets that do not strongly express either positive or negative sentiment towards COVID-19.

Conclusions - 
1. Tweet Posting Locations: London City appears to be the primary location for tweet postings, followed by the United States. This suggests a significant presence of Twitter users in these regions.

2. Seasonal Tweet Patterns: The data indicates that the majority of tweets were posted between April and October.

3. COVID-19 Impact: The peak in tweet activity observed in April 2020 coincides with the early stages of the COVID-19 pandemic. This spike in activity is likely due to heightened global interest and concerns about the virus during that time.

4. Tweet Length: The length of tweets varied, with some being as short as 10 characters and others slightly more than 350 characters. This variation suggests that Twitter users have diverse communication styles and preferences.

5. We applied 6 different machine learing models namely, Logistic Regression with Grid Search CV, Desision Tree Classifier KNN, SVM Classifier and SGD classifier for Count Vector Vectorisation techniques.

6. We conclude that the machine is generating best results for SGD classifier  model with and Accuracy score of 80.69%.

7. Also, we observed that no overfitting is seen for the data, and we can deploy this model.

8. The sentiments of future tweets can be easily predicted using this model.


