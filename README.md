# ML-House-Price-Predictor

## 📌 Project Overview

This project aims to predict the market value of houses in Boston based on economic, geographical, and structural factors. 
I explored Linear Regression, Decision Trees, and Random Forest models, using Cross-Validation for evaluation. The Random Forest model delivered the best results.

## 🛠 Technologies Used

🔹 Python 🐍
🔹 Scikit-Learn – ML model training & evaluation
🔹 Pandas – Data manipulation & preprocessing
🔹 NumPy – Numerical computations
🔹 Matplotlib – Data visualization
🔹 SciPy – Statistical analysis

## 📊 Dataset

The dataset used is the Boston Housing Dataset from Scikit-Learn, containing the following key features:
🏙  X1 transaction date
🏡 X2 house age
🎓 X3 distance to the nearest MRT station
💰 X4 number of convenience stores
📉 X5 latitude
📍 X6 longitude
🌿 CHAS – Proximity to the Charles River (0 = No, 1 = Yes)
💲 Y house price of unit area

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing & EDA
✔ Handled missing values using imputation techniques 📉
✔ Performed Train-Test Splitting (80% train, 20% test) 🏋‍♂
✔ Created Attribute Combinations (e.g., Rooms per Household) for better predictions 🔄
✔ Used Matplotlib for Exploratory Data Analysis (EDA) 📊

### 2️⃣ Feature Engineering
✔ Identified key features using correlation heatmaps
✔ Normalized/standardized data where needed

### 3️⃣ Model Training & Evaluation
✔ Explored Linear Regression, Decision Trees, and Random Forest
✔ Used Cross-Validation for performance evaluation
✔ Random Forest performed best 🏆

### 4️⃣ Model Evaluation
📌 Metrics Used:

🔸 Mean Absolute Error (MAE)
🔸 Root Mean Squared Error (RMSE)
🔸 R² Score

## ✅ Results & Key Takeaways

✅ Random Forest outperformed other models with the best accuracy
✅ Handling missing values & attribute engineering improved model performance
✅ Cross-Validation ensured robust performance evaluation
✅ Learned how EDA, feature engineering, and model tuning improve predictions
