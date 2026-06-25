# Tubes-Siscer
anggota kelompok 6 : Muhammad Maulana Darmawansyah, Febriani Zahra, Fathahul Rizqa Arrahman
# 🏥 Medical Insurance Cost Prediction using K-Nearest Neighbor and Decision Tree Regression

## 📌 Project Overview

This project aims to compare the performance of **K-Nearest Neighbor (KNN) Regression** and **Decision Tree Regression** in predicting medical insurance costs using the **Medical Insurance Dataset**.

The project includes data preprocessing, feature engineering, hyperparameter tuning, model evaluation, and performance comparison using several regression metrics.

---

## 🎯 Objectives

* Predict medical insurance charges.
* Compare the performance of K-Nearest Neighbor Regression and Decision Tree Regression.
* Evaluate the effectiveness of preprocessing and feature engineering on prediction performance.

---

## 📂 Dataset

**Dataset:** Medical Insurance Dataset

### Features

| Feature  | Description                              |
| -------- | ---------------------------------------- |
| age      | Age of the policyholder                  |
| bmi      | Body Mass Index                          |
| smoker   | Smoking status                           |
| children | Number of children covered by insurance  |
| charges  | Medical insurance cost (Target Variable) |

Target Variable:

* **charges**

---

## ⚙️ Data Preprocessing

The preprocessing steps include:

* Handling missing values (if any)
* Label Encoding for categorical variables
* StandardScaler for feature normalization
* Log Transformation on the target variable (`charges`)
* Feature Engineering (`bmi_smoker`)

---

## 🤖 Machine Learning Models

### 1. K-Nearest Neighbor Regression

Used to predict insurance charges based on the nearest neighboring samples.

Hyperparameter tuning:

* n_neighbors
* weights
* metric

using **GridSearchCV**.

---

### 2. Decision Tree Regression

Used as a comparison model.

Hyperparameter tuning:

* max_depth
* min_samples_split
* min_samples_leaf
* criterion

using **GridSearchCV**.

---

## 🔄 Validation Method

Model evaluation uses:

* K-Fold Cross Validation
* GridSearchCV

to obtain optimal hyperparameters and reduce evaluation bias.

---

## 📊 Evaluation Metrics

The models are evaluated using:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)
* R² Score (Coefficient of Determination)

---

## 📈 Visualizations

This notebook contains several visualizations, including:

* Distribution of Charges
* Correlation Heatmap
* BMI vs Charges by Smoking Status
* Actual vs Predicted Values
* Residual Analysis
* Model Performance Comparison

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the notebook

```text
ML_Medical_Insurance_Regresi.ipynb
```

4. Run all cells sequentially.

---

## 📌 Results

The experiment compares KNN Regression and Decision Tree Regression using the same preprocessing pipeline and evaluation metrics.

Based on the evaluation, the model with the better performance is selected according to MAE, RMSE, MAPE, and R² Score.

---

## 👨‍💻 Author

**Muhammad Maulana Darmawansyah**
**Febriani Zahra**
**Fathahul Rizqa Arrahman**

Bachelor of Information Technology

Telkom University

---

## 📄 License

This project is developed for educational and academic purposes.

