# Wine Quality Prediction

A hands-on data science project predicting wine quality using machine learning.  
This project demonstrates data cleaning, exploratory data analysis (EDA), and classification modeling on the classic Wine Quality dataset.

---

## Project Overview

This project explores the [Wine Quality dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality), which includes chemical properties of red wines from Portugal. The goal is to build a machine learning model that predicts whether a wine is "good" (quality ≥ 7) or "bad" (quality < 7) based on these properties.

---

## Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Rows:** 1,599 wines
- **Features:** 11 chemical properties (e.g., acidity, sulphates, alcohol), plus quality score (0-10)

---

## Project Steps

1. **Exploratory Data Analysis (EDA):**
   - Checked data types, missing values, and distributions
   - Explored relationships between chemical properties and wine quality
2. **Feature Engineering:**
   - Created a binary target: `good` (1) if quality ≥ 7, else `bad` (0)
3. **Modeling:**
   - Split data into training and testing sets
   - Built and evaluated a Logistic Regression and Random Forest classifier
   - Assessed model accuracy and feature importances

---

## Results

- **Logistic Regression Accuracy:** ~88%
- **Random Forest Accuracy:** (Add your result if you ran it)
- **Key Features:** Alcohol, sulphates, and volatile acidity were most influential for predicting good wine.

![Feature Importances](images/feature_importance.png) <!-- Optional: add an image if you want -->

---

## How to Run

1. Download or clone this repository.
2. Install requirements (if needed):  
3. Open `wine_quality_eda_and_model.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to reproduce the analysis and results.

---

## What I Learned

- **Data preprocessing and visualization**
- **Working with real-world, unbalanced datasets**
- **Building and evaluating classification models**
- **Interpreting model results and feature importances**

---

## References

- Cortez, Paulo, et al. "Modeling wine preferences by data mining from physicochemical properties." Decision Support Systems, 2009.
- [UCI Machine Learning Repository - Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

---

*Created by [Snezhana Ismailaj]*  
