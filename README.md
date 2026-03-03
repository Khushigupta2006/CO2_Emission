# 🌍 CO₂ Emissions Prediction using Linear Regression

## 📌 Project Overview

This project aims to predict **CO₂ emissions (g/km)** of vehicles using **Linear Regression** based on important features such as:

- Engine Size (L)
- Fuel Consumption Combined (L/100 km)

The objective is to analyze how engine size and fuel consumption impact carbon emissions and build a predictive machine learning model.

---

## 🎯 Problem Statement

To develop a regression model that predicts vehicle CO₂ emissions based on engine size and fuel consumption, and evaluate its performance using statistical metrics.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Exploration
- Loaded dataset using Pandas
- Checked dataset structure using `.info()` and `.describe()`
- Visualized feature relationships using Correlation Heatmap

---

### 2️⃣ Data Preparation
- Selected important numerical features:
  - Engine Size (L)
  - Fuel Consumption Comb (L/100 km)
- Defined target variable:
  - CO2 Emissions (g/km)
- Split dataset into training and testing sets (80:20 ratio)

---

### 3️⃣ Model Building
- Applied **Linear Regression**
- Trained the model using training data
- Generated predictions on test data

---

### 4️⃣ Model Evaluation

The model was evaluated using:

- **Mean Absolute Error (MAE)** – Measures average absolute prediction error  
- **Mean Squared Error (MSE)** – Measures average squared prediction error  
- **R² Score** – Measures how well the model explains variance  

---

## 📊 Visualizations

- Correlation Heatmap
- Actual vs Predicted CO₂ Emissions Scatter Plot

The scatter plot helps compare actual emissions with predicted values.  
If points are close to the diagonal line, the model performance is good.

---

## 📈 Results

- Engine size and fuel consumption show strong positive correlation with CO₂ emissions.
- The model achieved a reasonable R² score, indicating good predictive performance.
- The scatter plot shows predictions closely aligned with actual emission values.

