# House Price Prediction

This repository contains a Jupyter notebook that builds and evaluates a **house price prediction model** using supervised machine learning.  
The goal is to learn how different property features (size, rooms, location, etc.) influence market value and use that model to predict house prices for new data.

---

## Objectives

- Load and explore a housing dataset  
- Clean and preprocess data  
- Train regression models to predict house prices  
- Evaluate model performance using standard metrics  
- Visualize key trends and results  

---

## Dataset

The notebook uses a housing dataset containing features such as:

- Square footage / lot area  
- Number of bedrooms / bathrooms  
- Age or condition of the property  
- Location-related factors (zip code, neighborhood, etc.)  
- Additional numerical or categorical attributes related to housing  

**Target Variable:** `SalePrice` (house price)

---

## Workflow Overview

### 1. Data Import
Load the dataset using Python libraries such as `pandas`.

### 2. 🔍 Exploratory Data Analysis (EDA)
- Check structure, missing values, duplicates  
- Visualize correlations and distributions  
- Understand key price-driving features  

### 3. Data Cleaning & Preprocessing
- Handle missing values  
- Encode categorical variables  
- Normalize/scale numerical features  
- Train-test split  

### 4. Model Training
Train one or more regression models (e.g., Linear Regression, Random Forest Regressor) using `scikit-learn`.

### 5. Model Evaluation
Evaluate using:
- **MAE** (Mean Absolute Error)  
- **MSE** (Mean Squared Error)  
- **RMSE** (Root Mean Squared Error)  
- **R² Score**

Use visualizations such as:
- Predicted vs Actual plot
- Residual plot

### 6. Predictions
Use the trained model to predict prices on unseen data.

---

## 🛠️ Requirements

Install required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

