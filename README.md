# Machine Learning Classification Model Comparison

## 🧠 Overview

This project focuses on **comparing different machine learning models for a binary classification task** using a real-world dataset. The aim is to evaluate model performance, handle class imbalance, and determine which algorithm provides the most reliable results.

Three widely used machine learning models are implemented and compared:
- **Random Forest**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

The project includes data preprocessing, model training, evaluation, and hyperparameter tuning.

---

## 🚀 Key Features

- Data cleaning and preprocessing (handling missing values, encoding, scaling)
- Binary classification using multiple machine learning models
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
- Hyperparameter tuning using **GridSearchCV**
- Comparison of model strengths and weaknesses

---

## 🛠️ Tools and Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **Scikit-learn** – Machine learning models and evaluation
- **SciPy** – Dataset loading (`.arff` format)
- **GridSearchCV** – Hyperparameter tuning

---

## 📊 Models Implemented

- **Random Forest Classifier**
  - Best overall performance
  - Handles class imbalance effectively
- **Logistic Regression**
  - Strong recall for the minority class
  - More false positives
- **Support Vector Machine (SVM)**
  - High accuracy but lower precision for the minority class

---

## 📁 Project Structure

- **dataset/** – Input dataset (`.arff` file)
- **notebooks / scripts/** – Data preprocessing, training, and evaluation code
- **README.md** – Project overview

---

## ✅ Conclusion

Among the models tested, **Random Forest** achieved the best balance between accuracy, recall, and precision, making it the most reliable model for this classification task. Logistic Regression and SVM showed strong recall for the minority class but struggled with precision.

This project demonstrates a complete machine learning workflow, from preprocessing real-world data to evaluating and optimising classification models.
