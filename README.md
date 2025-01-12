# Sentiment-Based-Drug-Recommendation-System
This project focuses on analyzing user reviews of drugs to build a recommendation system based on sentiment analysis. Using machine learning and natural language processing (NLP) techniques, the system achieves an accuracy of 93%.

Overview
The project involves analyzing over 215,000 drug reviews to extract sentiments and build a recommendation system. It combines machine learning and NLP to predict user preferences effectively.

Key Features

Machine Learning Models Used:
1. LinearSVC
2. Random Forest
3. LightGBM (LGBM)
Achieved 93% accuracy with optimized models.

NLP Techniques Used:
1. TF-IDF (Term Frequency-Inverse Document Frequency)
2. Word2Vec
3. Text preprocessing (cleaning, tokenization, etc.) to prepare reviews for analysis.
   
Data Imbalance Handling:
Used SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset and improve model performance.
Applied feature engineering to select the most relevant features for better predictions.

Challenges Addressed : 
Imbalanced Dataset: Handled with SMOTE to ensure fair model training.
Sentiment Analysis: Extracted meaningful insights from noisy, unstructured text data.
Feature Optimization: Improved accuracy through effective feature selection.

Future Improvements :
Expand the dataset to include more recent reviews.
Explore deep learning techniques like transformers (BERT, RoBERTa) for enhanced performance.
Develop a user-friendly interface for the recommendation system.
