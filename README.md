# 🩺 Healthcare Stroke Prediction using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge\&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge\&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

# 🩺 Healthcare Stroke Prediction

### Predicting Stroke Risk using Machine Learning

*A Machine Learning classification project that predicts the likelihood of stroke using patient healthcare records and a Decision Tree Classifier.*

---

# 📖 Table of Contents

* Project Overview
* Problem Statement
* Dataset Information
* Features
* Technologies Used
* Machine Learning Workflow
* Exploratory Data Analysis
* Model Development
* Results
* Screenshots
* Project Structure
* Installation
* Future Improvements
* Author

---

# 📌 Project Overview

Stroke is one of the leading causes of death and long-term disability worldwide. Early identification of patients at risk can support timely medical intervention and improve patient outcomes.

This project uses a Decision Tree Classifier to predict whether a patient is likely to experience a stroke based on demographic and medical information.

The project demonstrates the complete machine learning workflow, including data preprocessing, missing value handling, label encoding, exploratory data analysis (EDA), model training, evaluation, and visualization.

---

# 🎯 Problem Statement

Develop a classification model capable of predicting stroke occurrence from healthcare data using patient attributes such as age, hypertension, heart disease, glucose level, BMI, smoking status, and lifestyle factors.

---

# 📊 Dataset Information

**Dataset Size:** 5,110 patient records

**Target Variable:** `stroke`

### Features Used

* Gender
* Age
* Hypertension
* Heart Disease
* Ever Married
* Work Type
* Residence Type
* Average Glucose Level
* BMI
* Smoking Status

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# ⚙ Data Preprocessing

The following preprocessing steps were performed:

* Missing BMI values replaced using mean imputation
* Categorical variables encoded using LabelEncoder
* Data type conversion to integer format
* Feature selection
* Train-Test Split (80:20)

---

# 📈 Exploratory Data Analysis

EDA included:

* Stroke Count Distribution
* Gender vs Stroke Analysis
* Age Distribution
* Correlation Heatmap
* Missing Value Analysis

---

# 🤖 Machine Learning Model

**Algorithm Used**

* Decision Tree Classifier

The model was trained using balanced class weights to reduce the impact of class imbalance in the dataset.

---

# 🔄 Machine Learning Workflow

Healthcare Dataset

↓

Missing Value Handling

↓

Label Encoding

↓

Exploratory Data Analysis

↓

Feature Selection

↓

Train-Test Split

↓

Decision Tree Classifier

↓

Prediction

↓

Model Evaluation

---

# 📊 Model Performance

| Metric     | Value                                    |
| ---------- | ---------------------------------------- |
| Accuracy   | **91.48%**                               |
| Model      | Decision Tree Classifier                 |
| Evaluation | Confusion Matrix & Classification Report |

The model achieved high overall accuracy. Since the dataset is imbalanced, future improvements could focus on increasing recall for stroke cases using resampling techniques or ensemble methods.

---

# 📸 Project Screenshots

Add screenshots in an **assets/** folder.

### Dataset Preview

`assets/dataset-preview.png`

### Stroke Count

`assets/stroke-count.png`

### Gender vs Stroke

`assets/gender-vs-stroke.png`

### Age Distribution

`assets/age-distribution.png`

### Correlation Heatmap

`assets/correlation-heatmap.png`

### Confusion Matrix

`assets/confusion-matrix.png`

### Decision Tree

`assets/decision-tree.png`

---

# 📁 Project Structure

```text
healthcare-stroke-prediction/

├── assets/
│   ├── dataset-preview.png
│   ├── stroke-count.png
│   ├── gender-vs-stroke.png
│   ├── age-distribution.png
│   ├── correlation-heatmap.png
│   ├── confusion-matrix.png
│   └── decision-tree.png
│
├── healthcare-stroke.ipynb
├── healthcare-dataset-stroke-data.csv
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/healthcare-stroke-prediction.git

cd healthcare-stroke-prediction

pip install -r requirements.txt

jupyter notebook
```

Open the notebook and run all cells.

---

# 🚀 Future Improvements

* Hyperparameter Tuning
* Random Forest Classifier
* XGBoost Classifier
* SMOTE for class imbalance
* ROC-AUC Optimization
* Streamlit Web Application
* Model Deployment

---

# 👩‍💻 Author

**Shreya Pramod Patil**

Bachelor of Engineering (Computer Engineering)

Interested in Machine Learning, Data Science, Artificial Intelligence, and Python Development.

---

<div align="center">

⭐ If you found this project useful, please consider giving it a Star!

</div>
