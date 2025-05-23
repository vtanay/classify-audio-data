# 🎵 Music Genre Classification – Rock vs. Hip-Hop

This project applies machine learning to classify music tracks into two genres: **Hip-Hop** or **Rock**. Using raw audio analysis data provided by [The Echo Nest](https://the.echonest.com/), this notebook walks through a full pipeline—from data preparation to model training—to demonstrate how streaming platforms can personalize music recommendations based on underlying track features.

## 🧠 Project Overview

In the age of music streaming, platforms strive to understand listener preferences through advanced audio analytics. This project demonstrates how machine learning models can help classify genres based solely on **audio-derived features**, without needing to "listen" to the music.

Key steps include:
- Data loading and merging (from CSV and JSON sources)
- Exploratory data analysis and visualization
- Feature correlation and reduction
- Model training using Logistic Regression and Decision Trees

## 📂 Dataset Details

Two datasets were used:
- **Track Metadata**: Contains song IDs and labeled genres (`rock`, `hip-hop`)
- **Echo Nest Metrics**: Contains audio features like `danceability`, `energy`, `acousticness`, etc.

## 🛠️ Tools & Technologies

- **Languages/Libraries**: `Python`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
- **Models Used**:
  - Logistic Regression
  - Decision Tree Classifier
- **Techniques**:
  - Correlation analysis to reduce feature redundancy
  - Train/test data splitting
  - Model evaluation and comparison

## 🔍 Key Learnings

- Audio features can be powerful predictors of musical genre.
- Proper data preprocessing (merging, cleaning, reducing) is crucial for optimal model performance.
- Simpler models like logistic regression can be highly effective for binary classification tasks when data is well-prepared.

## 📁 File Structure

- `notebook.ipynb` – Main notebook with full analysis and modeling steps
- `datasets/` – Contains:
  - `fma-rock-vs-hiphop.csv`: Track metadata with genre labels
  - `echonest-metrics.json`: Audio features extracted from tracks

---

*This notebook is inspired by real-world music recommendation systems and showcases how ML can enhance user experiences by making intelligent content suggestions.*
