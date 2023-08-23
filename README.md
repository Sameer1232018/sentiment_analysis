# COVID-19 Tweets Sentiment Analysis

## Project Overview
This project focuses on sentiment analysis of COVID-19 related tweets. By utilizing TF-IDF and Bag-of-Words (BoW) vectorization methods, we aim to determine the sentiment expressed in these tweets. The project includes the implementation of various machine learning models and data visualization techniques to analyze and visualize the sentiment classification performance.

## Features
- **Sentiment Analysis**: The project conducts sentiment analysis on COVID-19 tweets, determining whether the sentiment is positive, negative, or neutral.

- **Vectorization Methods**: We employ both TF-IDF (Term Frequency-Inverse Document Frequency) and BoW (Bag-of-Words) vectorization techniques to preprocess the text data for analysis.

- **Machine Learning Models**: Logistic Regression, Decision Trees, Gradient Boosting, and Random Forest models are implemented for sentiment classification.

- **LSTM Model**: A separate LSTM model file is included for sentiment analysis, providing an alternative approach to classification.

- **Performance Analysis**: The performance of these models is evaluated and compared using data visualization techniques, helping to identify the most effective approach.

## Installation and Usage
1. Clone this repository to your local machine.
2. Install the necessary dependencies using the requirements file (`requirements.txt`).
3. Run the Jupyter Notebook (`sentiment_analysis.ipynb`) to access the analysis, models, and visualizations.
4. Modify and experiment with different parameters, vectorization methods, and models as desired.

## Data Sources
https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification

## LSTM Model
- The LSTM model for sentiment analysis can be found in the `lstm_sentiment_analysis.py` file. Run this file to explore the LSTM approach to sentiment classification.

## Screenshots
Screenshot 1: Sentiment Distribution
![download (4)](https://github.com/Sameer1232018/sentiment_analysis/assets/49482350/247da2ab-ee45-4d6b-83d0-a0fa44631a1c)

Screenshot 2: Word Cloud
![download (5)](https://github.com/Sameer1232018/sentiment_analysis/assets/49482350/9a782525-913d-4b7f-9ce6-718204b00f62)

Screenshot 3: The ressults
![image](https://github.com/Sameer1232018/sentiment_analysis/assets/49482350/f24568e7-0117-4d7b-b1a1-167f2161d52f)

## LSTM

Screenshot 4: Training and Validation Accuracy
![image](https://github.com/Sameer1232018/sentiment_analysis/assets/49482350/a9c92d4a-1009-4d4f-8313-5d1c540ce16d)


Screenshot 5: Training and Validation Loss
![image](https://github.com/Sameer1232018/sentiment_analysis/assets/49482350/f72ddafe-ee9b-4f24-b002-37acdc7a753c)

