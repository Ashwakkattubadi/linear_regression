# 🏥 Insurance Charges Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts **medical insurance charges** using **Linear Regression** with Python and Scikit-learn.

This project demonstrates the complete machine learning workflow—from loading and preprocessing data to training a regression model and evaluating its performance using **R² Score** and **Adjusted R² Score**.

---

## 📌 Project Overview

Medical insurance costs depend on several factors such as:

* Age
* Gender
* BMI (Body Mass Index)
* Number of Children
* Smoking Status

In this project, a Linear Regression model is trained to predict insurance charges based on these features.

---

## 🚀 Features

* Data preprocessing using Pandas
* Encoding categorical variables
* Exploratory Data Visualization with Seaborn
* Train-Test Split
* Linear Regression Model
* Prediction of Insurance Charges
* Model Evaluation using:

  * R² Score
  * Adjusted R² Score

---

## 📂 Dataset

**Dataset:** `insurance.csv`

### Features

| Column   | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the person                           |
| sex      | Gender (Male/Female)                        |
| bmi      | Body Mass Index                             |
| children | Number of children covered by insurance     |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (Target Variable) |

---

## 🛠 Technologies Used

* Python
* Pandas
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Load the dataset
2. Convert categorical values into numerical values
3. Visualize relationships using Seaborn
4. Split data into training and testing sets
5. Train a Linear Regression model
6. Predict insurance charges
7. Evaluate model performance using:

   * R² Score
   * Adjusted R² Score

---

## 📈 Model Evaluation

The model is evaluated using:

* **R² Score** – Measures how well the model explains the variance in the target variable.
* **Adjusted R² Score** – Adjusts the R² score by considering the number of input features, helping prevent misleading improvements caused by unnecessary variables.

---

## 📁 Project Structure

```text
linear_regression/
│
├── insurance.csv
├── linear_reg.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/Ashwakkattubadi/linear_regression.git
```

2. Navigate to the project folder

```bash
cd linear_regression
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook and run all cells.

---

## 📚 Concepts Practiced

* Data Preprocessing
* Feature Encoding
* Exploratory Data Analysis (EDA)
* Linear Regression
* Train-Test Split
* Model Prediction
* R² Score
* Adjusted R² Score

---

## 🎯 Future Improvements

* Add Multiple Linear Regression with One-Hot Encoding
* Compare with Ridge and Lasso Regression
* Perform Feature Engineering
* Build a Streamlit Web Application
* Hyperparameter Optimization

---

## 👨‍💻 Author

**Ashwak Kattubadi**

⭐ If you found this project helpful, consider giving this repository a star!
