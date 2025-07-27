# 🧠 Claim vs. Opinion Classifier
This project is a simple but effective binary classifier that distinguishes between factual claims and subjective opinions in short text passages. It’s designed as a foundational NLP task to demonstrate how text data can be cleaned, vectorized, and modeled for binary classification.

## 💡 Motivation
In today's digital world, the ability to distinguish fact from opinion is critical in areas like journalism, content moderation, and social listening. This project demonstrates a practical NLP workflow using classic machine learning methods — with 100% cross-validated accuracy, thanks to the clarity and structure of the dataset.

## 🔧 Tools and Technologies
- Python
- scikit-learn
- CountVectorizer
- Logistic Regression
- pandas, numpy
- Jupyter Notebook

## 🧪 Dataset
A small, well-structured dataset containing labeled short sentences as either:
- Claim: A verifiable statement (e.g., "The Earth revolves around the Sun.")
- Opinion: A subjective thought or feeling (e.g., "I think the sky looks beautiful today.")

## 🚀 Approach
- Text Preprocessing
- Lowercasing
- Stopword removal
- Tokenization (via CountVectorizer)
- Vectorization
- Bag-of-Words with CountVectorizer
- Model Training
- Logistic Regression
- 5-Fold Cross-Validation
- Achieved 100% accuracy

## 📈 Results
- Accuracy: 100%
- Cross-Validation: 100%
- Precision / Recall / F1: 100% (all classes)

## 🧠 What I Learned
- How to clean and vectorize textual data
- Building binary classifiers with classical ML
- Evaluating model performance using cross-validation
- How even simple models can work well on clear and well-defined datasets

## 📦 Future Improvements
- Add more nuanced, ambiguous examples
- Use a neural model like LSTM or BERT
- Build a web interface to test real-time input

## 📌 Summary
Although basic, this project reflects a strong grasp of fundamental NLP techniques and a complete ML pipeline. It's also a good foundation for more advanced NLP tasks like emotion detection, sentiment analysis, or fake news detection.

