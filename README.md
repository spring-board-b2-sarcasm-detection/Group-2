# Sarcasm Detection on Airline Reviews

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training](#model-training)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Introduction
This project focuses on detecting sarcasm in airline reviews. Sarcasm detection is an essential task in natural language processing (NLP) as it helps in understanding the sentiment of the text more accurately. Airline reviews often contain sarcastic remarks that can mislead sentiment analysis models if not properly identified.

## Scope of the Solution
1. Accurately detects sarcasm, improving sentiment analysis in airline reviews.
2. Enables real-time sarcasm detection for timely customer feedback management.
3. Scalable framework adaptable to various industries needing sarcasm detection.


## Features
- **Data Preprocessing**: Techniques for cleaning and preparing textual data.
- **Feature Extraction**: Methods to extract meaningful features from text.
- **Model Training**: Implementation of various machine learning models for sarcasm detection.
- **Evaluation Metrics**: Tools to evaluate the performance of the models.
- **Visualization**: Visual representation of data and results.

## Dataset
The dataset used for this project consists of airline reviews collected from Data.World. Each review is labeled as either sarcastic or non-sarcastic. The dataset can be found [https://data.world/khushipitroda/skyratings-unleashing-23k-airline-reviews]

## Installation
To run this project, you need to have Python installed on your system. Follow the steps below to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sarcasm-detection-airline-reviews.git
    cd sarcasm-detection-airline-reviews
    ```

## Model Training
The project supports several machine learning models, including:
- Logistic Regression
- Gradient Boosting
- Support Vector Machine (SVM)
- Random Forest
- GaussianNB
- Simple Neural Network
- LSTM
- BiLSTM
- CNN
- RNN
- CNN-LSTM

## Results
The evaluation metrics used includes accuracy, precision, recall, and F1-score.
The best model among all is the LSTM model with 90% accurate predictions.

## Acknowledgements
Kaggle for providing the dataset.
NLTK, scikit-learn, and TensorFlow for their amazing tools and libraries.
