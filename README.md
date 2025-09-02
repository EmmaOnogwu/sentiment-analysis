![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

# 📊 Instructor Engagement Dashboard (Sentiment Analysis)

## 🧩 Overview
This project analyzes student reviews using **sentiment analysis** to provide insights into instructor performance and engagement. It helps educators and administrators identify strengths, weaknesses, and areas for improvement.

---

## 🎯 Objectives
- Classify feedback into **positive, neutral, or negative** sentiments  
- Extract recurring themes with **topic modeling**  
- Visualize trends across instructors and courses  
- Support data-driven improvements in teaching  

---

## 🔧 Tools & Technologies
- **Python**: Pandas, NLTK, Scikit-learn, Gensim, TextBlob  
- **Visualization**: Power BI  
- **Deployment (Optional)**: Streamlit  
- **Version Control**: Git & GitHub  

---

## 🛠️ Workflow
1. Load student reviews dataset  
2. Preprocess text (cleaning, tokenization, lemmatization)  
3. Assign sentiment labels (Negative, Neutral, Positive)  
4. Build sentiment prediction model (TF-IDF + Naive Bayes)  
5. Apply topic modeling (LDA) to detect themes  
6. Generate outputs (CSV + Power BI dashboard)  

---

## 📈 Dashboard Features
- Instructor-level sentiment breakdown  
- Course comparisons and category insights  
- Sentiment trends over time  
- Region-wise satisfaction analysis  

---

## 📄 Key Deliverables
- **CSV**: Structured sentiment and topic results  
- **PDF Reports**: Instructor-specific summaries  
- **Power BI Dashboard**: Interactive insights  

---

## ▶️ How to Run
Install dependencies and run the analysis:
```bash
pip install pandas nltk spacy scikit-learn gensim textblob matplotlib seaborn wordcloud
```