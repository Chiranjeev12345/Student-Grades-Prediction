# Student Grade Prediction using PySpark

## Overview
This project predicts student final grades using machine learning techniques implemented with **PySpark**.  
The model uses academic indicators such as internal assessment scores and attendance to estimate student performance.

The project demonstrates the complete machine learning workflow:
- Data loading  
- Data preprocessing  
- Feature engineering  
- Model building  
- Evaluation  
- Visualization  

---

## Problem Statement
Traditional methods of evaluating student performance are often reactive and time-consuming.  
This project aims to develop a predictive system that can estimate student grades in advance, helping educators identify students who may need academic support.

---

## Dataset
The project uses the **Student Performance Dataset (student-por.csv)**.

### Key Features Used:
- **G1** – First internal assessment score  
- **G2** – Second internal assessment score  
- **G3** – Final grade (target variable)  
- **Absences** – Number of classes missed  

### Derived Features:
- **Attendance** = 100 - absences  
- **Test Score** = (G1 + G2) / 2  

---

## Technologies Used
- **Python**
- **PySpark**
- **Apache Spark MLlib**
- **Matplotlib**
- **Seaborn**
- **PowerShell**

---

## Project Workflow

```text
Dataset
  ↓
Data Loading
  ↓
Data Cleaning
  ↓
Feature Engineering
  ↓
Feature Vector Creation
  ↓
Train-Test Split
  ↓
Model Training (Linear Regression)
  ↓
Prediction
  ↓
Evaluation (RMSE, R²)
  ↓
Visualization
