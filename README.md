# X-Twitter-_API-_Sentimental_Analysis

# 1. Sentiment Analysis on Sentiment140 Dataset using BERT
#### This project uses the Sentiment140 dataset to perform sentiment analysis using BERT, classifying tweets into positive and negative categories.

## Key Highlights:
#### Dataset: Utilized the Sentiment140 dataset, which contains 1.6 million labeled tweets.
#### Preprocessing: Cleaned the text data by removing special characters, URLs, user mentions, and extra spaces.
#### Model: Leveraged the BERT model (bert-base-uncased) for sequence classification, fine-tuning it for binary sentiment classification (positive or negative).
#### Accuracy: Achieved an accuracy of 87% on the sentiment classification task.
#### Training: Trained the model on 10% of the dataset (for faster experimentation), using PyTorch and Hugging Face's transformers library.
#### Evaluation: Evaluated the model's performance using accuracy and loss, and fine-tuned it with an optimizer and learning rate scheduler.
#### Deployment: Saved the trained model and tokenizer for future inference tasks.
#### Inference: Implemented a sentiment prediction function that can classify new tweets as positive or negative.
#### Platform: The model was trained and evaluated on Google Colab for access to GPU acceleration.

# 2. Twitter Sentiment Analysis on Elon Musk Tweets
#### This project analyzes Twitter data related to Elon Musk, using Tweepy, TextBlob, and VADER for sentiment analysis.

#### Key Highlights:
####  Data Collection: Collected real-time tweets using the Tweepy API, filtered by the hashtag #ElonMusk and excluding retweets.
#### Text Cleaning: Preprocessed tweet text by removing mentions, URLs, and special characters using regular expressions.
#### Sentiment Analysis: Applied multiple sentiment analysis methods:
#### TextBlob for calculating polarity and subjectivity.
#### VADER to classify sentiment as positive, negative, or neutral.
#### Sentiment Distribution: Visualized sentiment distribution using a pie chart to understand the overall sentiment trends in the collected data.
#### Word Cloud: Generated a word cloud to visualize the most frequent terms in the tweets.
#### Text Analysis: Analyzed tweet length and word count across different sentiment categories, revealing interesting patterns in tweet size based on sentiment.
#### Export: Saved the results in a CSV file and uploaded them to Google Drive for easy sharing and access.
#### Visualization: Created visual representations such as the word cloud and sentiment distribution to make the results more accessible and comprehensible.
#### Technologies Used:
#### Python Libraries: tweepy, pandas, numpy, re, nltk, textblob, matplotlib, wordcloud, transformers, torch
#### Data Processing: Pandas for data manipulation, Regex for text cleaning, and nltk for sentiment analysis.
#### Machine Learning: Fine-tuning BERT for sentiment classification, using PyTorch for model training.
#### Data Storage: Exported results to CSV and saved models to Google Driv

# 3. Sentiment Analysis with Logistic Regression on Kaggle Sentiment140 Dataset
#### This project performs sentiment analysis using logistic regression on the Sentiment140 dataset from Kaggle, applying text preprocessing and machine learning techniques.

## Key Highlights:
#### Dataset: Downloaded the Sentiment140 dataset from Kaggle, containing 1.6 million tweets labeled as positive or negative.
#### Dataset: Downloaded the Sentiment140 dataset from Kaggle, containing 1.6 million tweets labeled as positive or negative.
#### Preprocessing:
#### Cleaned the tweet text by removing non-alphabetic characters, converting text to lowercase, and applying stemming using Porter Stemmer.
#### Removed stopwords using nltk's stopword list.
#### Model: Trained a Logistic Regression model using TF-IDF vectorization of the tweet text.
#### Performance:
#### Achieved an accuracy of 79.87% on the training data.
#### Achieved an accuracy of 77.67% on the test data.
#### Prediction: Implemented functionality to classify tweets as positive or negative.
#### Model Saving: Saved the trained model using pickle for future use.
#### : The project was implemented in Google Colab and leveraged Kaggle's API for dataset download.
#### Technologies Used:
#### Python Libraries: tweepy, pandas, numpy, re, nltk, textblob, matplotlib, wordcloud, transformers, torch, sklearn
#### Data Processing: Pandas for data manipulation, Regex for text cleaning, and nltk for sentiment analysis.
#### Machine Learning: Fine-tuning BERT for sentiment classification, using PyTorch for model training. Also implemented Logistic Regression for Kaggle dataset sentiment analysis.
#### Data Storage: Exported results to CSV and saved models to Google Drive.
#### Visualization: Created visual representations using matplotlib and wordcloud.
