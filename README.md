# Multi-Project Machine Learning Portfolio 🤖💼

Welcome to my Machine Learning repository! This repository contains two independent practical projects applying **Linear Regression** to solve real-world prediction problems. 

The projects demonstrate the complete end-to-end Data Science pipeline: from data cleaning and feature selection to model training and performance evaluation.

---

## 📌 Project 1: Airline Flight Delay Prediction ✈️
* **Dataset:** Airline Delay Cause (`Airline_Delay_Cause.csv`)
* **Objective:** Predict the number of delayed aircrafts (`late_aircraft_ct`) based on multiple flight features.
* **Key Highlights:**
  * Handled large-scale data (over 310,000 rows).
  * Performed feature selection by dropping irrelevant textual columns to avoid overfitting.
  * Split data into 75% Training and 25% Testing with a fixed `random_state=44`.
* **Results:** Achieved an incredibly low **Mean Squared Error (MSE = 3.58e-05)**, showing high precision on smaller-scale target units.

---

## 📌 Project 2: House Price Prediction 🏠
* **Dataset:** House Price Regression Dataset (`house_price_regression_dataset.csv`)
* **Objective:** Predict the real estate market prices (`House_Price`) based on house specifications (Square Footage, Bedrooms, Bathrooms, Neighborhood Quality, etc.).
* **Key Highlights:**
  * Processed features containing large numeric values.
  * Split data into 80% Training and 20% Testing.
* **Results:** * Although the MSE was high (108 Million) due to the nature of squaring large currency units, the model's true performance was validated using the **R² Score**.
  * Achieved an outstanding **R² Score of 0.998 (99.8% Accuracy)**, proving the model perfectly captured the data variance!

---

## 🛠️ Technologies & Libraries Used
* **Language:** Python 🐍
* **Environment:** Jupyter Notebook / Anaconda 📓
* **Libraries:** * `Pandas` (Data manipulation & exploration)
  * `Scikit-Learn` (Model training, train_test_split, LinearRegression, Evaluation Metrics)
  * `Numpy` (Numerical operations)

---

## 🚀 How to Run the Projects
1. Clone this repository:
   ```bash
   git clone (https://github.com/adel-mahmoud-elazawy/ML-Regression-Projects.git)
