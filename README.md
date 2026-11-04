# Breast Cancer Prediction using XGBoost Classifier

A machine learning project built with Python and XGBoost that predicts breast cancer diagnosis using the **Breast Cancer dataset** (`load_breast_cancer`). The project implements an optimized gradient boosting classification algorithm via `XGBClassifier`[cite: 10].

## 📋 Features

* **Data Loading & Prep**: Loads the built-in breast cancer diagnostic dataset, converts it into a Pandas DataFrame, and partitions it into training and test sets (`train_test_split`)[cite: 10].
* **Extreme Gradient Boosting Model**: Trains an `XGBClassifier` using specialized hyperparameters (such as `n_estimators=100`, `learning_rate=0.5`, `max_depth=1`, and L2 regularization)[cite: 10].
* **Model Evaluation**: Assesses classification performance and generalization capability using accuracy scores and model scoring across training and testing splits[cite: 10].

## 🛠️ Tech Stack

* **Python**[cite: 10]
* **Pandas & NumPy** (Data manipulation)[cite: 10]
* **XGBoost** (`XGBClassifier` for gradient boosting)[cite: 10]
* **Scikit-Learn** (Dataset, metrics, and splitting utilities)[cite: 10]

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/breast-cancer-classification-xgboost.git](https://github.com/your-username/breast-cancer-classification-xgboost.git)
