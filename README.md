# Report on the Sentiment About Airlines Using Text Data Analysis on Tweets

## Introduction
This report analyzed more that 11,000 tweets to gauge customers’ sentiment towards the company and its major competitors. Word usage is compared between positive and negative tweets, and across airlines. Then, two predictive tools are built to classify them. A dictionary-based method and one using supervised machine-learning are compared to help the company respond better to customers in real time.

## Text preparation and word usage

Text preparation started with the removal of numbers, stopwords, punctuation, and symbols commonly used on Twitter. Very rarely used words were also removed to ease text data analysis. Term Frequency–Inverse Document Frequency (TF-IDF) weighting was carried out to help give an accurate picture of words that are most characteristic of tweets, and diminish the importance of uninformative words. TF-IDF weightings were carried out after the different groupings of documents as a TF-IDF weighted document-term matrix should not be amalgamated.

Some words are commonly associated with a positive or negative sentiment. Words of gratitude like “thanks” and “appreciate”, along with “awesome”, “great” and “amazing” are found in many positive tweets.

*Fig 4. Words most frequently used in positive tweets (TF-IDF weighted)*

IMAGE

