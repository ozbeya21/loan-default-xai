# 🧠 Loan Default Prediction with Explainable AI

This project predicts the probability of loan default using a real-world financial dataset.  
It combines modern ML techniques with explainability to build a business-ready credit risk model.

---

## 🔍 Problem

Loan defaults create major losses for financial institutions. The goal is to predict if a borrower is likely to default based on personal and financial data.

---

## 💪 Tools & Techniques

- **Model**: LightGBM (optimized with Optuna)
- **Imbalance Handling**: SMOTEENN
- **Explainability**: SHAP (Summary + Waterfall)
- **Performance**:  
  - Accuracy: **98.05%**  
  - ROC AUC: **0.893**  
  - Error Rate: **1.95%**

---

## 📊 Business Impact

The model can detect ~36% of high-risk customers and potentially prevent **520,000₺ in annual losses**.

---

## 📁 Project Structure

- `data/`: Cleaned dataset  
- `models/`: Trained LightGBM model  
- `images/`: SHAP visualizations  
- `notebooks/`: Jupyter notebook with full code  
- `requirements.txt`: Dependencies

---

## 📌 Key Insights

- Risk is higher for:
  - Customers with low payment ratios
  - Unverified income
  - Grade C/D credit scores
  - Renters and long-term loans

- SHAP helps explain individual predictions for business transparency.
