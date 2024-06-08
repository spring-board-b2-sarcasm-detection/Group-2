Sarcasm Detection on Airline Reviews

Table of Contents:
Introduction
Dataset
Preprocessing
Model Training 
Results

I. Introduction
Sarcasm detection is a challenging task in natural language processing (NLP), especially when dealing with user-generated content like reviews. This project aims to detect sarcasm in airline reviews using various deep learning and NLP techniques.

II. Dataset
The dataset was taken from Data.world. Below is the link for the dataset.
https://data.world/khushipitroda/skyratings-unleashing-23k-airline-reviews

1. The dataset consists of airline reviews is labeled as sarcastic or non-sarcastic with the help of pre-trained model.
2. It includes the following features:
3. review: The text of the review.
4. sarcasm_label: Binary label indicating whether the review is sarcastic (1) or not (0).
5. Additional features related to airline information.

III. PREPROCESSING
The preprocessing steps involved in this project include:
1. Text Cleaning: Removing HTML tags, URLs, special characters, and converting text to lowercase.
2. Tokenization: Splitting text into individual words (tokens).
3. Stop Words Removal: Removing common words that do not carry much meaning.
4. Lemmatization: Reducing words to their base or root form.
5. Handling Missing Values: Addressing any missing data in the dataset.
6. handling imbalanced classes: using SMOTE.
7. Vectorization and Encoding
8. Feature Engineering: Creating additional features like review length and number of exclamations.
