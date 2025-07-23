# 🚗 Car Price Prediction using Machine Learning

## 📌 Overview
Built a regression-based machine learning model to predict car prices using a dataset of 3,000+ used cars. Implemented Linear Regression, Decision Tree, and Random Forest models. Evaluated performance with R² and RMSE.

## 🧰 Tools & Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Dataset
- Source: [Kaggle Used Car Dataset](https://www.kaggle.com/)
- Features: Year, Price, Fuel Type, Mileage, Engine, Transmission, Owner Type

## 🔍 Project Steps
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Building & Evaluation  
5. Visualizations

## 📊 Visualizations

| Chart | Description |
|-------|-------------|
| ![heatmap](images/correlation_heatmap.png) | Correlation heatmap |
| ![boxplot](images/price_boxplot.png) | Outlier detection using boxplots |

## 🎯 Key Outcomes
- Achieved **87% R² score** using Random Forest
- Identified key predictors: Year, Fuel Type, Transmission
- Built a reusable ML pipeline for regression tasks

## 🚀 Run This Project
```bash
1. Clone the repo
2. Install dependencies (requirements.txt)
3. Run car_price_prediction.ipynb
