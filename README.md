# 📊 Facebook Marketplace Analysis

## 📌 Overview
This project analyzes the Facebook Live Sellers dataset to understand user engagement patterns and optimize content strategy.

## 🎯 Objectives
- Analyze impact of posting time on reactions
- Study correlation between reactions, comments, and shares
- Compare engagement across post types
- Apply K-Means clustering to group posts

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Records: 7050 posts
- Features: reactions, comments, shares, post type, time

## 🔍 Key Insights
- Peak engagement: 5 PM – 9 PM (highest around 7 PM)
- Weak correlation:
  - Reactions vs Comments (~0.15)
  - Reactions vs Shares (~0.25)
- Strong correlation:
  - Comments vs Shares (~0.64)
- Most common post type: Photo

## 🤖 ML Model
- K-Means Clustering (K=3)
- PCA used for visualization

## 📈 Results
- 3 clusters identified:
  - Low engagement
  - Medium engagement
  - High engagement

## 🚀 How to Run
```bash
git clone <repo-link>
cd facebook-marketplace-analysis
pip install -r requirements.txt
jupyter notebook
