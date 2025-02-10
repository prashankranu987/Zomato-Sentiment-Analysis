# Zomato-Sentiment-Analysis
This project performs sentiment analysis on Zomato restaurant reviews, classifying them as positive or negative using **Natural Language Processing (NLP)** techniques and the **Naive Bayes classifier.**

**Requirements:**

numpy, pandas, matplotlib, sklearn, nltk, wordcloud

**Dataset:**

The dataset consists of restaurant reviews, each labeled as either positive or negative. It includes the text of the review and the corresponding sentiment.

**Project Overview**

**1.Data Preprocessing:**

->Clean text by removing special characters and stopwords.

->Convert all text to lowercase and apply stemming.

**2.Feature Extraction**:

->Transform text into numerical features using the Bag of Words model.

**3.Model Training**:

->Train a Naive Bayes classifier on the prepared dataset.

**4.Visualization**:

->Generate a word cloud to visualize frequent words in the reviews.

**5.Model Evaluation**:

->Evaluate the model using confusion matrix and accuracy score.
