# Housing Price Prediction using Linear Regression

This project implements a **Linear Regression** model to predict house prices based on various property features.  
It demonstrates a complete machine learning workflow including data preprocessing, model training, prediction, and evaluation.

---

## 📌 Project Objective

To build a supervised machine learning model that accurately predicts **housing prices** using **Linear Regression** and historical housing data.

---

## 📊 Dataset

- **Source:** Kaggle  
- **Type:** Housing price dataset  
- **Target Variable:** House price (SalePrice / Price)

Each row in the dataset represents a house with multiple numerical and categorical features describing its characteristics.

---

## 🔍 Features Used

Typical features include:
- Area of the house  
- Number of bedrooms and bathrooms  
- Year built  
- Location / neighborhood  
- Overall quality  
- Garage and basement details  

*(Exact features depend on the dataset used in the notebook.)*

---

## 🧪 Project Workflow

1. **Data Loading**
   - Load dataset using Pandas

2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Feature selection
   - Train–test split

3. **Model Building**
   - Apply **Linear Regression** using Scikit-Learn

4. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

5. **Prediction**
   - Predict house prices for test data

---

## 🛠️ Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-Learn  
- Jupyter / Kaggle Notebook  

---

## 🚀 How to Run

```python
import pandas as pd

df = pd.read_csv("housing.csv")
df.head()
