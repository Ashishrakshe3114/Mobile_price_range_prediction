# 📱 Mobile Price Range Prediction - Machine Learning Mini Project

This project predicts the **price range of mobile phones** based on their technical specifications using different **machine learning classification models**.  

It utilizes models such as **K-Nearest Neighbors**, **Logistic Regression**, **Support Vector Machine**, and **Naive Bayes** to compare performance and generate predictions.

---

## 📋 Project Overview

The goal is to predict the price range (0–3) of mobile phones using features such as:
- Battery power
- RAM
- Internal memory
- Screen size
- 4G / 3G / WiFi support
- Processor cores, etc.

Dataset:
- **train.csv** → Used to train the models  
- **test.csv** → Used to generate final predictions  

The final output is saved as **Final_price.csv** with predicted price ranges for the test dataset.

---

## 🧠 Models Used
1. **KNeighborsClassifier (KNN)**
2. **Logistic Regression**
3. **Support Vector Machine (SVM)**
4. **Gaussian Naive Bayes**

Each model is trained and evaluated using:
- **Accuracy score**
- **Confusion matrix**
- **Classification report**

---

## 🧰 Requirements

Install the required Python libraries before running the script:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
