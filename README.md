# YouTube Comment Sentiment Analysis

## Overview

This project aims to analyze the sentiment of comments on YouTube videos.  The goal is to provide content creators with a tool to understand public feedback on their videos, enabling them to tailor their content strategy effectively.  The project addresses the challenges of noisy and informal language common in social media, such as slang and vague expressions.

## Features

* **Data Preprocessing**: Cleans and prepares YouTube comment data for analysis.
* **Sentiment Classification**: Classifies comments into three categories: positive, neutral, and negative.
* **Model Variety**: Implements and compares several models, including:
    * TinyBERT
    * DistilBERT
    * Recurrent Neural Network (RNN)
    * Logistic Regression
    * Multinomial Naive Bayes
    * Support Vector Machine (SVM)
    * Feedforward Neural Network (FNN)
    * Long Short-Term Memory (LSTM)
* **Evaluation**: 
Uses standard classification metrics (accuracy, precision, recall, F1-score) for model evaluation.

## Results

The project evaluates the performance of the models and provides a comparison of their effectiveness in sentiment analysis of YouTube comments. Key findings are:

* Basic machine learning models achieved relatively poor performance.
* FNN and LSTM showed only marginal improvement over basic models.
* TinyBERT and DistilBERT achieved the best performance.

![Figure_1](results/figure_1.png)
![Figure_2](results/figure_2.png)
![Figure_3](results/figure_3.png)

## Future Work

* Explore fine-tuning with domain-adapted pre-trained models.
* Address class imbalance in the dataset.
* Incorporate multilingual or time-series features.

## Author
Nam Le
Darren Lie
Berny Chen
Sophie Lam
Gangsan Kim
