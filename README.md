# linear-regression-weather-Datasets
# 🌦️ Weather History Linear Regression Model

This project uses **Linear Regression** to model and predict weather-related data from the [Weather History dataset](https://www.kaggle.com/datasets/muthuj7/weather-dataset). The goal is to predict a continuous target variable (e.g., temperature, humidity, etc.) using various weather features.

---

## 📊 Project Overview

This model applies a supervised regression technique — **Linear Regression** — to a dataset containing historical weather data. It aims to find a linear relationship between features like temperature, humidity, visibility, wind speed, and more, and the target variable.

---

## 📁 Dataset

- **Source**: Kaggle - Weather History Dataset
- **Features**: Includes date/time, temperature, humidity, visibility, wind speed, wind bearing, and conditions.
- **Target Variable**: *(Specify which feature was predicted — e.g., `Temperature`, `Humidity`, etc.)*

---

## ⚙️ Workflow

1. Data Loading and Cleaning
2. Exploratory Data Analysis (EDA)
3. Correlation and Hihly Correlated value Selection
4. Train-Test Split
5. Model Training with Linear Regression
6. Model Evaluation using R² Score
7. Visualization of Predictions

---

## 🧪 Model Performance

| Metric       | Value     |
|--------------|-----------|
| R² Score (Train) | **0.9881** |
| R² Score (Test)  | **0.9883** |

> ✅ The model generalizes well with a high R² score on both training and test datasets, indicating excellent predictive accuracy and minimal overfitting.

---

## 📌 Key Insights

- The model explains **~98.8%** of the variance in the target variable.
- Features like `Humidity`, `Wind Speed`, and `Temperature` have a strong linear relationship with the target.
- Linear Regression is effective on this dataset without complex transformations or regularization.

---

## 📚 Requirements

- Python 3.x
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn

You can install dependencies using:

```bash
pip install -r requirements.txt
