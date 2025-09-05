# MBTI-Personality-Prediction-Using-Machine-Learning-and-NLP
MBTI Personality Prediction – Predict users’ MBTI personality types from text using Machine Learning and NLP. Includes code and detailed report for full reproducibility.
MBTI Personality Prediction Using Machine Learning and NLP

Author: Fateme Taroodi
Date: September 05, 2025

## Overview

This project predicts MBTI personality types based on users’ text using Machine Learning (ML) and Natural Language Processing (NLP) techniques. The MBTI divides personalities into 16 types along four dimensions:

Introversion (I) / Extraversion (E)

Intuition (N) / Sensing (S)

Thinking (T) / Feeling (F)

Judging (J) / Perceiving (P)

By analyzing users’ posts, this project builds models to predict personality traits automatically, which can be used for personalized content, online behavior analysis, and psychological research.

## Contents

Code: Data_Science_Final_Project.ipynb – Full implementation including data preprocessing, feature engineering, text vectorization, model training, and evaluation.

Documentation: MBTI Personality Prediction Using Machine Learning and NLP.docx – Detailed report on methodology, data analysis, visualizations, and conclusions.

## Key Features

Text cleaning, normalization, and lemmatization

Sentiment analysis and part-of-speech tagging

Metadata feature extraction (punctuation, word count, emojis, links)

Text vectorization: TF-IDF and Count Vectorizer

Separate ML models for each MBTI dimension using Logistic Regression, Naive Bayes, and Random Forest

Prediction system for new input text

## Results (Holdout Dataset)

| Dimension | Accuracy |
| --------- | -------- |
| I/E       | 69%      |
| N/S       | 66.7%    |
| T/F       | 77%      |
| J/P       | 54%      |


T/F dimension shows the best prediction accuracy
J/P dimension is more challenging


## Summary

This project demonstrates how textual data can be used to predict personality types. The pipeline combines NLP techniques, feature engineering, and ML algorithms to achieve meaningful results. It can be extended by using advanced models (like XGBoost or LSTM) or by collecting more balanced datasets. The project provides both the code for reproducibility and a detailed report for understanding the methodology.



