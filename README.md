# 4th-SEM-AI-ML
# Predictive Maintenance using XGBoost

## Project Overview
This project implements a Predictive Maintenance system using Machine Learning with the XGBoost algorithm. The model predicts whether a machine is likely to fail based on operational parameters such as temperature, rotational speed, torque, and tool wear.

The objective is to identify possible machine failures in advance so maintenance can be performed before breakdown occurs.

---

## Features

- Data preprocessing and cleaning
- Conversion of categorical variables into numeric values
- Train-test data splitting
- Machine learning model using XGBoost
- Model performance evaluation
- Save trained model using Joblib

---

## Dataset Information

The dataset contains machine operational parameters.

Example features:

- Type
- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear

Target variable:

- Target
    - `0` = No machine failure
    - `1` = Machine failure

Removed columns:

- UDI
- Product ID
- Failure Type

---

## Technologies Used

- Python
- Pandas
- NumPy
- XGBoost
- Scikit-learn
- Joblib

---

## Installation

Install required libraries:

```bash
pip install pandas numpy scikit-learn xgboost joblib
Predictive-Maintenance/
│
├── predictive_maintenance.csv
├── predictive_maintenance.py
├── xgboost_predictive_maintenance.pkl
├── README.md
git clone <repository-link>
cd Predictive-Maintenance
python predictive_maintenance.py
