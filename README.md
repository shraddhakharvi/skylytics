# ✈️ Aviation KPIs Analysis & Prediction

## 📌 Project Overview
This project focuses on analyzing aviation Key Performance Indicators (KPIs) and predicting their values using **Machine Learning models**. 
The primary goal is to derive **actionable insights** that help in improving aviation operations and decision-making.

## 📂 Dataset Information
- **Dataset Name:** `Aviation_KPIs_dataset.csv`
- **Total Rows & Columns:** *Total 200000 rows and 18 columns*
- **Features:**  
  - **Independent Variables:** *Flight Performance Metrics: On-time departures, delays, cancellations.
Operational Factors: Aircraft type, fuel consumption, crew efficiency.
Weather Conditions: Temperature, wind speed, visibility.
Passenger & Traffic Data: Load factor, passenger count, ticket sales.*
  - **Target Variable:** *The variable we aim to predict based on independent features.
In this project, it could be flight delays, on-time performance, or passenger satisfaction scores.
It is influenced by factors like weather, operational efficiency, and passenger traffic.
The model evaluates how well these factors impact the target for better decision-making.*

## 🔍 Exploratory Data Analysis (EDA)
Key steps performed during **EDA**:
- **Checked for missing values** and handled them appropriately.
- **Analyzed data distribution** using correlation matrics and boxplots.
- **Converted categorical data** using label encoding.
- **Standardized numerical features** for better model performance.

## 🚀 Machine Learning Models Used
1️⃣ **Linear Regression** – Provides a simple, interpretable model for KPI prediction.  
2️⃣ **Random Forest Regressor** – Handles non-linearity and improves accuracy.  

### **Model Evaluation Metrics**
| Model                 | MAE (Lower is better) | MSE (Lower is better) | R² Score (Higher is better) |
|----------------------|----------------|----------------|----------------|
| **Linear Regression** | 3.62e-11 | 2.03e-21 | 1.00 (Overfitting) |
| **Random Forest** | 41.34 | 2876.70 | 0.9999 (Good fit) |

✅ **Best Model:** **Random Forest Regressor** (Better generalization and accuracy).  

## 📊 Visualization of Predictions
- **Scatter Plot:** Shows actual vs. predicted values.
- **Feature Importance Chart:** Highlights the most influential features.
- **Error Distribution Graph:** Helps in understanding model errors.

## 🛠️ Challenges Faced
- Handling missing values and categorical data.
- Overfitting issue with Linear Regression.
- Ensuring the dataset had well-balanced features.

## 🔮 Future Improvements
- Implement advanced models like **XGBoost** or **Deep Learning**.
- Collect additional data for better generalization.
- Optimize hyperparameters for improved performance.

## 📌 How to Run This Project
1️⃣ Clone this repository:
```bash
git clone https://github.com/yourusername/aviation-kpi-analysis.git
