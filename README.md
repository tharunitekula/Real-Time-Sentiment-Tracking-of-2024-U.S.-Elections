# Real-Time-Sentiment-Tracking-of-2024-U.S.-Elections

This project focuses on analyzing and tracking public sentiment on Twitter during the 2024 U.S. elections using Natural Language Processing (NLP) techniques. By collecting tweets containing election-related hashtags like #USElections, #Vote2024, #Biden, and #Trump2024, the project aims to classify these tweets into positive, negative, and neutral sentiments to understand public opinion dynamics around key political events.

**Project Overview**
Social media, especially Twitter, plays a critical role in shaping and reflecting public discourse during elections. This project tackles the challenge of sentiment analysis on noisy and unstructured Twitter data by combining traditional machine learning methods and modern deep learning approaches for sentiment classification.

**The pipeline includes:**

**Data Collection:** Streaming tweets in real-time through Twitter’s API using election-related hashtags.

**Data Preprocessing:** Cleaning and normalizing text by removing URLs, mentions, hashtags, emojis, punctuation; converting text to lowercase; stopword removal; tokenization; and lemmatization.

**Feature Extraction:** Employing TF-IDF vectorization for traditional models and Word2Vec embeddings for the deep learning model to capture semantic relationships among words.

**Sentiment Classification Models:**

**Traditional ML models:** Logistic Regression and Naive Bayes using TF-IDF features for baseline performance.

**Deep Learning model:** LSTM neural network with Word2Vec embeddings to capture contextual and sequential nuances in tweets.

**Model Evaluation:** Using accuracy, precision, recall, and F1-score metrics to compare models. The LSTM model achieved superior performance with an F1-score of approximately 0.81.

**Sentiment Trend Analysis:** Visualizing sentiment shifts over time and correlating them with major events such as debates, rallies, and policy announcements to provide insights into public mood swings.

**Key Features**
Hybrid modeling approach balancing interpretability and performance.
Robust preprocessing pipeline tailored for social media text.
Real-time data capture for dynamic sentiment tracking.
Visualization of sentiment trends aligned with political event timelines.
Insightful analysis of how public sentiment reacts to election milestones.

**Use Cases**
Supporting researchers and political analysts in understanding voter sentiment.
Helping journalists report on the real-time mood of the electorate.
Assisting campaign strategists in gauging public response to messaging.

**Future Directions**
Incorporating transformer-based models like BERT for improved contextual understanding.
Enhancing annotation quality and expanding the dataset.

Adding modules for sarcasm detection, slang normalization, and demographic/geographic analysis.

Providing more granular insights into voter behavior across different groups.
