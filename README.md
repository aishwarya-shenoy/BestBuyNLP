# BestBuyNLP
Text Classification of Best Buy customer call data using NLP techniques

# Overview
The goal of this project is  to classify best buy's customer call data into distinct categories, including product inquiries, order updates, payment methods, return requests, and more. By leveraging advanced Natural Language Processing (NLP) techniques and machine learning models, this model is designed to accurately predict query types from conversations, providing Best buy with the opportunity to enhance customer relationship management strategies.

# Key Features
1. Data Preprocessing: Extraction of key words from the customer conversation by removing stop and courtesy words, repeated patterns across all calls, Parts of speech tagging, stemming and lemmatization.
2. Feature Engineering: Employs the TFIDF vectorizer and Bag of Words for transforming preprocessed text into a suitable format for model training.
3. Model Training: Naive Bayes Classification of the vectors.
4. Evaluation: Measures model performance using accuracy and F1 score metrics on validation datasets to ensure reliability and effectiveness.

# Dataset
The data consists of 2 columns : The speech to text translation of calls between the service agent and customer, and a label indicating the nature of the call. Each call is linked to exactly 1 label.

# Future Scope (In progress)
Implementing SVM, Random Forest and MLP to enhance classification accuracy.

