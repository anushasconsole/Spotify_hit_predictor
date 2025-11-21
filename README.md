Got you, Anusha! ⭐
Here is a **complete, polished, professional FULL README.md** for your GitHub repository — including **project intro, dataset details, novelties, methodology, results, visualizations, installation instructions, and usage**.

You can **copy–paste directly into README.md**.

---

# 🎵 **Song Popularity Prediction using Spotify Audio Analytics + Lyric NLP**

### 🚀 Predicting Song Success Before Release (Audio + Lyrics Hybrid ML Model)

---

## 📌 **Overview**

The music industry releases **100,000+ songs per day**, but artists and labels still lack a reliable method for predicting whether a **newly released song** will be successful.

This project develops a **hybrid machine learning framework** that predicts song popularity **using only pre-release features** — including **Spotify audio analytics** and **lyric-based NLP features**.

We built a **custom dataset**, extracted **advanced NLP features**, prevented **data leakage**, and trained multiple classification and regression models to predict song popularity.

---

## 📌 **Key Features**

✔️ Built custom dataset of **25,000 songs (2020–2024)**
✔️ Extracted **147 raw features** (audio + metadata + lyrics)
✔️ Created **16 lyric-based NLP features**
✔️ Strict **data leakage prevention**
✔️ Hybrid modeling (Audio + Lyrics)
✔️ Gradient Boosting achieved **88.96% accuracy**
✔️ Outperforms recent models like **SpotHippy (2023, 86% accuracy)**
✔️ Full visual analysis & model comparison

---

# 📁 **Dataset**

Unlike many studies relying on old Kaggle datasets, we built a **fresh, large-scale dataset from scratch**, consisting of:

### 🎧 **Spotify Audio Features**

* Danceability
* Energy
* Valence
* Acousticness
* Loudness
* Tempo
* Instrumentalness
* Speechiness
* Liveness
* Duration
* Mode, Key, Time Signature

### ✍️ **Lyric NLP Features (16 features)**

* Sentiment polarity
* Sentiment intensity (VADER)
* Complexity score
* Unique word ratio
* Word count & normalized word count
* Avg sentence length
* Rhyme density
* Emotional tone
* Repetition score
* Uniqueness score

### 🗂️ Metadata

* Release year/month
* Artist count
* Explicit flag
* Genre (processed)

After cleaning and leakage removal, final modeling used **pre-release-only features**.

---

# 🔥 **Novelty & Research Contributions**

### 🆕 **1. Large, Recent Dataset (2020–2024)**

We scraped **25k modern songs** and 147 features — significantly larger and newer than datasets used in previous studies.

### 🎤 **2. Added Lyric-Based NLP Features (Underexplored Area)**

Most earlier research focused on **audio features only**.
We added **16 lyric NLP features**, showing strong predictive improvements.

### 🛡️ **3. Strict Data Leakage Prevention**

Removed all post-release success indicators:

* Streams
* Playlist placements
* YouTube views
* TikTok engagement
* Chart ranks

Also removed any feature with **correlation > 0.85**, ensuring deployable performance.

### 🏆 **4. Outperforms Recent Research**

Recent 2023 work **SpotHippy** reported **86% accuracy**.
Our approach achieved:

| Model                 | Accuracy   |
| --------------------- | ---------- |
| **Gradient Boosting** | **88.96%** |
| **Random Forest**     | **88.17%** |
| SVM                   | ~82%       |
| Logistic Regression   | ~77%       |

A **clear improvement** driven by:

* Hybrid modeling
* Leakage-free training
* Richer dataset

---

# 🧠 **Methodology**

## ✔️ 1. Data Collection

* Scraped 25,000 Spotify tracks (2020–2024)
* Fetched 147 audio + metadata features
* Scraped lyrics and preprocessed text

## ✔️ 2. Feature Engineering

* 16 NLP features
* Interaction features (e.g., danceability × energy)
* Engagement metrics (normalized)
* Virality signals (log transforms)

## ✔️ 3. Data Leakage Removal

* Removed ALL post-release features
* Removed correlated variables (>0.85)
* Ensured only pre-release info used

## ✔️ 4. Model Training

Models used:

* Random Forest
* Gradient Boosting
* SVM (RBF)
* Logistic Regression

Techniques:

* StandardScaler
* 80/20 stratified split
* 5-fold Cross Validation

## ✔️ 5. Model Evaluation

* Accuracy
* Precision, Recall, F1
* ROC-AUC
* Confusion Matrix
* Feature Importance
* Regression R² & residuals

---

# 📊 **Results & Visualizations**

### 📌 Confusion Matrix — Gradient Boosting

![Confusion Matrix](sandbox:/mnt/data/Screenshot%202025-11-17%20162139.png)

---

### 🔥 ROC Curve Comparison

![ROC](sandbox:/mnt/data/Screenshot%202025-11-17%20163137.png)

---

### 🎵 Actual vs Predicted Popularity (Regression)

![Actual-Predicted](sandbox:/mnt/data/Screenshot%202025-11-17%20163147.png)

---

### 🔍 Residual Plot

![Residual](sandbox:/mnt/data/Screenshot%202025-11-17%20163157.png)

---

### 🧩 Top 20 Feature Importances

![Feature Importance](sandbox:/mnt/data/Screenshot%202025-11-17%20163707.png)

---

### 🔥 Correlation Heatmap (Top 10 Features)

![Heatmap](sandbox:/mnt/data/Screenshot%202025-11-17%20161511.png)

---

# ⚙️ **How to Run This Project**

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/your-username/song-popularity-prediction.git
cd song-popularity-prediction
```

### **2️⃣ Create environment**

```bash
pip install -r requirements.txt
```

### **3️⃣ Run the notebook or script**

```bash
python song_popularity_model.py
```

or open the Jupyter notebook.

---

# 🧪 **Tech Stack**

* **Python 3.9+**
* Pandas, NumPy
* Scikit-learn
* NLTK
* TextBlob
* VADER Sentiment
* Matplotlib & Seaborn
* Spotify API
* BeautifulSoup (lyric scraping)

---

# 📝 **Conclusion**

This project presents a deployable, reliable, and high-performing hybrid machine learning model that predicts song popularity **before release**, using audio features and lyric-based NLP.

We show that:

* **Lyrics matter**
* **Hybrid models outperform audio-only models**
* **Leakage-free design leads to trustworthy results**
* **Our model outperforms recent state-of-the-art research (SpotHippy 2023 — 86%)**

---

# 🚀 **Future Enhancements**

* BERT/GPT embeddings for deep lyric understanding
* Predict 5 popularity categories (Hit, Viral, Popular, Moderate, Underground)
* Genre-specific modeling
* Add artist network features
* Deploy as API + web dashboard
* Combine Spotify + TikTok + YouTube + Instagram trends

---

# 🤝 **Contributions**

Pull requests are welcome!
Feel free to suggest improvements.

---

# 📧 **Contact**

**Anusha Shetty**
PRE-FINAL YEAR , STUDENT , @PES UNIVERSITY , BANGALORE 
Email: ianushashetty04@gmail.com

---


