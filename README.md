# Personalized-Book-Recommendation-System
This project implements a personalized book recommendation system that predicts whether a user will like a book based on a combination of user preference history and book genre metadata. It follows a hybrid recommendation approach, integrating user-specific information with NLP-based content features to make data-driven recommendation decisions.

##  Overview
This project implements a **hybrid recommendation system** that predicts whether a user will like a book based on:
- User preference history
- Book genre metadata (NLP)

The system is built using **Naïve Bayes** and demonstrates scalable feature engineering with sparse matrices.

##  Why Naïve Bayes?
- Efficient for high-dimensional sparse data
- Commonly used in recommender system baselines
- Interpretable probabilistic outputs

## Architecture
- User ID → One-hot encoding
- Book genres → NLP vectorization
- Features combined → Multinomial Naïve Bayes

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- Confusion Matrix

## Example Use Case
Predict whether a user will like a new book before recommending it.

##  Tech Stack
Python · Pandas · Scikit-learn · NLP · Sparse ML

