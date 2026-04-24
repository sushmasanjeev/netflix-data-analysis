# 📺 Netflix Data Analysis & Clustering

## 📌 Project Overview
This project analyzes Netflix content data to uncover trends in movies and TV shows, identify content patterns, and apply clustering techniques for better understanding of content segmentation.

---

## 🎯 Objectives
- Analyze viewing trends and content distribution
- Identify top producing countries and genres
- Perform feature engineering
- Apply clustering (KMeans) to group content

---

## 📂 Dataset
- Source: Kaggle (Netflix Shows Dataset)
- Features:
  - Type (Movie/TV Show)
  - Country
  - Release Year
  - Duration
  - Genre

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn

---

## 📊 Key Analysis Performed
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Clustering using KMeans

---

## 📈 Visual Insights

### 1. Movies vs TV Shows
![Movies vs TV Shows](outputs/movies_vs_tvshows.png)

### 2. Top Countries
![Top Countries](outputs/top_countries.png)

### 3. Content Growth Over Time
![Growth](outputs/growth_trend.png)

---

## 🔍 Key Insights
- Netflix has more Movies than TV Shows
- USA is the leading content producer
- Content growth increased significantly after 2015
- TV-MA is the most common rating
- Clustering reveals distinct content groups

---

## 🤖 Machine Learning
- Algorithm: KMeans Clustering
- Features used:
  - Release Year
  - Duration
  - Genre Count

---

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Upload dataset
3. Run all cells

---

## 📌 Future Improvements
- Build recommendation system
- Add user viewing data
- Deploy dashboard using Streamlit
