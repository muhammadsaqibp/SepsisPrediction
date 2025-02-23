# Sepsis Early Warning Prediction System

A deep learning and machine learning-based system for the early detection of sepsis in critical care patients using clinical data.

---

## Overview

**Sepsis Early Warning Prediction System** is designed to analyze patient data and predict the early onset of sepsis. This project leverages the Medical Information Mart for Intensive Care IV (MIMIC-IV) database, a comprehensive critical care database developed by the **Massachusetts Institute of Technology (MIT)** and Beth Israel Deaconess Medical Center. The **MIMIC-IV database** is available through PhysioNet, a platform for sharing medical research data.

The model utilizes advanced data preprocessing, feature engineering, and predictive modeling techniques to analyze patient data and identify early signs of sepsis. Key performance metrics, including accuracy, ROC-AUC, precision, recall, and F1-score, have been used to evaluate the model's effectiveness.

Developed as a capstone project for my **Data Science & AI Certification**, this work was recognized with a *Distinguished Performer* award. The project includes comprehensive documentation and a user-friendly interface built with Streamlit, facilitating easy interaction and deployment of the model.

---

## Data Source

The model utilizes data from the **MIMIC-IV** database. Access to the MIMIC-IV database requires credentialed access due to patient privacy considerations. Researchers can apply for access through the PhysioNet website.

---

## Features

- **Data Preprocessing & Feature Engineering:**  
  - Handling missing values, outlier detection, and scaling.
- **Predictive Modeling:**  
  - Implementation of both deep learning and traditional machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
- **Evaluation Metrics:**  
  - Accuracy, ROC-AUC, Precision, Recall, F1-Score.
- **User Interface:**  
  - Integration with a Streamlit app for real-time prediction and visualization.

---

## Project Structure

```plaintext
Sepsis Early Warning Prediction System/
├── data/                # Sample data or instructions to download the full dataset (MIMIC-IV)
├── models/              # Saved model files and checkpoints
├── notebooks/           # Jupyter Notebooks for exploratory data analysis and modeling
├── src/                 # Source code scripts
│   ├── preprocessing.py  # Data cleaning and feature engineering
│   ├── modeling.py       # Model training and evaluation scripts
│   └── evaluation.py     # Analysis of model performance and metrics
├── app.py               # Streamlit application for real-time prediction
├── README.md            # This documentation file
├── requirements.txt     # Python dependencies
└── LICENSE              # MIT License
