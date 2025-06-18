# IMDB-Sentiment-Classification-NLP
IMDB Movie Review Sentiment Classification using NLP — with preprocessing, feature extraction (TF-IDF, Word2Vec), Logistic Regression, SVM, and Random Forest. Full pipeline with model evaluation.
# IMDB Movie Review Sentiment Classification (NLP)

This project demonstrates Sentiment Classification of IMDB movie reviews using Natural Language Processing (NLP) techniques.

It builds a full pipeline — from text cleaning and feature engineering, to classification using various machine learning models.

# Project Workflow

1. Data Collection
    - Load IMDB movie reviews dataset (`Imdb_data.csv`)

2. Exploratory Data Analysis
    - Review length distributions

3. Data Preprocessing
    - HTML tag removal
    - Lowercasing, punctuation removal
    - Tokenization
    - Stopwords removal
    - Lemmatization & Stemming

4. Feature Engineering
    - TF-IDF Vectorization
    - Word2Vec embeddings
    - Textual features (avg. word length, word count)

5. Model Training
    - Logistic Regression
    - Support Vector Machine (SVM)
    - Random Forest Classifier

6. Model Evaluation
    - Accuracy, Precision, Recall, F1-Score
    - Confusion Matrices
    - Model comparison

## Library Used
- pandas, numpy
- scikit-learn
- gensim (Word2Vec)
- matplotlib, seaborn
- NLTK (Natural Language Toolkit)
