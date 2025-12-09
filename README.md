# Housing Price Prediction Model

## 🚀 Project Overview

This project implements a **Housing Price Prediction Model** using popular Machine Learning and Data Science techniques. The goal is to predict the final sale price of a house based on various features such as square footage, number of bedrooms, location, and condition.

The machine learning pipeline involves extensive data cleaning, feature engineering, and the training of multiple regression models to find the best fit.

## ✨ Features

* **Exploratory Data Analysis (EDA):** Initial inspection of features like `price`, `bedrooms`, `bathrooms`, and living space metrics.
* **Data Cleaning & Preprocessing:** Handling of missing values using techniques like **median imputation** (`SimpleImputer`).
* **Feature Engineering:** Creation of new, informative features like `price_per_sq_feet`.
* **Categorical Feature Handling:** Using **One-Hot Encoding** to convert location data (`city`) into a model-friendly format.
* **Model Comparison:** (Implied, typically the next step in the pipeline) Training and evaluating multiple regression models (e.g., Linear Regression, Decision Tree, Random Forest) to determine the highest-performing predictor.

## 🛠️ Technologies Used

| Tool/Library | Purpose |
| :--- | :--- |
| **Python** | Primary programming language. |
| **Jupyter Notebooks** | Used for iterative development and documentation. |
| **Pandas** | Data manipulation and analysis. |
| **NumPy** | Numerical operations and array handling. |
| **Scikit-learn** | Machine Learning algorithms, preprocessing (`SimpleImputer`, `OneHotEncoder`), and model selection.
| **Matplotlib/Seaborn** | Data visualization (as seen by the imports in notebooks).

