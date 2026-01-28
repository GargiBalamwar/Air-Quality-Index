# Air Quality Index (AQI) Prediction using Machine Learning

## Overview
This project focuses on predicting the **Air Quality Index (AQI)** for New Delhi using historical air pollution data.  
The goal is to analyze pollutant concentrations and build a machine learning model that can estimate AQI values accurately, helping in air quality monitoring and environmental analysis.

---

## Problem Statement
Air pollution is a major concern in metropolitan cities like New Delhi.  
Accurate AQI prediction helps:
- Assess pollution levels
- Support early warnings
- Aid government and public health decisions  

Manual monitoring alone is insufficient, making machine learning-based prediction essential.

---

## Dataset
- **Dataset Name:** New Delhi Air Quality Dataset  
- **Source:** Kaggle  
- **File Used:** `NewDelhi_Air_quality.csv`

### Key Features
- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- AQI (Target Variable)

---

## Methodology
1. **Data Loading & Exploration**
   - Loaded dataset using Pandas
   - Checked missing values and data types

2. **Data Preprocessing**
   - Handled missing values
   - Feature selection
   - Normalization (if required)

3. **Model Building**
   - Implemented regression-based machine learning model
   - Split data into training and testing sets

4. **Model Evaluation**
   - Evaluated using accuracy/error metrics
   - Compared predicted AQI with actual AQI values

---

## Tech Stack
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Results
- The model successfully predicts AQI based on pollutant levels
- Demonstrates how air quality trends can be analyzed using ML
- Suitable for academic and beginner-level ML projects

---

## Applications
- Air pollution monitoring
- Environmental data analysis
- Smart city planning
- Public health assessment

---

## Future Enhancements
- Use advanced models (Random Forest, XGBoost)
- Time-series AQI forecasting
- Real-time AQI prediction using live data
- Deployment as a web application

---

## How to Run the Project
1. Clone the repository
2. Open the Jupyter Notebook file
3. Ensure the dataset CSV file is in the same directory
4. Run all cells sequentially

---

## Author
**Gargi Balamwar**  
B.Tech CSE Student  
