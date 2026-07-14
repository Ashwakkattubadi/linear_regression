# 🏥 Insurance Charges Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts **medical insurance charges** using **Linear Regression** with Python and Scikit-learn.

This repository contains **two implementations**:

* **Basic Linear Regression** – A simple implementation using basic preprocessing.
* **Feature Engineering + Linear Regression** – An improved version that applies feature engineering techniques before training the model.

The project demonstrates the complete machine learning workflow, from data preprocessing to model evaluation using **R² Score** and **Adjusted R² Score**.

---

# 📌 Project Overview

Medical insurance costs depend on several factors such as:

* Age
* Gender
* BMI (Body Mass Index)
* Number of Children
* Smoking Status
* Residential Region

The goal of this project is to build a Linear Regression model that predicts medical insurance charges based on these features.

---

# 🚀 Project Files

### 📘 1. Basic Linear Regression (`linear_regression.ipynb`)

This notebook covers the fundamental workflow of building a Linear Regression model.

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

### 📗 2. Feature Engineering + Linear Regression (`feature_engineering.ipynb`)

This notebook extends the basic model by applying Feature Engineering techniques before training.

### Additional Techniques Used

#### Feature Encoding

* One-Hot Encoding for the `region` column

#### Derived Features

* Underweight Indicator
* Normal Weight Indicator
* Overweight Indicator

#### Interaction Features

* `age_smokers`
* `bmi_smokers`

After creating these additional features, the Linear Regression model is trained again and evaluated.

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
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 📊 Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Feature Encoding
4. Feature Engineering (Advanced Notebook)
5. Exploratory Data Analysis
6. Train-Test Split
7. Linear Regression
8. Prediction
9. Model Evaluation

---

# 📈 Model Evaluation

Both notebooks evaluate the model using:

* **R² Score** – Measures how well the model explains the variance in the target variable.
* **Adjusted R² Score** – Considers both the model performance and the number of input features.

---

# 📁 Project Structure

```text
linear_regression/
│
├── insurance.csv
├── linear_regression.ipynb
├── feature_engineering.ipynb
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/Ashwakkattubadi/linear_regression.git
```

2. Navigate to the project directory

```bash
cd linear_regression
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open either notebook:

* `linear_regression.ipynb` (Basic Model)
* `feature_engineering.ipynb` (Feature Engineering Version)

Run all cells.

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
* Model Prediction
* R² Score
* Adjusted R² Score

---

# 🎯 Future Improvements

* Feature Scaling
* Outlier Detection and Treatment
* Feature Selection
* Polynomial Regression
* Ridge Regression
* Lasso Regression
* Cross Validation
* Hyperparameter Tuning
* Streamlit Deployment

---

# 👨‍💻 Author

**Ashwak Kattubadi**

⭐ If you found this project helpful, consider giving this repository a star!
