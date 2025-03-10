# sentiment_analysis
 YouTube comments sentiment analysis project using Natural Language Processing (NLP). With 691,400 records and four key columns (id, comment_text, likes, replies)
NLP Sentiment Analysis on YouTube Comments

Overview

This project performs sentiment analysis on a dataset of YouTube comments using Natural Language Processing (NLP) techniques. The dataset consists of 691,400 records with columns: id, comment_text, likes, and replies. The goal is to analyze the sentiment of each comment, visualize common words, and identify the most frequently used emojis.

Features

Data Cleaning & Preprocessing: Removed special characters, stopwords, and unnecessary spaces.

Sentiment Analysis: Used TextBlob to compute polarity scores for each comment.

WordCloud Visualization: Generated a word cloud of frequently used words.

Emoji Analysis: Identified and counted the most frequently used emoji in the dataset.

Data Insights: Extracted valuable insights from YouTube comments.

Technologies Used

Python

Pandas (Data Cleaning & Manipulation)

TextBlob (Sentiment Analysis)

Matplotlib & Seaborn (Data Visualization)

WordCloud (Word Frequency Analysis)

emoji (Emoji Analysis)

Installation

Usage

Load the dataset

Run the notebook cells to clean the data

Perform sentiment analysis using TextBlob

Visualize the most commonly used words and emojis

Results

Polarity Distribution: Analyzed the overall sentiment of YouTube comments.

WordCloud: Displayed frequently used words in positive and negative comments.

Emoji Insights: Identified the most frequently used emoji in the dataset.

Future Improvements

Implement VADER for better sentiment classification.

Use Transformers (BERT) for advanced sentiment analysis.

Deploy the model as a FastAPI endpoint for real-time sentiment analysis.

Contributing

Contributions are welcome! Feel free to fork the repository, raise issues, or submit pull requests.

License

This project is open-source and available under the MIT License.

