# Student-Performance-Prediction

This project focuses on analyzing student performance using machine learning techniques and data visualization. The goal is to uncover patterns in academic performance and build predictive models to help educators understand the factors influencing student success.

---

## 🔍 Overview

This notebook includes:

- **Exploratory Data Analysis (EDA)** with `pandas`, `matplotlib`, and `seaborn`
- **Data Cleaning & Preprocessing** – handling nulls, encoding categorical features
- **Correlation Analysis** to understand relationships between features
- **Machine Learning Models** for classification
- **Evaluation Metrics** such as accuracy, precision, recall, and confusion matrix

---

## 🧰 Tech Stack

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 📁 Dataset

The dataset includes the following columns:

- `gender`
- `race/ethnicity`
- `parental level of education`
- `lunch`
- `test preparation course`
- `math score`
- `reading score`
- `writing score`

> *(If sourced from an external platform, you can add a link like: [Download Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams))*

---

## 🧠 ML Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

These models were trained to predict if a student is performing **above average** based on test scores and demographic indicators.

---

## 📈 Results

Model performance was measured using:
- **Accuracy**
- **Precision & Recall**
- **Confusion Matrix**

Random Forest generally performed the best in terms of balanced accuracy and generalization.

---

## 🚀 How to Run

To run this project locally:

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/Student-Performance-ML.git
2. Navigate to the project folder
  ```bash
  cd Student-Performance-ML
```
3. Launch Jupyter Notebook
  ```bash
  jupyter notebook Student_Performance.ipynb
