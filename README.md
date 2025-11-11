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
## 📁 Project Structure


```text
AI-Art-Sentiment-Analysis/
├── data/
│   └── AI_Art_Comments_Clean.xlsx     # Clean YouTube comment data
├── scripts/
│   └── ai_art_sentiment.py            # Helper script for text cleaning & feature extraction
├── AI_Art_Sentiment_Analysis.ipynb    # Main analysis notebook
├── requirements.txt                   # Dependencies
└── README.md                          # Project documentation
```



---

## 🧠 Methodology

| Step | Description |
|------|--------------|
| **1️⃣ Data Cleaning** | Removed URLs, symbols, and punctuation. Converted text to lowercase, tokenized comments, and removed English stopwords using **NLTK**. |
| **2️⃣ Sentiment Labeling** | Used **TextBlob** for polarity tagging and trained a **Logistic Regression** model for refined classification. |
| **3️⃣ Feature Engineering** | Converted text into **TF-IDF vectors** to capture important sentiment-related words and patterns. |
| **4️⃣ Evaluation** | Measured model performance with **Accuracy** and **F1-Score**, reviewed the **Classification Report**, and visualized key trends using **matplotlib** and **seaborn**. |


---

## 📊 Model Performance

| Metric | Score |
|--------|--------|
| **Accuracy** | 0.87 |
| **F1 Score** | 0.85 |
| **Model** | Logistic Regression |
| **Vectorization** | TF-IDF |

> ⚙️ The model shows strong baseline accuracy.  
> Future improvements may include **BERT**, **RoBERTa**, or transformer-based embeddings for deeper sentiment understanding.

------

## 💬 Insights

### 🟢 Positive Comments
- Emphasize **creativity**, **beauty**, and **innovation** in AI-generated art.  
- Viewers often admire the blend of technology and imagination.

### 🔴 Negative Comments
- Reflect **concerns about ethics**, **plagiarism**, and **AI replacing human artists**.  
- Some users question the authenticity and originality of AI creations.

### ⚪ Neutral Comments
- Express **curiosity and balanced views**.  
- Many are exploring how AI tools can coexist with human creativity and traditional art forms.

> 🧠 These insights highlight the cultural and emotional tension between **innovation** and **authenticity** — a key theme in the evolving perception of AI-driven creativity.

-----

## 🧩 Future Enhancements

### 🚀 Planned Improvements
- **Expand Dataset** — include multiple platforms (Reddit, Instagram, DeviantArt) for richer sentiment diversity.  
- **Deep Learning Integration** — experiment with **BERT**, **RoBERTa**, or **DistilBERT** to capture nuanced emotional tones.  
- **Dashboard Visualization** — build an interactive **Power BI** or **Streamlit** dashboard for visual insights.  
- **Web App Deployment** — host a demo app using **Streamlit + Hugging Face Spaces** for real-time comment analysis.  
- **Multilingual Support** — incorporate sentiment detection for non-English comments using **Google Translate API** or **Polyglot**.

> 💡 These enhancements will transform the project from a notebook-based analysis into an **AI-driven research and analytics tool** ready for production.

------
## 🚀 How to Run the Project

You can run this notebook in **two simple ways** — either via Google Colab (no setup needed) or on your local machine.

---

### 🟢 Option 1: Run on Google Colab
1. Open the notebook directly in [Google Colab](https://colab.research.google.com/).  
2. Upload the dataset (`comment_tracker.xlsx`).  
3. Click **Runtime → Run all**.  
4. All cells will execute sequentially and generate visual outputs (bar plots, word clouds, sentiment charts).

---

### 💻 Option 2: Run Locally (Manual Setup)
```bash
# 1️⃣ Clone this repository
git clone git@github.com:BhumikaGohiya/AI-Art-Sentiment-Analysis.git

# 2️⃣ Navigate to the project directory
cd AI-Art-Sentiment-Analysis

# 3️⃣ Create a virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate  # for Mac/Linux
venv\Scripts\activate     # for Windows

# 4️⃣ Install all dependencies
pip install -r requirements.txt

# 5️⃣ Launch Jupyter Notebook
jupyter notebook AI_Art_Sentiment_Analysis.ipynb
```

---

### ✅ Output Examples
After running the notebook, you’ll see:
- **Sentiment distribution plots** (positive/negative/neutral)
- **Wordclouds** showing most frequent terms
- **Bar charts** ranking AI art videos by engagement
- **Model performance metrics** with accuracy and F1-score

> 💬 Tip: You can adapt the same code for any YouTube or Reddit dataset — just replace the CSV file.

-------

---

## 👩‍💻 Author

**Bhumika Gohiya**  
🎓 M. Eng. Technology Innovation Management, Carleton University  
💼 QA Automation Engineer | Data & AI Analytics Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/bhumikagohiya) | 🌐 [GitHub](https://github.com/BhumikaGohiya)

---

## 📜 License
This project is open-source under the **MIT License**.  
You’re free to reuse the code with proper attribution.

---

⭐ **If you found this project inspiring, please give it a star!** 🌟

-----




