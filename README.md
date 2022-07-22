# Report on the Sentiment About Airlines Using Text Data Analysis on Tweets

## Introduction
This report analyzed more that 11,000 tweets to gauge customers’ sentiment towards the company and its major competitors. Word usage is compared between positive and negative tweets, and across airlines. Then, two predictive tools are built to classify them. A dictionary-based method and one using supervised machine-learning are compared to help the company respond better to customers in real time.

## Text preparation and word usage

Text preparation started with the removal of numbers, stopwords, punctuation, and symbols commonly used on Twitter. Very rarely used words were also removed to ease text data analysis. Term Frequency–Inverse Document Frequency (TF-IDF) weighting was carried out to help give an accurate picture of words that are most characteristic of tweets, and diminish the importance of uninformative words. TF-IDF weightings were carried out after the different groupings of documents as a TF-IDF weighted document-term matrix should not be amalgamated.

Some words are commonly associated with a positive or negative sentiment. Words of gratitude like “thanks” and “appreciate”, along with “awesome”, “great” and “amazing” are found in many positive tweets.

*Fig 1. Words most frequently used in positive tweets (TF-IDF weighted)*

![Fig 1](figures/fig1.png =100x20)

On the other hand, the language associated to delay or cancellation (“hours”, “cancelled”, “hold”, “delayed”, “time”) are commonly associated with negative tweets.

*Fig 2. Words most frequently used in negative tweets (TF-IDF weighted)*

![Fig 2](figures/fig2.png)

While commonly used words associated with a positive sentiment are similar across airlines, an overview of how negative word usage differs across airlines can help reveal specific customer complaints (Fig.6). For example, American Airlines, Southwest, and US Airways customers seemed to have troubles with cancelled flights and help service. JetBlue and United customers mostly complain about delays. Virgin America customers seem to dislike the website of the company. Many negative tweets associated to United mention “bag”, hinting at problems of luggage management by the company.

## Dictionary-based classifier

A classic method to judge the sentiment of texts is to use a dictionary. For sentiment analysis, the dictionary includes language associated with positive and negative emotions. This list of pre- selected words can be used to classify tweets by analyzing the proportion of words associated with those emotions.
The customized dictionary includes fundamental words of sentiment analysis. It also includes jargon specific to airlines to fit the context in which the dictionary is used. The selection of words is based on the analysis of their frequency in tweets after they were grouped by sentiment and TF-IDF weighted.
