# Spam Mail Detection using Logistic Regression
## Project Overview
This project focuses on detecting spam emails using a Logistic Regression model. It leverages Natural Language Processing (NLP) techniques to classify email messages as either Spam or Ham (Not Spam). The text data is transformed using TF-IDF vectorization, and the model is trained on a labeled dataset of 5,500+ emails.

## Model Details
Algorithm Used: Logistic Regression (Scikit-learn)
Text Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency)

### Preprocessing:
Null value handling
Label encoding (spam = 0, ham = 1)
Lowercasing, stopword removal
Train-Test Split: 80:20

## Results
Dataset	Accuracy
Training Set	96.76%
Test Set	96.66%
Model shows excellent generalization on unseen data.
Successfully predicts spam/ham classification on custom inputs.

## Sample Prediction
Input: "I'm searching for the right words to thank you..."
Output: ✅ Ham Mail
