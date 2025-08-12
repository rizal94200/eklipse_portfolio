# 🎯 Eklipse Portfolio – Game Clip Engagement Prediction

This project aims to analyze game clip data and build a model to predict **user engagement** with uploaded clips on the *Eklipse* platform.  
The analysis covers **Exploratory Data Analysis (EDA)**, feature engineering, and machine learning modeling.

---

## 📂 Project Structure
eklipse_portfolio/
│
├── data/ # Raw data (not uploaded to GitHub, ignored via .gitignore)
│ ├── raw/ # Original CSV files
│ └── processed/ # Cleaned & transformed data
│
├── notebooks/ # Jupyter Notebooks for EDA & modeling
│ └── Eklipse_EDA_ML.ipynb
│
├── reports/ # Analysis reports
│ ├── figures/ # Visualizations
│ └── insights_and_recommendations.md
│
└── models/ # Saved machine learning models (joblib/pkl)

---

## 🛠 Tech Stack
- **Python 3.11**
- **Pandas, NumPy** – Data wrangling
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Preprocessing & modeling
- **FeatureHasher** – Categorical encoding
- **Joblib** – Model persistence
- **Jupyter Notebook** – Experimentation & analysis

---

## 📊 Analysis Workflow
1. **Data Loading** – Read raw datasets from `data/raw`.
2. **EDA (Exploratory Data Analysis)** – Analyze trends, distributions, and feature relationships.
3. **Feature Engineering** – Transform numerical & categorical features.
4. **Modeling** – Build Logistic Regression to predict engagement probability.
5. **Model Saving** – Save the trained model as `.joblib` for deployment.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/eklipse_portfolio.git
   cd eklipse_portfolio
---
   pip install -r requirements.txt

---
jupyter notebook notebooks/Eklipse_EDA_ML.ipynb

---
📌 Key Insights
The most influential factors affecting engagement:

Clip duration

Upload time

Game title

Event type

Logistic Regression produces probabilities for engagement per clip.

📄 Notes
Raw datasets are not included in this public repository due to size limitations & privacy reasons.
A .gitignore file is used to prevent large or sensitive files from being pushed.

---
✨ Author
Syamsul Rizal – Data Analyst & Machine Learning Enthusiast
📧 Email: rizal.bhp8902@gmail.com

   
