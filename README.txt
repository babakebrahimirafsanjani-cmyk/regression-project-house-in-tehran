# 🏠 Tehran Housing Price Prediction

A compact Machine Learning project focused on predicting residential apartment prices using **Linear Regression (with Polynomial Features)** and **Ridge Regularization**.

---

## 📌 Project Overview
This project demonstrates an introductory regression workflow on a **small-scale dataset** of Tehran housing prices:
- **Data Preprocessing & Feature Engineering:** Handling data points, cleaning, and generating polynomial features to capture non-linear patterns.
- **Model Training:** Training an Ordinary Least Squares (OLS) Linear Regression model alongside a Ridge Regression model ($\alpha=1.0$).
- **Model Evaluation:** Benchmarking performance using **MAE**, **MSE**, and **$R^2$ Score**.

---

## 📊 Results & Key Findings
- **Performance Comparison:** Both Linear Regression and Ridge Regression yielded very similar results (approx. $R^2 \approx 0.864$), showing no dramatic performance gap between the standard and regularized models on this specific dataset size.
- **Dataset Limitation:** The project works with a **limited sample size**, which serves well for practicing fundamental regression pipelines, exploring feature transformations, and understanding basic evaluation metrics.

---

## 🛠️ Tech Stack & Requirements
- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

To run this project locally:
```bash
pip install -r requirements.txt
jupyter notebook
