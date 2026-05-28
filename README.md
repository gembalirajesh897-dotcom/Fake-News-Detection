# Fake-News-Detection

A Machine Learning-based web application that detects whether a news article is Real or Fake using Natural Language Processing (NLP) techniques.

## 📌 Project Overview
Misinformation and fake news spread rapidly in today's digital era, making it crucial to verify the authenticity of online content. This project focuses on detecting whether a news article is fake or real using Natural Language Processing (NLP) techniques and Machine Learning. The system analyzes textual patterns and word importance to make highly accurate predictions, showcasing how AI can solve real-world problems.

## 🚀 Features
* **Fake News Classification:** Accurately predicts if an article is real or fake.
* **NLP-based Text Processing:** Advanced text cleaning and preparation.
* **TF-IDF Vectorization:** Transforms text into meaningful numerical features.
* **Multi-Model Support:** Implements multiple machine learning models for comparison.

## 🛠 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, NLTK
* **Concepts:** Machine Learning, Natural Language Processing (NLP), Evaluation Matrix

## 📂 Project Structure
```text
Fake-News-Detection/
│
├── dataset/
├── model/
├── fake_news_detection.py
├── train_model.py
├── requirements.txt
└── README.md
```

## 📊 Machine Learning Workflow
1. **Data Collection:** Gathering the real and fake news dataset.
2. **Data Cleaning:** Removing noise, URLs, and special characters.
3. **Text Preprocessing:** Cleaning the text for feature extraction.
4. **TF-IDF Vectorization:** Transforming text into numerical features based on word importance.
5. **Model Training:** Training classification models on the processed data.
6. **Prediction & Evaluation:** Testing the model accuracy on unseen data.

## 📈 Algorithms Used
* **Logistic Regression:** Used as the baseline model for binary classification.
* **Passive Aggressive Classifier:** Efficient for large text streams and online learning.
* **Naive Bayes:** A probabilistic classifier ideal for text classification and NLP tasks.

## 🧠 NLP Techniques Used
* **Tokenization:** Splitting sentences into individual words or tokens.
* **Stopword Removal:** Filtering out common words (like 'is', 'the', 'and') that do not add meaning.
* **Stemming:** Reducing words to their root or base form (e.g., "running" to "run").

## 📊 Evaluation Metrics
To measure the performance of our models, we use:
* **Accuracy Score:** Percentage of correct predictions.
* **Confusion Matrix:** To visualize true positives vs. false positives.
* **Classification Report:** Detailed analysis using Precision, Recall, and F1-Score.

## 📌 Future Improvements
* **Deep Learning Integration:** Implementing LSTM or BERT models for better context understanding.
* **Real-time News Verification:** Creating a web app extension to check news live.
* **Large Dataset Training:** Scaling the model with bigger, multi-domain datasets.

## 👨‍💻 Author
Rajesh
