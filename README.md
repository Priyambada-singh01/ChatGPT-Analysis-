# 📊 ChatGPT Reviews Sentiment Analysis

## 🧾 Project Overview

This project focuses on analyzing customer reviews of **ChatGPT** to uncover insights into user **sentiment** and **satisfaction trends**.

---

## 🎯 Objectives

* ✅ **Perform Sentiment Analysis** (Positive, Negative, Neutral classification)
* ✅ **Measure Subjectivity** to assess opinion-based vs. fact-based feedback
* ✅ **Extract Key Features** and frequently mentioned terms from the reviews
* ✅ **Visualize Insights** using plots and word clouds

---

## 🛠️ Project Workflow

1. **Problem Framing** – Understand the goal and scope of review analysis
2. **Data Preparation** – Load, clean, and preprocess the review data
3. **Exploratory Data Analysis (EDA)** – Discover patterns, ratings distribution, and word frequencies
4. **Sentiment & Text Analysis** – Use NLP techniques to classify sentiments and measure subjectivity
5. **Insights & Recommendations** – Summarize findings and suggest improvements based on user feedback

---

## 🧰 Tech Stack

* **Python**
* **Pandas** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **TextBlob** – Sentiment and subjectivity scoring
* **Scikit-learn** – Text feature extraction
* **WordCloud** – Keyword visualization

---

## 📁 Project Structure

```
├── data/                   # Raw and cleaned CSV data
├── notebooks/              # Jupyter Notebooks for EDA and modeling
├── outputs/                # Visualizations and final charts
├── README.md               # Project documentation (this file)
└── main.py / analysis.py   # Core analysis scripts
```

---

## 📌 Notes

* Sentiment scores range from **-1 to +1**
* Subjectivity scores range from **0 (objective)** to **1 (subjective)**
* Frequently used words are visualized via **WordClouds**
* Text features like TF-IDF or CountVectorizer can be used for further modeling


