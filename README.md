# 🧠 Depression Detection on Social Media using Text Mining

This project analyzes user-generated content from Twitter and Facebook to detect potential signs of depression using text mining and machine learning. It features end-to-end capabilities including data collection (via Twitter), preprocessing, classification, and a simple GUI for live sentiment checks.

The goal is to explore how Natural Language Processing (NLP) and machine learning can be applied to mental health awareness by identifying depressive tendencies based on emotional, temporal, and linguistic patterns in social media posts.

---

## 🎯 Objectives

- Detect early signs of depression using social media posts
- Leverage emotional, temporal, and linguistic features for classification
- Evaluate multiple ML algorithms and feature combinations
- Build a minimal GUI for real-time sentiment prediction

---

## 🧠 Project Workflow

1. **Tweet Collection**
   - Tweets collected using the Twitter API (via `Depression_Twitter.ipynb`)
   - Stored in `dep_tweet.txt` for further processing

2. **Text Preprocessing**
   - Conducted in `Depression_PreProcessing.ipynb`
   - Steps include: cleaning, tokenization, stop-word removal, normalization

3. **Feature Engineering**
   - Features extracted across three domains:
     - Emotional (sentiment, mood polarity)
     - Temporal (time-context cues)
     - Linguistic (style, grammar patterns)

4. **Classification**
   - Models: Decision Tree, k-Nearest Neighbor, SVM, Ensemble methods
   - Implemented in `Depression_SentimentAnalysis.ipynb`
   - Output labels: `Positive`, `Neutral`, `Negative` (depressive)

5. **Evaluation**
   - Model performance checked in `Depression_AccuracyCheck.ipynb`
   - Final outputs saved in `dep_output.xlsx`

6. **Interactive Interface**
   - Simple web GUI built with HTML + jQuery (`home.html`)
   - Backend connected via `mains.py`

---

## 📊 Sample Output

Each social media post is classified into:
- **Positive** – No depressive indication
- **Neutral**
- **Negative** – Potential signs of depression

Outputs are shown live on the GUI or stored in `.xlsx` format for analysis.

---

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: scikit-learn, NLTK, Word2Vec, pandas, numpy
- **Web Interface**: HTML, jQuery, Python backend
- **Data**: Tweets and Facebook posts
- **ML Models**: Decision Tree, KNN, SVM, Ensemble

---

## 🚀 Future Enhancements

- Integrate contextual models like BERT or RoBERTa
- Incorporate image/video metadata for richer sentiment context
- Expand GUI with backend API support (e.g., Flask or FastAPI)
- Add POS tagging and n-gram features for improved accuracy

---

## 📄 Reports

- [📊 Project Presentation](Min_Project3.pptx)

---

## 📃 License

This project is for academic purposes only and is not a diagnostic tool.
