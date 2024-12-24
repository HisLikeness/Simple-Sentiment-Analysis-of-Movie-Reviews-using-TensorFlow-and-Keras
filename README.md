# Simple-Sentiment-Analysis-of-Movie-Reviews-using-TensorFlow-and-Keras
## Problem Statement
The goal of this project is to train a neural network to classify movie reviews from the IMDB dataset as either positive or negative. The dataset contains a large collection of movie reviews along with sentiment labels. The challenge is to develop a model that can accurately predict whether a review is positive (the reviewer liked the movie) or negative (the reviewer didn’t like the movie).

## Dataset Information
- **Dataset**: IMDB Movie Reviews
- **Number of Entries**: 50,000
- **Features**: 
  - `review` (Text): The movie review text.
  - `sentiment` (Label): The sentiment of the review, either "positive" or "negative".

## Model Overview
The project uses a **Neural Network** model to classify movie reviews. The preprocessing steps involve:
- Lowercasing all text.
- Removing HTML tags and URLs.
- Tokenizing the reviews and removing stop words.
- Using **TF-IDF vectorization** to convert text data into a format suitable for the neural network.

The neural network architecture consists of:
- Dense layers with ReLU activation.
- A final sigmoid activation function for binary classification.

## Installation
To run this project, you will need to install the following libraries:
```bash
pip install pandas matplotlib seaborn nltk scikit-learn tensorflow
