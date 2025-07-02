## POTENTIAL_CUSTOMERS

### 📌 Project Overview

This project was developed as part of the MIT/IDSS Data Science & Machine Learning certification, focusing on predicting whether individuals are likely to convert into paying customers for an online EdTech platform.

With the global e-learning industry booming — forecasted to hit $286.62 billion by 2023 — identifying and targeting high-conversion leads is crucial for growth. This project dives into that exact challenge.

---

### 🎯 Objectives

- Identify key user behaviors and traits that predict conversion
- Build a machine learning model to classify potential customers
- Provide strategic insights for business decision-making

---

### 🧠 Methodology

The analysis followed these steps:

1. **Data Preprocessing**
   - Encoding categorical features with `get_dummies`
   - Handling missing values and scaling features

2. **Exploratory Data Analysis (EDA)**
   - Heatmaps and distribution plots
   - Correlation matrix and feature importance review

3. **Model Building**
   - Logistic Regression
   - Decision Tree (pruned)
   - Random Forest (with GridSearchCV)
   - Model evaluation with F1-score, precision, recall

4. **Feature Insights**
   - Top predictors included:
     - Time spent on site
     - First interaction type
     - Profile completion level
     - Last activity type
     - Age

---

### ✅ Key Findings

- **Profile Completion** and **Phone Activity** were strong indicators of conversion likelihood.
- **Unemployed** and **Student** tags in occupation fields showed opportunities to improve conversion.
- The pruned Decision Tree outperformed the Random Forest post-tuning, offering the best trade-off between precision and recall.

---

### 🛠 Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook / Google Colab
- HTML export for presentation

---

### 📊 Recommendation Summary

To increase conversions:

- Simplify the user profile completion process
- Target users using phone activity
- Prioritize directing users to the website as much as possible
