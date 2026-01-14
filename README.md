# Used Car Price Prediction

This project focuses on predicting the prices of used cars using machine learning techniques.  
The dataset contains real-world, unstructured data that required significant cleaning and feature engineering before model training.

---

## 📌 Problem Statement
Predict the selling price of a used car based on features such as brand, mileage, engine specifications, fuel type, transmission, and vehicle age.

---

## 📊 Dataset Overview
The dataset includes both numerical and categorical features, with several columns containing noisy and text-based values (e.g., mileage, engine details, accident history).

Target variable:
- `price` (continuous)

---

## 🛠️ Data Preprocessing & Feature Engineering
Key steps performed:
- Cleaned and converted mileage and engine information from text to numerical values
- Created `car_age` from model year
- Handled missing values using appropriate imputation strategies
- Removed high-cardinality and noisy features
- Encoded categorical variables using OneHotEncoding
- Applied log transformation to the target variable to handle right-skewness

---

## 🤖 Models Used
- Linear Regression
- Random Forest Regressor

Both models were trained using a preprocessing + modeling pipeline built with scikit-learn.

---

## 📈 Model Evaluation
Models were evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

Random Forest performed better due to its ability to capture non-linear relationships in the data.

---

## 🧠 Key Learnings
- Feature engineering plays a crucial role in model performance
- Real-world datasets require careful handling of text-based and noisy features
- Log transformation of skewed targets can significantly improve regression results
- Pipelines help maintain clean and reproducible workflows

---

## 🧰 Tech Stack
- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib

---


---

## ✅ Conclusion
This project demonstrates an end-to-end machine learning workflow, from raw data preprocessing to model evaluation, using a realistic dataset.

