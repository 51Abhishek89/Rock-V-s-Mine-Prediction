# Rock-vs-Mine-Prediction
A machine learning model that predicts whether an underwater object is a rock or a mine using sonar signal data. Model is built using logistic regression with preprocessing, scaling, and a custom input prediction system for real-time classification.

## 📌 Overview
This project predicts whether a given object is a **mine** or a **rock** using sonar frequency data.  
The dataset contains **60 numeric features** extracted from sonar signals, and the objective is to build a classification model that can accurately identify the object type.

---

## 🎯 Motivation
Sonar-based object detection is widely used in:
- Naval defense systems  
- Underwater exploration  
- Safety & obstacle detection  

Manually analyzing sonar patterns is time-consuming.  
This project provides a **machine-learning-based automated solution** to identify objects with high accuracy.

---

## 🎓 Learning Outcomes
Through this project, I learned:
- How to load and preprocess numerical datasets  
- Feature scaling and data normalization  
- Model training and validation using Scikit-Learn  
- Evaluating classification models  
- Saving and testing the model with new input data  
- Working with Google Colab, Jupyter notebooks, and GitHub version control  

---

## ⚙️ Technical Aspects
### ✔ Dataset  
- **Sonar Dataset (CSV)** — Each row contains 60 sonar features  
- Target variable:  
  - **R** → Rock  
  - **M** → Mine  

### ✔ Problem Type  
- **Binary Classification**

### ✔ Machine Learning Workflow  
1. Load dataset  
2. Data preprocessing (cleaning, splitting, scaling)  
3. Model training (Logistic Regression)  
4. Model evaluation  
5. Predicting new values  

---

## 🛠 Technology & Libraries Used
### 🔹 **Programming Language**
- Python

### 🔹 **Libraries**
- `pandas` — Data loading & preprocessing  
- `numpy` — Numerical operations  
- `sklearn.model_selection` — Train-test split  
- `sklearn.preprocessing` — Standard scaler  
- `sklearn.linear_model` — Logistic Regression  
- `sklearn.metrics` — Accuracy score  

### 🔹 **Tools**
- Google Colab  
- GitHub  
- Jupyter Notebook  
- CSV dataset processing  

---

## 🧠 Algorithm Used
### **Logistic Regression**
Selected because:
- Works well for binary classification  
- Fast training  
- Good performance on numerical datasets  
- Interpretable  

---

## 📌 Conclusion
This project successfully builds a **machine learning model that can classify Rock vs Mine with high accuracy** using sonar signal data.  
It demonstrates key ML concepts such as preprocessing, model training, evaluation, and prediction.

The model can be extended further using:
- SVM  
- Random Forest  
- Neural Networks  

---
