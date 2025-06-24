# Task2EDA
 # Task 2 - Exploratory Data Analysis (EDA) on Titanic Dataset

## 🔍 Objective:
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand data patterns, handle missing values, visualize distributions, and prepare it for machine learning.

---

## 📁 Dataset:
- *Source:* [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- *File used:* train.csv

---

## 📌 What I Did:

### 1. *Imported and Explored the Dataset*
- Loaded the dataset using pandas
- Viewed shape, data types, and missing values

### 2. *Handled Missing Values*
- Filled Age with median
- Filled Embarked with mode
- Dropped Cabin due to excessive nulls

### 3. *Encoded Categorical Variables*
- Label encoded Sex (male = 0, female = 1)
- One-hot encoded Embarked (created Embarked_Q, Embarked_S)

### 4. *Standardized Numerical Features*
- Used StandardScaler to scale Age, Fare, SibSp, and Parch

### 5. *Visualized and Removed Outliers*
- Created boxplots for numerical columns
- Removed outliers using the IQR method

---

## 📊 Tools & Libraries Used:
- *Pandas* – for data handling
- *NumPy* – for numerical operations
- *Matplotlib / Seaborn* – for visualizations
- *Scikit-learn* – for preprocessing (StandardScaler)

---

## 📷 Screenshots:
You can view EDA plots (boxplots, histograms, heatmaps) in the notebook.

---

## 📁 Files in this Repo:
- Titanic_EDA.ipynb – Jupyter/Colab notebook with all steps
- train.csv – Titanic dataset file
- README.md – This file

---

## 🔗 Submission Link:
Submitted via Google Form as instructed in the task.

---

## 🙋‍♀️ Done By:
*Sharmila L*  
AI & ML Internship – Task2
