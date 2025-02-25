# **Twitter Sentiment Analysis using Machine Learning** 🚀  

## 📌 **Overview**  

This project analyzes tweets to classify sentiment into **Positive, Negative, Neutral, or Irrelevant** categories using **machine learning techniques**.  

### 📊 **Key Features**  
✔ **Data Cleaning & Preprocessing** – Removed **HTML tags, URLs, emojis, stopwords, abbreviations, and applied lemmatization**.  
✔ **Feature Engineering** – Used **TF-IDF Vectorization** to convert text into numerical features.  
✔ **Model Comparison** – Tested multiple ML models for best performance.  
✔ **Best Model: Random Forest** – Achieved **90% accuracy** and the highest precision, recall, and F1-score.  

---

## 📂 **Dataset Information**  
- **Source:** [Insert Kaggle Dataset Link]  
- **Columns:**  
  - `id` → Unique tweet identifier  
  - `game/company` → Associated topic or entity  
  - `label` → Sentiment category (Positive, Negative, Neutral, Irrelevant)  
  - `tweet` → The actual tweet text  

---

## 🛠 **Data Preprocessing**  
- **Lowercased text** for uniformity.  
- **Removed HTML tags, URLs, emojis, and stopwords** for cleaner data.  
- **Expanded chat abbreviations** (e.g., "LOL" → "Laughing Out Loud").  
- **Applied lemmatization** to standardize word forms (e.g., "running" → "run").  
- **Applied TF-IDF vectorization** to transform text into numeric data.  

---

## 🤖 **Machine Learning Models Compared**  
| Model                  | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|------------------------|----------|----------|--------|----------|---------|
| Logistic Regression    | 84%      | 86%      | 85%    | 86%      | 96%     |
| SGD Classifier        | 76%      | 66%      | 96%    | 79%      | 93%     |
| Multinomial Naïve Bayes | 82%      | 82%      | 83%    | 82%      | 95%     |
| **Random Forest (Final Model)** | **90%** | **91%** | **90%** | **90%** | **98%** |

---

## 🏆 **Final Model Selection**  
After testing multiple models, **Random Forest** emerged as the best performer due to its **high accuracy, strong recall, and excellent precision**.  

**Why Random Forest?**  
✔ **Handles complex relationships well**  
✔ **Less prone to overfitting compared to Decision Trees**  
✔ **Excels in multi-class classification**  

---

## 📌 **Project Structure**  
📂 `data/` → Contains the dataset files  
📜 `twitter_sentiment_analysis.ipynb` → Jupyter notebooks for analysis  
📜 `README.md` → Project details  
