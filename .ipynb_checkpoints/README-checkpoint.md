# 🏥 Insurance Charges Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts **medical insurance charges** using **Linear Regression** and explores techniques to improve model performance using **Feature Engineering**, **Ridge Regression**, and **Lasso Regression**.

This repository demonstrates the complete machine learning workflow—from data preprocessing and feature engineering to model training, evaluation, and regularization.

---

# 📌 Project Overview

Medical insurance costs depend on several factors such as:

* Age
* Gender
* BMI (Body Mass Index)
* Number of Children
* Smoking Status
* Residential Region

The objective of this project is to build and improve a Linear Regression model that predicts medical insurance charges using these features.

---

# 🚀 Repository Contents

## 📘 1. Basic Linear Regression (`linear_regression.ipynb`)

A beginner-friendly implementation of Linear Regression.

### Includes

* Loading the dataset
* Label Encoding (`sex` and `smoker`)
* Basic Data Visualization
* Train-Test Split
* Linear Regression Model
* Prediction
* R² Score
* Adjusted R² Score

> **Note:** The `region` column is removed in this notebook. No One-Hot Encoding or Feature Engineering is applied.

---

## 📗 2. Feature Engineering (`feature_engineering.ipynb`)

Builds upon the basic model by applying Feature Engineering techniques before training.

### Feature Encoding

* One-Hot Encoding for the `region` column

### Derived Features

* Underweight Indicator
* Normal Weight Indicator
* Overweight Indicator

### Interaction Features

* `age_smokers`
* `bmi_smokers`

After creating these additional features, a Linear Regression model is trained and evaluated.

---

## 📙 3. Ridge & Lasso Regularization (`lasso_ridge.ipynb`)

This notebook focuses on improving model generalization using regularization techniques.

### Includes

* Linear Regression (Baseline)
* Train R² vs Test R² Comparison
* Underfitting and Overfitting Analysis
* Ridge Regression
* Lasso Regression
* Comparison of Model Performance
* Regularization using different Alpha values

The notebook demonstrates how regularization helps reduce overfitting and improve model generalization.

---

# 📂 Dataset

**Dataset:** `insurance.csv`

### Dataset Features

| Column   | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the person                           |
| sex      | Gender                                      |
| bmi      | Body Mass Index                             |
| children | Number of children                          |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (Target Variable) |

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 📊 Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Feature Encoding
4. Feature Engineering
5. Exploratory Data Analysis
6. Train-Test Split
7. Linear Regression
8. Model Evaluation
9. Overfitting & Underfitting Analysis
10. Ridge Regression
11. Lasso Regression
12. Model Comparison

---

# 📈 Model Evaluation

The models are evaluated using:

* R² Score
* Adjusted R² Score
* Training R² Score
* Testing R² Score

The project also compares the performance of Linear Regression, Ridge Regression, and Lasso Regression to analyze the effect of regularization.

---

# 📁 Project Structure

```text
linear_regression/
│
├── insurance.csv
├── linear_regression.ipynb
├── feature_engineering.ipynb
├── lasso_ridge.ipynb
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Ashwakkattubadi/linear_regression.git
```

### 2. Navigate to the project directory

```bash
cd linear_regression
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open any notebook

* `linear_regression.ipynb` – Basic Linear Regression
* `feature_engineering.ipynb` – Feature Engineering
* `lasso_ridge.ipynb` – Ridge & Lasso Regularization

Run all cells to reproduce the results.

---

# 📚 Concepts Practiced

* Data Preprocessing
* Label Encoding
* One-Hot Encoding
* Derived Features
* Interaction Features
* Exploratory Data Analysis (EDA)
* Train-Test Split
* Linear Regression
* Feature Engineering
* Model Evaluation
* R² Score
* Adjusted R² Score
* Overfitting & Underfitting Detection
* Ridge Regression
* Lasso Regression
* Regularization

---

# 🎯 Future Improvements

* Feature Scaling
* Polynomial Regression
* Elastic Net Regression
* Cross Validation
* Hyperparameter Tuning using GridSearchCV
* Residual Analysis
* Model Deployment using Streamlit or Flask

---

# 👨‍💻 Author

**Ashwak Kattubadi**