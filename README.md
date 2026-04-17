# financial-nlp-stock-prediction

🚀 Overview

This project explores the use of Natural Language Processing (NLP) and Machine Learning to predict short-term stock price movements based on financial news sentiment.

It combines textual sentiment analysis, contextual embeddings, and market indicators with a Bayesian Deep Learning model to generate predictions along with uncertainty estimates.


🎯 Problem Statement

Can financial news sentiment be used to predict stock price movements?

Traditional models rely only on numerical data, ignoring the rich information present in news text. This project bridges that gap.


🛠 Tech Stack

Language: Python

Libraries:pandas, numpy, scikit-learn, PyTorch / TensorFlow, matplotlib, seaborn

NLP Models:

FinBERT

LSTM

CNN

Bayesian CNN (SGLD)


📂 Dataset

Financial news headlines (Reuters, Bloomberg, Yahoo Finance)

Stock price data (via yfinance)

👉 Headlines were aligned with next-day stock movements


⚙️ Methodology

🔹 Text Preprocessing

Tokenization & lowercasing

Stopword removal

Lemmatization

Noise removal

🔹 Feature Engineering

📊 Sentiment Features

VADER

TextBlob

🧠 Contextual Embeddings

FinBERT for financial text understanding

📉 Market Features

Price change

Volatility

Trading volume

🔹 Models Used

📌 Classical ML

Logistic Regression

SVM

Random Forest

📌 Deep Learning

LSTM

CNN

🚀 Advanced Model

Bayesian CNN with SGLD

Provides predictions + uncertainty estimates

Useful in volatile markets

