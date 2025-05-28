
# 💳 Credit Card Fraud Detection

Detect fraudulent transactions in a credit card dataset using machine learning techniques with Python.

---

## 🚀 Project Overview

This project demonstrates how to detect anomalies (fraudulent transactions) in a highly imbalanced credit card transaction dataset using:

- Data preprocessing and cleaning
- Handling class imbalance with **SMOTE**
- Training a **Random Forest Classifier**
- Evaluating the model using metrics like **ROC-AUC**, **confusion matrix**, and **classification report**

---

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Features**:
  - 30 features: `V1` to `V28` (PCA components), `Amount`, and `Time`
  - `Class`: 0 (legit), 1 (fraud)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- imbalanced-learn (`SMOTE`)
- Google Colab (for execution)

---

## 📂 Project Structure

```
CodeClauseInternship_Fraud-Detection/
│
├── creditcard.csv                # Dataset file (not included in repo due to size)
├── fraud_detection.ipynb         # Google Colab Notebook
├── README.md                     # Project documentation
```

---

## ⚙️ How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vijaykonidana28/CodeClauseInternship_Fraud-Detection.git
   cd credit-card-fraud-detection
   ```

2. **Open the notebook** in [Google Colab](https://colab.research.google.com/):
   - Upload `creditcard.csv` when prompted
   - Run each code cell step-by-step

---

## 📈 Model Performance

- The model uses **SMOTE** to balance the data
- Trained with a **Random Forest Classifier**
- Evaluated using:
  - Confusion matrix
  - Classification report (precision, recall, f1-score)
  - ROC-AUC score

---

## 🔍 Key Learnings

- Handling **imbalanced datasets**
- Applying **SMOTE** for synthetic oversampling
- Building a robust fraud detection pipeline
- Evaluating performance beyond just accuracy

---

## 📌 To-Do (Improvements)

- Try other classifiers: XGBoost, LightGBM, SVM
- Use cross-validation and grid search for hyperparameter tuning
- Deploy the model as an API with Flask or FastAPI

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

- [Vijay kumar Konidana](https://github.com/vijaykonidana28)
