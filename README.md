# 💻 Laptop Price Predictor

A **web-based application** that predicts the price of a laptop based on configuration details provided by the user.

This project follows a full machine learning pipeline — from data collection and preprocessing to model training, evaluation, and deployment — designed to generate real-world business value.

---

## 🧠 Business Problem

**Objective**: Predict the price of a laptop based on its specifications.

Laptop prices vary widely based on components such as processor type, storage, RAM, and GPU. This tool helps users estimate a fair price and assists sellers in setting competitive pricing.

---

## 📦 Dataset

- **Records**: 1300 laptop models  
- **Features**:
  - Company Name  
  - Product Name  
  - Laptop Type  
  - Screen Inches  
  - Screen Resolution  
  - CPU Model  
  - RAM  
  - Storage (HDD/SSD)  
  - GPU  
  - Operating System  
  - Weight  
  - Price (target)

---

## 🧪 ML Problem Type

- **Type**: Regression  
- **Goal**: Predict a continuous value (Laptop Price)

---

## 🎯 Performance Metrics

- R² Score  
- Mean Absolute Error (MAE)

---

## 🔁 Machine Learning Workflow

1. **Data Cleaning**  
2. **Feature Engineering**  
3. **Exploratory Data Analysis (EDA)**  
4. **Model Selection**  
5. **Hyperparameter Tuning**  
6. **Model Evaluation**  
7. **Web App Deployment (Streamlit)**

---

## 📊 Model Results

- **Best Model**: Random Forest Regressor *(or replace with your final model)*  
- **R² Score**: `0.87` *(example)*  
- **MAE**: `₹3,500` *(example)*

---

## 🖼️ Application UI

### 🔧 Input Form

<img width="407" alt="form" src="https://user-images.githubusercontent.com/63099028/183035027-a8e3e365-7d37-4ed1-93d3-02ecd44ff668.PNG">

### 🛒 Amazon Price Example

<img width="597" alt="amazon" src="https://user-images.githubusercontent.com/63099028/180611808-28a90158-4f95-4199-b767-f53e584b7366.PNG">

### 📈 Predicted Price Output

<img width="938" alt="predicted" src="https://user-images.githubusercontent.com/63099028/180611810-97d7b279-f1b0-4f62-9469-4f01b931e1f6.PNG">
