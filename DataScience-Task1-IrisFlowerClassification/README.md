# 🌸 Iris Flower Classification

## 📌 Project Overview

This project is part of my **Data Science Internship** at **Oasis Infobyte**.

The objective is to build machine learning models that classify iris flowers into three species:
- Setosa
- Versicolor
- Virginica

using their physical measurements.

---

## 🎯 Objective

Develop and compare multiple machine learning classification models to predict the species of an iris flower using the built-in Iris dataset from scikit-learn.

---

## 📂 Dataset

- Dataset: Iris Dataset
- Source: `sklearn.datasets.load_iris()`
- Total Samples: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

Target Classes:
- Setosa
- Versicolor
- Virginica

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

1. Load the Iris Dataset
2. Perform Exploratory Data Analysis (EDA)
3. Visualize the data using Pair Plot and Box Plots
4. Select important features
5. Split the dataset into training and testing sets
6. Train two Machine Learning models:
   - Logistic Regression
   - Random Forest Classifier
7. Evaluate models using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
8. Compare the results and identify the best-performing model

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

- Dataset Shape
- Data Types
- Missing Values
- Descriptive Statistics
- Pair Plot
- Box Plots

---

## 🤖 Machine Learning Models

### Logistic Regression

Used as a baseline classification algorithm.

### Random Forest Classifier

Used to improve prediction accuracy through ensemble learning.

---

## 📊 Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

---

## 🏆 Best Model

Random Forest Classifier achieved the highest accuracy and provided better classification performance, making it the best model for this dataset.

---

## 📸 Project Screenshots

Example:

- Pair Plot
- Box Plot
- Confusion Matrix
- Accuracy Comparison

(Add images from the `images` folder.)

---

## 📁 Project Structure

```text
DataScience-Task1-IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
├── README.md
├── requirements.txt
├── model.pkl
└── images/
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone <repository-link>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run **Iris_Flower_Classification.ipynb**

---

## 📌 Results

- Successfully classified iris flower species.
- Compared Logistic Regression and Random Forest.
- Random Forest achieved the best overall performance.

---

## 👨‍💻 Author

**Mahip Singh**

Data Science Intern

Oasis Infobyte
