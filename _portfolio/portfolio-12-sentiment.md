---
title: "Nepali Twitter Sentiment Analysis"
excerpt: "Sentiment Analysis of Nepali Tweets using state-of-the-art Machine Learning models"
collection: portfolio
---

<img src="{{ site.url }}{{ site.baseurl }}/images/sentiments.jpeg" alt="">

**Sentiment Analysis of Nepali Tweets using state-of-the-art Machine Learning models**

This was a Notebook I made for <a href="https://www.sanzal.com" target="_blank">Project Sanzal</a> where I demonstrated my approach of classifying Sentiments of Non-English Tweets - which was later used in the project.

**What I have done in this Notebook:**

- Fetched tweets using the Twitter API
- Preprocessed each tweet's text (removed links, 'RT's, etc.)
- Detected the language, then translated all Nepali tweets into English
- Used Natural Language Processing models to classify the sentiment of processed tweets into 3 categories (Positive, Negative, and Neutral).
- Kept the most likely sentiment and its corresponding probability in a CSV file


**Sentiment classification models used in this project:**

- [RoBERTa-base-sentiment](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)
- [Flair TextClassifier](https://github.com/flairNLP/flair)
- [TextBlob Polarity](https://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis)

<a href="https://docs.google.com/spreadsheets/d/1wGrKnm1Tm5W2G0UC0bZLfRula_YMyDyAkOn1f_yYNFI/edit?usp=sharing" target="_blank">Here</a> is a sample output of this Notebook, where I have classified sentiments of K.P. Sharma Oli's last \~200 tweets.

`Tools Used: Python, Transformers, SciPy, Tweepy, Pandas, TextBlob, Flair, langdetect, googletrans`

<a href="https://github.com/ayushrajdahal/NepaliTwitterSentimentAnalysis/blob/master/Sentiment%20Analysis.ipynb" target="_blank">[Link to the Notebook]</a>

<a href="https://www.sanzal.com/" target="_blank">[Link to the Web App]</a>
