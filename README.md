#📄 Resume Classification Model Training with NLP (NLTK)

This project demonstrates the training of a machine learning model to classify resumes, using NLP preprocessing techniques. While the model was trained (e.g., SVM), this project focuses on preparing text data and building a robust training pipeline, rather than generating predictions.

🔍 Project Overview

The goal is to create a pipeline that prepares resume text for machine learning:

Cleaning and preprocessing raw resumes

Applying NLP techniques using NLTK

Converting text into numerical features suitable for ML

Training an SVM model on the processed data

This pipeline can later be extended to classify new resumes once deployed.

🛠️ Tech Stack

Python

NLTK – tokenization, stopwords removal, stemming/lemmatization

scikit-learn – TF–IDF vectorization, SVM model training

pandas, numpy – data manipulation

🧹 Preprocessing Steps

Lowercasing and removing punctuation

Tokenization using NLTK

Stopword removal

Stemming or lemmatization

Conversion into TF–IDF vectors for model training
