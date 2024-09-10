# Fake-news-Detection

This project implements a machine learning model using Logistic Regression to detect whether a given news article is real or fake. It processes a dataset of news articles, vectorizes the text using TF-IDF, and applies text preprocessing techniques such as stemming and stopword removal.

## Features:
- Preprocessing of news data using stemming and stopword removal.
- Vectorization of text data with TF-IDF.
- Logistic Regression model for classification of fake and real news.
- Command-line interface for user input to check the authenticity of news articles.

## Dataset
The dataset used is `train.csv`, which contains the following columns:
- **id**: Unique identifier for each article.
- **title**: Title of the news article.
- **author**: Author of the article.
- **text**: Full text of the article.
- **label**: Target label (1: Fake, 0: Real)

## Dependencies
- Python 3.x
- NumPy
- pandas
- scikit-learn
- nltk
- Pytorch

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/jaiwantD/Fake-news-Detection
2. Create a virutal enivronment
3. Add the dependencies (Enssure GPU is enabled)
   ```bash
   pip install numpy pandas scikit-learn nltk pytorch

