# Fake-news-classifier
Developed a Machine Learning model to identify whether a news is real or fake. In this problem, I used a corpus of labeled real and fake news articles to build a classifier that can use the artcles to tell whether the news is real or fake.

# Dataset
train.csv : A full training dataset with the following attributes:

- id: unique id for a news article
- title: the title of a news article
- author: author of the news article
- text: the text of the article; could be incomplete
- label: a label that marks the article as potentially unreliable. where 1: unreliable and 0: reliable

# Requirements: 
numpy, pandas, matplotlib, wordcloud, ntlk, CountVectorizer, TfidfTransformer

# Models Used
- Logistic Regression
- Naive Bayes Model
- Decision Tree Model

# Performance
- Model	Accuracy
- Logistic	96%
- Naive Bayes	84%
- Decision Tree	97%

# References
https://www.kaggle.com/c/fake-news/data
