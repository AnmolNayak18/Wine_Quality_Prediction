# 🍷 Wine Quality Prediction

This project focuses on predicting the quality of red and white wines based on their physicochemical properties using machine learning models. The goal is to help understand which features influence wine quality the most and build a predictive model that performs reasonably well on real-world data.

---

## 📁 Dataset

The dataset is taken from the UCI Machine Learning Repository and includes two CSV files:

- `winequality-red.csv` — 1,599 red wine samples
- `winequality-white.csv` — 4,898 white wine samples

Each entry contains 11 physicochemical tests (e.g., acidity, alcohol, pH) and a **quality score (0–10)** rated by human tasters.

---

## 🧠 Objective

- Merge and analyze red and white wine data
- Explore relationships between features and wine quality
- Train regression models to predict the `quality` score
- Evaluate which features are most influential

---

## 🔍 Features Used

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Type (Red or White)

---

## 🧪 Models Applied

| Model                 | R² Score | RMSE (approx.) |
|----------------------|----------|----------------|
| Linear Regression     | ~0.30    | ~0.72          |
| SGD Regressor         | ~0.30    | ~0.72          |
| **Random Forest**     | **~0.51**| **~0.61**      |

> 🔎 The best performing model was the **Random Forest Regressor**, which was able to explain around **50% of the variance** in wine quality.

---

## 📊 Key Insights

- **Alcohol** has the highest positive correlation with wine quality.
- **Volatile acidity** and **density** negatively impact quality.
- The models perform moderately well, but human taste involves subjective variables not present in the dataset.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📁 Repository Structure

