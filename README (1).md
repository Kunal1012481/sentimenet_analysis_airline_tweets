# ✈️ Twitter Sentiment Analysis - Airline Tweets

## 📌 Overview
This project uses Natural Language Processing (NLP) techniques to analyze sentiment in tweets related to airlines. The tweets are classified into three categories: Positive, Neutral, and Negative. It includes text preprocessing, feature extraction using TF-IDF, model training (Logistic Regression), evaluation, and insights.

---

## 📂 Dataset
- **Source**: [Kaggle - Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- **Columns Used**: `text` (tweet content), `airline_sentiment` (label)

---

## 🧠 Key Steps
1. **Data Cleaning**: Remove URLs, mentions, punctuation, emojis, stopwords, etc.
2. **Feature Extraction**: TF-IDF Vectorization
3. **Modeling**: Logistic Regression for classification
4. **Evaluation**: Accuracy, Confusion Matrix, Word Importance
5. **Visualization**: Sentiment distribution, top predictive words per class

---

## 🔍 Insights
- Most tweets are Negative in sentiment.
- The model performs well with ~80% accuracy.
- Top keywords influencing each sentiment are printed and visualized.

---

## 💡 Dependencies
Install required libraries using:

```bash
pip install -r requirements.txt
```

---

## 📄 Credits
- Dataset by Crowdflower (via Kaggle)
- NLP methods and modeling using Scikit-learn, NLTK, and CleanText
- Guided learning adapted from online tutorials

---

## ⚠️ Disclaimer
This project is for academic and learning purposes only. The dataset contains real tweets and should be used responsibly.