# Email-Detection-


📧 Email Spam Detection Using NLP
This project focuses on detecting whether an email is Spam or Not Spam (Ham) using Natural Language Processing (NLP) and Machine Learning.

🔍 Project Overview
The project implements an end-to-end spam classification pipeline. The email text is first cleaned and preprocessed using lowercasing, stopword removal, and Porter Stemming. The processed text is then converted into numerical features through text vectorization and passed to a Naive Bayes classifier for prediction.

🛠️ Workflow
- Text Preprocessing: Lowercasing, stopword removal, and Porter Stemming
- Feature Extraction: Text vectorization to convert emails into numerical features
- Model Training: Naive Bayes classification algorithm
- Prediction: Classifies emails as Spam or Not Spam
- Evaluation: Evaluates the model's classification performance using appropriate metrics

🎯 Objective
The main objective of this project is to build an NLP-based machine learning system that can automatically identify unwanted or spam emails and distinguish them from legitimate messages.
Technologies: Python, NLP, Pandas, NumPy, NLTK, Scikit-learn, Naive Bayes
