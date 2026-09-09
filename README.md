# 🏠 NYC Airbnb Room Type Prediction

An end-to-end Machine Learning project that predicts the room type of an Airbnb listing based on its listing features.

The project includes data preprocessing, exploratory data analysis, machine learning model training, REST API development using FastAPI, and deployment of the frontend and backend.

## 🚀 Live Demo

👉 [Open Live Application](https://nyc-airbnb-room-type-prediction-4.onrender.com)

## 🔗 Backend API

👉 [FastAPI Backend](https://nyc-airbnb-room-type-predictor.onrender.com)

## 📌 Project Overview

The goal of this project is to predict the **room type** of an Airbnb listing using features such as:

- Neighbourhood
- Room type related features
- Price
- Number of reviews
- Availability
- Minimum nights
- Reviews per month
- Other listing-related features

The project follows a complete Machine Learning workflow:

**Data → EDA → Preprocessing → Feature Engineering → Model Training → Evaluation → API → Deployment**

## 🛠️ Tech Stack

### Machine Learning
- Python
- NumPy
- Pandas
- Scikit-learn

### Backend
- FastAPI
- Uvicorn
- REST API

### Frontend
- HTML
- CSS
- JavaScript

### Deployment
- Render

## ✨ Features

- 🏠 Airbnb room type prediction
- 📊 Exploratory Data Analysis
- 🔄 Data preprocessing
- ⚙️ Feature engineering
- 🤖 Machine Learning classification models
- 🔌 REST API using FastAPI
- 🌐 Interactive web interface
- 🚀 Deployed frontend and backend

## 🤖 Machine Learning Workflow

### 1. Data Collection

The project uses the **NYC Airbnb 2019 dataset** containing information about Airbnb listings in New York City.

### 2. Exploratory Data Analysis

Performed EDA to understand:

- Missing values
- Numerical feature distributions
- Categorical features
- Outliers
- Feature relationships
- Target variable distribution

### 3. Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Encoding categorical variables
- Feature transformation
- Numerical feature preprocessing

`ColumnTransformer` and `Pipeline` from Scikit-learn were used to keep preprocessing and model prediction consistent.

### 4. Model Training

Different classification algorithms were evaluated, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

### 5. Model Evaluation

Models were evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Cross-validation and hyperparameter tuning were also used to improve model performance.

## 📁 Project Structure

```text
NYC-Airbnb-Room-Type-Prediction/
│
├── app.py
├── requirements.txt
├── README.md
│
├── model/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── notebooks/
│   └── model_training.ipynb
│
└── data/
    └── AB_NYC_2019.csv
