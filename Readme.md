# 📡 SignalJudge - Confidence vs Disagreement

This project explores how multiple machine learning models can be combined to analyse pulsar signals using **confidence** and **model agreement**, instead of relying only on a single prediction or accuracy score.

The notebook builds a small experimental pipeline that compares model outputs and visualises where predictions are strong, uncertain, or conflicting.

---

## 🧠 Overview

The idea behind *SignalJudge* is simple:

- Train several models on pulsar signal data.
- Collect probability predictions from each model.
- Measure:
  - **Consensus Confidence** - average probability across models.
  - **Model Disagreement** - variation between model outputs.
- Categorise signals into:
  - Likely Pulsar
  - Noise
  - Borderline

This approach helps highlight ambiguous samples and understand model behaviour beyond traditional metrics.

---

## ⚙️ Models Used

- Logistic Regression  
- Random Forest  
- XGBoost  

Each model contributes probability estimates that are analysed together.

---

## 📊 Dataset

The notebook uses the **HTRU2 pulsar dataset**, a binary classification dataset focused on distinguishing real pulsar signals from noise.

---

## 📈 Key Concepts Explored

- Probability-based evaluation
- ROC-AUC vs accuracy
- Ensemble intuition through agreement/disagreement
- Visual analysis of prediction confidence

---

## 🚀 Running the Notebook

1. Clone the repository
2. Open the notebook in Jupyter / Colab
3. Run all cells sequentially

## Dependencies:
pandas
numpy
scikit-learn
xgboost
matplotlib


