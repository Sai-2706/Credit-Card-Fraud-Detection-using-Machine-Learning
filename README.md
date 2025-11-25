# Credit-Card-Fraud-Detection-using-Machine-Learning

Absolutely Sahith — here is a **clean, professional, GitHub-friendly README.md** for your **Credit Card Fraud Detection Project** 🌟

This README is written in a way that recruiters and developers will love — you can **copy–paste directly into your GitHub repo**.

---

# 💳 **Credit Card Fraud Detection using Machine Learning**

## 📌 **Project Overview**

Credit card fraud is a major challenge in the financial industry.
In this project, I built a machine learning model that detects **fraudulent transactions** using the popular **Credit Card Fraud Dataset**, which contains anonymized features and is highly imbalanced.

The goal of this project is to:
✔ Perform data preprocessing
✔ Handle missing values
✔ Analyze data imbalance
✔ Apply SMOTE oversampling
✔ Build a classification model
✔ Evaluate the performance
✔ Predict whether a new transaction is Fraud or Not Fraud

---

## 🛠️ **Tech Stack Used**

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn**
* **Scikit-Learn**
* **Imbalanced-Learn (SMOTE)**
* **Google Colab / Jupyter Notebook**

---

## 📂 **Dataset**

This project uses the **Kaggle Credit Card Fraud Dataset** which contains:

* 284,807 total transactions
* 492 frauds (Class = 1)
* Highly imbalanced (0.17% fraud)
* 30 numerical features (V1–V28, Time, Amount)

Dataset includes:

* **Class = 0** → Legitimate
* **Class = 1** → Fraudulent

---

## 🔍 **Project Workflow**

### 1️⃣ **Data Loading**

* Loaded the creditcard.csv dataset
* Checked dataframe structure, missing values, duplicates, shape

---

### 2️⃣ **Exploratory Data Analysis (EDA)**

Performed visualization using Pandas, Matplotlib, and Seaborn:

* Class distribution
* Boxplots for outliers
* Correlation heatmap
* Amount & Time distribution
* Fraud vs Legitimate comparison

---

### 3️⃣ **Data Preprocessing**

* Handled missing values using `.isnull().sum()`
* Removed duplicates using `.duplicated().sum()`
* Normalized / scaled features using `StandardScaler`
* Balanced dataset using **SMOTE (Synthetic Minority Oversampling Technique)**

---

### 4️⃣ **Train–Test Split**

Split the data into:

```
80% → Training
20% → Testing
```

---

### 5️⃣ **Model Training**

Built a classification model using:
### ✔ **Logistic Regression**


### 6️⃣ **Model Evaluation**

Evaluated the model using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC–AUC Curve

These metrics are important because dataset is **highly imbalanced**.

---

### 7️⃣ **Fraud Prediction**

Used the trained model to predict:

```python
The transaction is legitimate.
or
The transaction is fraudulent.
```

Based on the model output.

---

## 🚀 **Results**

* Achieved a balanced dataset using SMOTE
* Model successfully detects fraudulent transactions
* Good Precision/Recall for Class 1 (Fraud)
* Improves fraud detection accuracy significantly

(Add your exact accuracy / AUC score here)
✔ Example:

```
Accuracy: 98.7%
AUC Score: 0.97
```

---

## 📸 **Visualizations Included**

* Class imbalance plot
* Histogram of Amount & Time
* Boxplots for outliers
* Correlation heatmap
* Confusion matrix
* ROC curve
