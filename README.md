# Boiler Efficiency Drop

## Overview

This project leverages machine learning techniques to analyze and predict thermal conductance variations. Using a Random Forest model, the system predicts anomalies and visualizes probability distributions for potential fault detection. Key features include predictive analytics, anomaly detection, and advanced visualization.

---

## Table of Contents

1. [Project Features](#project-features)
2. [Data Pipeline](#data-pipeline)
4. [Usage](#usage)
5. [Plots and Visualizations](#plots-and-visualizations)
6. [Project Structure](#project-structure)

---

## Project Features

- **Predictive Analytics**: Utilize a Random Forest model for fault prediction.
- **Visualization**: Generate informative plots for probability distributions and true/false predictions.
- **Anomaly Detection**: Implement anomaly detection in thermal conductance data.
- **Flexibility**: Easily configurable for other types of predictive analyses.

---

## Data Pipeline

- **Data Preprocessing**: The input data undergoes cleaning and normalization.
- **Model Training**: A Random Forest classifier is trained on pre-processed data.
- **Prediction**: Model generates probabilities and triggers alerts based on thresholds.
- **Visualization**: Key metrics are visualized for better interpretability.

---

## Usage

# Predict Anomalies

- Modify the input dataset or preprocessing steps as needed.
- Execute the notebook sequentially.
- Inspect generated plots and prediction results.

# Configurations
- Adjust prediction thresholds in the alert_trigger function.
- Update fault_var and other variables to suit your specific use case.

---

## Plots and Visualizations

- **Probability Distributions**: Visualizes the probability of faults based on thermal conductance.
- **True/False Alerts**: Plots overlay predictions against actual data to evaluate model performance.

---

# Project Structure

📁 BoilerEfficiencyDrop/
├── 📄 Priyanshu_210107066_FINAL.pdf                             # Project Report
├── 📄 Priyanshu_210107066_Project_FINAL (3).ipynb               # Jupyter Notebook file
└── 📄 README.md                                                 # Project documentation
