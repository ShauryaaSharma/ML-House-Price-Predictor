# ML-House-Price-Predictor

## 📌 Project Overview

This project aims to predict the market value of houses in Boston based on economic, geographical, and structural factors. <br>
I explored Linear Regression, Decision Trees, and Random Forest models, using Cross-Validation for evaluation. The Random Forest model delivered the best results.<br>

## 🛠 Technologies Used

🔹 Python 🐍 <br>
🔹 Scikit-Learn – ML model training & evaluation<br>
🔹 Pandas – Data manipulation & preprocessing<br>
🔹 NumPy – Numerical computations<br>
🔹 Matplotlib – Data visualization<br>
🔹 SciPy – Statistical analysis<br>

## 📊 Dataset

The dataset used is the Boston Housing Dataset from Scikit-Learn, containing the following key features:<br>
🏙  X1 transaction date<br>
🏡 X2 house age<br>
🎓 X3 distance to the nearest MRT station<br>
💰 X4 number of convenience stores<br>
📉 X5 latitude<br>
📍 X6 longitude<br>
🌿 CHAS – Proximity to the Charles River (0 = No, 1 = Yes)<br>
💲 Y house price of unit area<br>

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing & EDA<br>
✔ Handled missing values using imputation techniques 📉<br>
✔ Performed Train-Test Splitting (80% train, 20% test) 🏋‍♂<br>
✔ Created Attribute Combinations (e.g., Rooms per Household) for better predictions 🔄<br>
✔ Used Matplotlib for Exploratory Data Analysis (EDA) 📊<br>

### 2️⃣ Feature Engineering<br>
✔ Identified key features using correlation heatmaps<br>
✔ Normalized/standardized data where needed<br>

### 3️⃣ Model Training & Evaluation<br>
✔ Explored Linear Regression, Decision Trees, and Random Forest<br>
✔ Used Cross-Validation for performance evaluation<br>
✔ Random Forest performed best 🏆<br>

### 4️⃣ Model Evaluation<br>
📌 Metrics Used:<br>

🔸 Mean Absolute Error (MAE)<br>
🔸 Root Mean Squared Error (RMSE)<br>
🔸 R² Score<br>

## ✅ Results & Key Takeaways

✅ Random Forest outperformed other models with the best accuracy.<br>
✅ Handling missing values & attribute engineering improved model performance.<br>
✅ Cross-Validation ensured robust performance evaluation.<br>
✅ Learned how EDA, feature engineering, and model tuning improve predictions.<br>
