# 🏦 Loan Approval Prediction using Support Vector Machine (SVM)

A machine learning project to predict loan approval outcomes based on borrower data using a **Support Vector Machine (SVM)** with a **linear kernel**. The model focuses on understanding applicant attributes such as credit score, income, and employment history to forecast loan eligibility.

---

## 📌 Project Overview

This project addresses a common financial challenge: **automated loan approval**. By analyzing a variety of financial and demographic attributes, the model can determine the likelihood of loan approval with **up to 92% accuracy**.

---

## 🧠 Key Features

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| ✅ Binary Classification     | Classifies whether a loan should be approved or rejected.                  |
| 🧹 Data Preprocessing       | Cleaned, encoded, and normalized borrower data for optimal performance.    |
| 🔄 Cross-Validation         | Used **k-fold cross-validation** to prevent overfitting.                   |
| 🔧 Hyperparameter Tuning    | Performed tuning (e.g., C value) to improve model accuracy.                |
| 📊 Performance Evaluation   | Evaluated using accuracy score and visualization metrics.                  |

---

## 🗂️ Dataset Attributes

| Attribute            | Description                        |
|----------------------|------------------------------------|
| `Credit Score`       | Numerical indicator of credit risk |
| `Annual Income`      | Reported income of the borrower    |
| `Employment History` | Duration/type of employment        |
| `Loan Amount`        | Requested loan size                |
| `Approval Status`    | Target variable (approved/rejected)|

*(Note: This is a simulated or anonymized dataset)*

---

## 🚀 Model Details

- **Model**: Support Vector Machine (SVM) with **linear kernel**
- **Accuracy Achieved**: **~92%**
- **Evaluation Metric**: Accuracy, confusion matrix, precision-recall

---

## 🧰 Tech Stack

| Tool/Library     | Role                                        |
|------------------|---------------------------------------------|
| `Python 3.x`     | Programming language                        |
| `Scikit-learn`   | Machine learning model & metrics            |
| `Pandas`         | Data manipulation and loading               |
| `NumPy`          | Numerical computations                      |
| `Matplotlib`     | Visualizations and plots                    |
| `Seaborn`        | Statistical data visualization              |

---

## 📊 Visualizations

- **Feature distribution** using histograms and boxplots
- **Correlation heatmap** for feature importance
- **Confusion matrix** to inspect classification results

---

## 📁 Project Structure

