# US Airline Sentiment Analysis on Twitter

## Introduction
Sentiment analysis involves analyzing opinions or emotions regarding a specific topic using data such as text. This project focuses on tweets about six major U.S. airlines to classify the sentiment as positive, negative, or neutral. The goal is to help companies understand customer feedback and respond effectively.

## Usage

This dataset can be utilized for various tasks related to sentiment analysis, including:

1. *Sentiment Classification*:
   - Train machine learning models to classify tweets as positive, negative, or neutral based on customer feedback about airlines.

2. *Exploratory Data Analysis (EDA)*:
   - Analyze the distribution of sentiments across different airlines.
   - Visualize trends in sentiment over time and identify common issues raised by customers.

3. *Text Preprocessing*:
   - Clean and preprocess tweet text for sentiment analysis, including tokenization, stop-word removal, and lemmatization.

4. *Feature Extraction*:
   - Use techniques like TF-IDF or word embeddings to convert text data into numerical features for modeling.

5. *Model Evaluation*:
   - Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score to assess how well the models classify sentiments.

6. *Insight Generation*:
   - Generate insights on customer sentiment trends to help airlines improve their services and customer satisfaction.
  
## Libraries Used
- **NumPy:** Library for numerical operations and array manipulations.
- **Pandas:** Data manipulation and analysis tool, particularly for structured data.
- **Matplotlib:** Plotting library for creating static and interactive visualizations.
- **Seaborn:** Statistical data visualization library based on Matplotlib.
- **NLTK:** Natural Language Toolkit for text processing tasks.
- **Scikit-learn:** Comprehensive library for machine learning and model evaluation, including logistic regression.


## Exploratory Data Analysis
### Attributes of the Dataset
- **tweet_id:** Unique identifier for each tweet.
- **airline_sentiment:** Sentiment of the tweet (positive, neutral, negative).
- **airline_sentiment_confidence:** Confidence score for the sentiment.
- **negativereason:** Reason for a negative sentiment (only for negative tweets).
- **negativereason_confidence:** Confidence score for the negative reason.
- **airline:** The airline mentioned in the tweet.
- **airline_sentiment_gold:** Gold standard sentiment (if available).
- **name:** Twitter username.
- **negativereason_gold:** Gold standard negative reason (if available).
- **retweet_count:** Number of retweets.
- **text:** The tweet text.
- **tweet_coord:** Coordinates where the tweet was sent from.
- **tweet_created:** Timestamp of when the tweet was created.
- **tweet_location:** User-specified tweet location.
- **user_timezone:** User-specified timezone.

## Links
- [Google Colab](https://colab.research.google.com/drive/1sQQz9XpdPrBy95ffp0YQNt1gvdJe1can?usp=sharing)
- [Dataset](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)

## Credits

This file was created by:
- [Joud Ahmad Al-huthaly](https://github.com/BYXDATA)
- [Nehal Hamed Al-zahrani](https://github.com/nehal3589)
