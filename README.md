# 🧠 Depression Detection on Social Media using Text Mining

This project explores how social media content, particularly user-generated text on platforms like Twitter and Facebook, can be analyzed to detect signs of depression. Using natural language processing and supervised machine learning techniques, the system classifies text as **positive**, **neutral**, or **indicative of depressive symptoms**. The goal is to offer an early-warning tool by extracting emotional, temporal, and linguistic cues from social media posts.

---

## 🎯 Objectives

- Identify early signs of depression from social media posts using NLP
- Evaluate multiple classification models and feature sets
- Explore emotional, temporal, and linguistic factors in text
- Build a lightweight, ML-based system for mental health analysis

---

## 📊 Methodology

1. **Data Collection**  
   - Sample comments and posts from Twitter and Facebook  
   - Preprocessed using tokenization, normalization, and stop word removal

2. **Feature Engineering**  
   - Emotional processes (e.g., sentiment polarity)
   - Temporal cues (e.g., posting time references)
   - Linguistic style (e.g., personal pronouns, negations)

3. **Machine Learning Models**  
   - Decision Tree  
   - k-Nearest Neighbor  
   - Support Vector Machine  
   - Ensemble techniques

4. **Classification Output**  
   - Each input post is classified into:  
     - **Positive** (no depressive indication)  
     - **Neutral**  
     - **Negative** (potential depressive symptoms)

---

## 🧠 Tools & Technologies

- **Language**: Python  
- **Libraries**: scikit-learn, NLTK, Word2Vec  
- **Techniques**: Text mining, Sentiment analysis, Supervised ML  

---

## 📈 Results

- The system successfully classifies random test comments with reasonably accurate labels.
- Screenshots in the presentation show sample inputs and predicted sentiment output.
- Results indicate that combining emotional, temporal, and linguistic features improves model performance over single-feature models.

---

## 🚀 Future Scope

- Integrate advanced NLP techniques such as contextual embeddings (e.g., BERT)
- Use stop-word optimization and POS tagging for more nuanced feature extraction
- Expand data to include multimedia (images, video captions)
- Apply the system across multiple languages and platforms

---

## 📄 Reports

- [📊 Project Presentation](Min_Project3.pptx)

---

## 📃 License

This project is for academic purposes only and is not a diagnostic tool.
