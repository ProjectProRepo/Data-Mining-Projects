# Fake News Detection System  

This project demonstrates how to build a **Fake News Detection System** using machine learning and data mining techniques. The system applies **Natural Language Processing (NLP)** and **classification algorithms** to distinguish between real and fake news articles.  

---

## Project Objectives  
- Explore and analyze text data from news articles.  
- Perform data cleaning and preprocessing (stopword removal, lemmatization, TF-IDF).  
- Visualize trends such as word frequency, article length distribution, and subject categories.  
- Build classification models:  
  - **Logistic Regression**  
  - **Naive Bayes**  
  - **Passive Aggressive Classifier**  
  - (Optional) **Deep Learning Models** like LSTM or BERT  
- Evaluate model performance using accuracy, precision, recall, and F1-score.  

---

## Dataset  
- **Source:** [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)  
- **Files include:**  
  - `Fake.csv` → Fake news articles  
  - `True.csv` → Real news articles  
- Columns:  
  - `title` → Headline of the article  
  - `text` → Article body  
  - `subject` → Category of news (politics, world, etc.)  
  - `date` → Publication date  

---

## Tech Stack  
- **Programming Language:** Python 3.x  
- **Libraries:**  
  - `pandas`, `numpy` → Data manipulation  
  - `matplotlib`, `seaborn`, `wordcloud` → Data visualization  
  - `scikit-learn` → ML models (Logistic Regression, Naive Bayes, PassiveAggressive)  
  - `nltk` or `spaCy` → NLP preprocessing  
  - (Optional) `tensorflow` / `transformers` → Deep learning models  

---

## Data Mining  
- Distribution of fake vs real news articles  
- Word frequency and n-gram analysis for fake vs real news  
- Word clouds showing key terms in fake vs real articles  
- Article length distribution (word count)  
- Correlation of subjects with fake vs real labels  

---

## Classification Approaches  
1. **Logistic Regression & Naive Bayes**  
   - Simple yet effective for text classification with TF-IDF features.  

2. **Passive Aggressive Classifier**  
   - Works well for real-time detection of fake news.  

3. **Deep Learning Models (Optional)**  
   - **LSTMs** or **BERT** for advanced text understanding and higher accuracy.  

---

## Expected Outcomes  
- A trained classifier achieving high accuracy (>90%) in detecting fake news.  
- Visual insights into how fake and real news differ linguistically.  
- Hands-on understanding of applying NLP and data mining for misinformation detection.  
- A deployable fake news detection model (Streamlit/Flask app).  

---

## Resources  
- [Kaggle: Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)  
- [ProjectPro: Build a Fake News Detection System](https://www.projectpro.io/project-use-case/sequence-classification-with-lstm-rnn-in-python)  

---

👉 For the **full solution with code and detailed explanation**, check: **[Fake News Classifier in Python](https://www.projectpro.io/project-use-case/sequence-classification-with-lstm-rnn-in-python)**
