---
title: "Nepali Twitter Sentiment Analysis"
excerpt: "Sentiment Analysis of Nepali Tweets using state-of-the-art Machine Learning models"
collection: portfolio
---

**Sentiment Analysis of Nepali Tweets using state-of-the-art Machine Learning models**

- Fetched tweets using the Twitter API
- Preprocessed each tweet's text (removed links, 'RT's, etc.)
- Detected the language, then translated all Nepali tweets into English
- Used Machine Learning models to classify the sentiment of processed tweets into 3 categories (positive, negative, and neutral).
- Kept the most likely sentiment and its corresponding probability in a CSV file


**Sentiment classification models used in this project:**

- [RoBERTa-base-sentiment](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)
- [Flair TextClassifier](https://github.com/flairNLP/flair)
- [TextBlob Polarity](https://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis)

A sample output of this project can be found <a href="https://docs.google.com/spreadsheets/d/1wGrKnm1Tm5W2G0UC0bZLfRula_YMyDyAkOn1f_yYNFI/edit?usp=sharing" target="_blank">here</a>.

`Tools Used: Python, PyTorch, Transformers, SciPy, Tweepy, Pandas, TextBlob, Flair, langdetect, googletrans`

<a href="https://github.com/ayushrajdahal/NepaliTwitterSentimentAnalysis" target="_blank">[Link to GitHub Repository]</a>