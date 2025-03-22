# 🧠 Obesity Risk Analysis & BMI Prediction

This project explores obesity-related factors and predicts BMI using various regression models. It also classifies whether an individual is overweight using logistic regression. The analysis is based on the **Obesity Dataset** from the UCI Machine Learning Repository.

---

## 📊 Project Overview

### ✅ Objectives
- Perform **data cleaning**, **feature engineering**, and **exploratory data analysis (EDA)**
- Predict **Body Mass Index (BMI)** using:
  - Simple Linear Regression
  - Polynomial Regression
  - Bivariate Regression
  - Ridge, Lasso, and ElasticNet
- Classify **overweight status (BMI ≥ 25)** using **Logistic Regression**
- Visualize results and evaluate model performance

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository  
- **Dataset Name**: [Estimation of Obesity Levels based on Eating Habits and Physical Condition](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition)

> The dataset includes synthetic data on individuals’ eating habits, physical condition, and lifestyle, useful for predicting obesity-related health outcomes.

---

## 🔍 Key Features

| Feature Type       | Description |
|--------------------|-------------|
| `Weight`, `Height` | Used to calculate BMI |
| `Gender`, `SMOKE`, `FAVC`, etc. | Lifestyle factors |
| `BMI`              | Derived feature used in regression |
| `overweight`       | Binary classification target (BMI ≥ 25) |

---

## 🧪 Models Used

### 🧮 Regression
- Linear Regression (Simple, Bivariate)
- Polynomial Regression (1D and 2D)
- Ridge Regression
- Lasso Regression
- ElasticNet Regression

### 🔐 Classification
- Logistic Regression for binary classification of overweight status

---

## 📈 Evaluation Metrics

- **R² (Coefficient of Determination)**
- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-Score)**
- **Matthews Correlation Coefficient (MCC)**

---

## 📷 Visualizations

- Correlation Heatmap
- Missing Data Bar Plot
- Linear and Polynomial Regression Plots
- 3D Bivariate Regression Planes
- Confusion Matrix Heatmap

---

## 📂 Project Structure

```
obesity-bmi-analysis/
│
├── data/
│   └── ObesityDataSet_raw_and_data_sinthetic.csv
│
├── Full_Obesity_Analysis.ipynb   # Full Jupyter notebook
├── README.md
└── requirements.txt
```

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mgedna/obesity-bmi-analysis.git
   cd obesity-bmi-analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from the [UCI Repository](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition) and place it in the `data/` folder.

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook Obesity_BMI_Analysis.ipynb
   ```

---

## 🧠 Author

Edna Memedula 
📫 [LinkedIn](www.linkedin.com/in/edna-memedula-24b519245) • [GitHub](https://github.com/mgedna) 
