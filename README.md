# Student-Performance-Prediction


This project analyzes student academic performance using data visualization and machine learning models. The goal is to find patterns and predict student scores based on different attributes.

## Dataset

- Source: [Kaggle - Student Scores Dataset](https://www.kaggle.com/datasets/markmedhat/student-scores)
- Includes:
  - Student names, gender, email
  - Subject scores: Math, History, Physics, Chemistry, Biology, English, Geography

## Features

- Data cleaning and preprocessing
- Outlier removal using IQR method
- Feature engineering (`Total_score`, `Percentage`)
- Exploratory Data Analysis (EDA)
- Machine learning models to predict percentage score

## ML Models Used

- Linear Regression
- Polynomial Regression (degree 3)
- XGBoost Regressor

## Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score
- Feature importance visualization from XGBoost

## Libraries Used

- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

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
