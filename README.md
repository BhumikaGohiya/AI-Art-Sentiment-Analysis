# 🎨 AI-Art Sentiment Analysis  
> Analyzing public perception of AI-generated art using NLP & Machine Learning  

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![NLP](https://img.shields.io/badge/NLP-Text_Analysis-orange?logo=googlecolab)
![AI Art](https://img.shields.io/badge/AI_Art-Ethics_&_Creativity-purple)
![Logistic Regression](https://img.shields.io/badge/Model-Logistic_Regression-success)

---

## 🧭 Overview
This project investigates how audiences react to **AI-generated art** by analyzing YouTube comments through Natural Language Processing (NLP) and Machine Learning.  
It applies **text cleaning, TF-IDF vectorization**, and a **Logistic Regression classifier** to predict whether a comment expresses **positive, negative, or neutral sentiment**.  

💡 The project highlights not just technical modeling, but also **ethical and emotional perspectives** in how people perceive AI-generated creativity.

---

## 🧰 Tools & Technologies
| Category | Libraries |
|-----------|------------|
| Data Processing | `pandas`, `numpy` |
| NLP | `nltk`, `textblob`, `scikit-learn` |
| Visualization | `matplotlib`, `seaborn`, `wordcloud` |
| Model | TF-IDF + Logistic Regression |
| IDE / Environment | Google Colab, Jupyter Notebook |

---

## 📂 Project Structure
```bash
AI-Art-Sentiment-Analysis/
│
├── data/
│   └── AI_Art_Comments_Clean.xlsx          # Clean YouTube comment data
│
├── scripts/
│   └── ai_art_sentiment.py                 # Script for text cleaning and feature extraction
│
├── visuals/                                # Folder for generated plots and wordclouds
│
├── AI_Art_Sentiment_Analysis.ipynb         # Main analysis notebook
├── requirements.txt                        # Dependencies
└── README.md                               # Documentation

🧠 Methodology
1️⃣ Data Cleaning

Removed URLs, symbols, and punctuation

Lowercased and tokenized text

Removed English stopwords using NLTK

2️⃣ Sentiment Labeling

Initial tagging via TextBlob polarity

Supervised model trained using Logistic Regression

3️⃣ Feature Engineering

Converted text to numerical vectors using TF-IDF

Trained on small labeled samples, later scalable to full datasets

4️⃣ Evaluation

Used metrics: Accuracy, F1 Score, and Classification Report

Visualized results with bar plots and word clouds
