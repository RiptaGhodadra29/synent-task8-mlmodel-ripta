# synent-task8-mlmodel-ripta
House Price Prediction using Machine Learning (Linear Regression &amp; Random Forest)
# 🏠 House Price Prediction using Machine Learning

## 🚀 Internship Task
This project is part of the Synent Technologies Data Science Internship Program.

---

## 📌 Problem Statement
The objective of this project is to build a machine learning model that can predict house prices based on various features such as area, number of bedrooms, and other amenities.

---

## 📊 Dataset
House Price Dataset

### Features:
- price → Target variable (house price)
- area → Area of the house
- bedrooms → Number of bedrooms
- bathrooms → Number of bathrooms
- stories → Number of floors
- mainroad → Access to main road (yes/no)
- guestroom → Availability of guest room (yes/no)
- basement → Availability of basement (yes/no)
- hotwaterheating → Hot water facility (yes/no)
- airconditioning → AC availability (yes/no)
- parking → Parking spaces
- prefarea → Preferred area (yes/no)
- furnishingstatus → Furnishing status (furnished/semi/unfurnished)

---

## ⚙️ Approach

### 1. Data Preprocessing
- Converted categorical variables into numerical format
- Mapped binary values (yes/no → 1/0)
- Applied one-hot encoding on furnishing status

---

### 2. Feature Selection
- Selected all relevant features except target variable
- Defined:
  - X → input features
  - y → target variable (price)

---

### 3. Train-Test Split
- Split dataset into:
  - 80% training data
  - 20% testing data

---

### 4. Model Training

#### ✅ Linear Regression
- Used to predict continuous values
- Captures linear relationships between features and price

#### ✅ Random Forest Regressor
- Ensemble learning method
- Used for comparison with Linear Regression

---

### 5. Model Evaluation

- Used RMSE (Root Mean Squared Error)

#### Results:
- Linear Regression RMSE ≈ 1.32M
- Random Forest RMSE ≈ 1.36M

---

## 📈 Insights
- Linear Regression performed better than Random Forest
- Dataset shows mostly linear relationships
- Area, number of bedrooms, and bathrooms significantly influence house price
- Model predictions are reasonably accurate with moderate error

---

## 🧠 Conclusion
The project demonstrates how machine learning can be used to predict house prices. Simpler models like Linear Regression can outperform complex models when the dataset has linear patterns.

---

## 🎥 Demo Video
(Add your video link here)

---

## 🔗 GitHub Repository
https://github.com/RiptaGhodadra29/synent-task8-mlmodel-ripta.git
