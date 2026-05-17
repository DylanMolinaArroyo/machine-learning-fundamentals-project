# Applied Machine Learning Project

A comprehensive machine learning project.

This project applies five core ML algorithms to real-world datasets sourced from Kaggle, covering a wide range of problem types including regression, classification, clustering, and time series forecasting.

---

## Project Overview

The goal of this project is to demonstrate correct implementation, evaluation, and interpretation of fundamental machine learning algorithms applied to real-world data. Each dataset presents a unique challenge, requiring different preprocessing strategies, model choices, and evaluation metrics.

---

## Datasets & Algorithms

| Problem Type | Algorithm(s) | Dataset |
|---|---|---|
| 🫀 Binary Classification | Logistic Regression & KNN | Heart Failure Prediction |
| 🏠 Regression | Linear Regression & KNN | House Prices (Ames, Iowa) |
| ₿ Time Series Forecasting | Moving Average & ARIMA | Bitcoin Historical Prices |
| 🛒 Clustering | K-Means & GMM | Customer Personality Analysis |
| 🎓 Regression & Classification | Linear & Logistic Regression | Student Performance in Exams |

---

## Topics Covered

- **Data Exploration** — understanding structure, distributions, and feature relationships
- **Data Preprocessing** — handling missing values, encoding, scaling, and train/test splitting
- **Model Implementation** — applying multiple ML algorithms per dataset
- **Model Evaluation** — using appropriate metrics (RMSE, R², Accuracy, F1-Score, Silhouette Score, etc.)
- **Result Interpretation** — comparing models and extracting meaningful insights

---

## Key Results

| Dataset | Best Model | Key Metric |
|---|---|---|
| Heart Failure | KNN (K=7) | Accuracy: ~90% |
| House Prices | KNN Regression (K=10) | R²: 0.8188 |
| Bitcoin Prices | ARIMA(5,1,0) | Lower RMSE vs Moving Average |
| Customer Segmentation | GMM (K=6) | 6 distinct customer profiles |
| Student Performance | Linear Regression | R²: 0.8804 |

---

## Project Structure

```
 ┣ 📓 ProyectoIA_v4.ipynb     # Main notebook with all models and analysis
 ┣ 📄 README.md
```

> **Note:** Datasets are not included in this repository due to file size. Download them from the Kaggle links below and place them on a google drive folder.

---

## Dataset Sources

- [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data)
- [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- [Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)
- [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels
```

The notebook was developed and tested on **Google Colab**.

---

## Authors

- **Dylan Andrey Molina Arroyo**
- **Jose Fabricio Alfaro Cabezas**
- **Andrés Esquivel Gómez**
