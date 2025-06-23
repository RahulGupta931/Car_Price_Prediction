# Car Price Prediction 🚗💰

This project uses machine learning techniques to predict car prices based on various features such as company name, year of manufacture, fuel type, and more. It aims to help users estimate the value of their vehicles or make informed decisions when purchasing a car.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Modeling](#modeling)
- [Results](#results)
- [How to Run](#how-to-run)

---

## Project Overview
Car price prediction is a crucial task in the automotive industry, benefiting both buyers and sellers. This project focuses on building a regression model to predict car prices based on various features.

## Features
- Predict car prices with high accuracy.
- Preprocess and analyze data to identify key trends.
- Deploy the model using Flask.

## Dataset
The dataset includes:
- **Columns**: name, company,	year,	Price,	kms_driven,	fuel_type

## Technologies Used
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, pickle
- **Frameworks**: Flask
- **Tools**: Jupyter Notebook, Google Colab

## Modeling
1. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.
2. **Model Selection**:
   - Compare algorithms (Linear Regression, Random Forest, Gradient Boosting, etc.).
   - Perform hyperparameter tuning.
3. **Evaluation**:
   - Metrics: R² Score.

## Results
- Achieved **90% accuracy** on test data.
- Model shows robust performance for unseen data.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Car-Price-Prediction.git
