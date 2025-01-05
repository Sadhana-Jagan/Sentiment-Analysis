# Sentiment Analysis

## Overview
This Jupyter Notebook demonstrates how to perform sentiment analysis using the Cardiff NLP Twitter RoBERTa model and NLTK library.
The notebook uses the Hugging Face Transformers library to preprocess text, apply a pre-trained model, and classify input text into sentiment categories like positive, neutral, and negative.

## Model
The notebook uses the pre-trained model:
1. Model Name: cardiffnlp/twitter-roberta-base-sentiment
2. Purpose: Designed for sentiment classification of Twitter data.

## Usage
Load the Model and Tokenizer: The AutoTokenizer and AutoModelForSequenceClassification classes from the Transformers library are used to load the model and tokenizer.

Input Text: Provide raw text (e.g., amazon reviews) for sentiment classification.

Tokenization: The text is tokenized using the pre-trained tokenizer to prepare it for the model.

Prediction: The pre-trained RoBERTa model processes the tokenized input and classifies the sentiment.
