# Spam Mail Prediction

## Overview
The Spam Mail Prediction project is a machine learning application that classifies emails as either "spam" or "ham" (not spam) using a Logistic Regression model. The model is trained on a dataset of labeled emails and utilizes the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique to convert text data into numerical feature vectors.

## Features
- Classify emails as spam or ham.
- Train a Logistic Regression model using a dataset of emails.
- High accuracy on both training and test datasets.
- User-friendly input for testing new email messages.

## Technologies Used
- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Scikit-learn for machine learning
- TF-IDF for text feature extraction

## Dataset
The dataset used in this project is a CSV file (`mail_data.csv`) containing two columns:
- **Category**: Label indicating whether the email is spam (0) or ham (1).
- **Message**: The text content of the email.
