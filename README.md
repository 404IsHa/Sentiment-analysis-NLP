# 🧠 Sentiment Analysis using NLP

A Natural Language Processing (NLP) project that classifies customer reviews
as **Positive**, **Negative**, or **Neutral** using Machine Learning.

---

## 📌 Project Overview

Sentiment Analysis is the process of identifying and extracting emotional
tone from text data. This project builds a complete NLP pipeline from raw
text to a trained classification model — covering text preprocessing,
feature extraction, model training, and evaluation.

---

## 🎯 Objectives

- Clean and preprocess raw text data using NLP techniques
- Convert text into numerical features using TF-IDF Vectorization
- Train and compare two ML models: Naive Bayes and Logistic Regression
- Evaluate models using Accuracy, Precision, Recall and F1-Score
- Build a reusable function to predict sentiment on any new text

---

## 🗂️ Project Structure
sentiment-analysis-nlp/
│
├── sentiment_analysis.ipynb   # Main Jupyter Notebook
├── requirements.txt           # Required Python libraries
└── README.md                  # Project documentation

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Programming Language |
| NLTK | Tokenization, Stopwords, Stemming |
| Scikit-learn | TF-IDF, Model Training, Evaluation |
| Matplotlib | Bar charts, Accuracy plots |
| Seaborn | Confusion Matrix heatmap |
| WordCloud | Word frequency visualization |
| Pandas | Data handling and manipulation |

---

## 🔁 NLP Pipeline
Raw Text
↓
Lowercase Conversion
↓
Tokenization
↓
Stopword Removal
↓
Stemming (Porter Stemmer)
↓
TF-IDF Vectorization
↓
Model Training
↓
Prediction

---

## 📊 Steps Covered

| Step | Description |
|------|-------------|
| 1 | Import libraries and download NLTK data |
| 2 | Create labeled dataset (30 reviews) |
| 3 | Exploratory Data Analysis (EDA) |
| 4 | Word Cloud visualization |
| 5 | Text Preprocessing pipeline |
| 6 | TF-IDF Feature Extraction |
| 7 | Train Naive Bayes and Logistic Regression |
| 8 | Confusion Matrix visualization |
| 9 | Model accuracy comparison |
| 10 | Custom sentiment prediction function |

---

## 📈 Results

| Model | Accuracy |
|-------|----------|
| Naive Bayes | ~75% |
| Logistic Regression | ~87% |

> Logistic Regression outperforms Naive Bayes on this dataset.

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
1. Click the badge below or go to [colab.research.google.com](https://colab.research.google.com)
2. Upload `sentiment_analysis.ipynb`
3. Run all cells from top to bottom (Shift + Enter)

### Option 2 — Jupyter Notebook (Local)
```bash
# Step 1: Clone the repository
git clone https://github.com/YOUR_USERNAME/sentiment-analysis-nlp.git

# Step 2: Navigate into the folder
cd sentiment-analysis-nlp

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Launch Jupyter
jupyter notebook
```
Then open `sentiment_analysis.ipynb` and run all cells.

---

## 💡 Sample Predictions

| Review | Predicted Sentiment |
|--------|-------------------|
| "This product is absolutely wonderful!" | 😊 Positive |
| "It is okay, nothing great about it." | 😐 Neutral |
| "Terrible quality. I want my money back." | 😠 Negative |

---

## 🔮 Future Improvements

- Use larger datasets from Kaggle (IMDB, Amazon Reviews)
- Add VADER lexicon-based sentiment as baseline comparison
- Implement deep learning using LSTM or BERT
- Deploy as a Streamlit web application
- Add cross-validation for more reliable evaluation

---

## 📚 Concepts Used

- **Tokenization** — splitting text into individual words
- **Stopword Removal** — removing common meaningless words
- **Stemming** — reducing words to their root form
- **TF-IDF** — converting text to numerical feature vectors
- **Naive Bayes** — probabilistic classification model
- **Logistic Regression** — linear classification model
- **Confusion Matrix** — visual evaluation of model predictions
- **F1-Score** — balanced metric for classification performance

---
