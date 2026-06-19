# 🏡 House Price Prediction - Machine Learning

**Author:** Sadi Daveed (@daveedreddy)  
**Role:** AI & Data Science Intern at XYlofyAI

---

## 📌 Project Overview

This repository contains the complete **Week 1 Project** for my Data Science Internship at **XYlofyAI**.

The objective of this project is to eliminate guesswork in real estate evaluations by building a machine learning model capable of accurately predicting house prices based on various property features and amenities.

---

## 📊 Dataset & Features

The model is trained on a comprehensive real estate dataset containing features such as:

- Total Area (Square Feet)
- Number of Bedrooms
- Number of Bathrooms
- Number of Stories
- Air Conditioning Availability
- Guestroom Availability
- Basement Availability
- Parking Capacity
- Furnishing Status
- Other Property Amenities

---

## 🛠️ Data Processing & Methodology

### 1. Data Cleaning
- Checked for missing values (null values)
- Removed duplicate records
- Ensured overall data quality and consistency

### 2. Exploratory Data Analysis (EDA)
- Distribution Histograms
- Scatter Plots
- Box Plots
- Correlation Heatmap

These visualizations helped identify relationships between property features and house prices.

### 3. Feature Engineering
- Converted categorical features into numerical format
- Applied **One-Hot Encoding** using `pd.get_dummies()`
- Prepared the dataset for machine learning algorithms

### 4. Train-Test Split
- Training Data: **80%**
- Testing Data: **20%**

---

## 🤖 Machine Learning Models

To determine the most effective predictive approach, two regression models were trained and evaluated:

### Linear Regression
A baseline regression model used to establish initial prediction performance.

### Random Forest Regressor
An ensemble learning model capable of capturing complex relationships within the data.

---

## 📈 Model Performance

| Metric | Linear Regression | Random Forest Regressor |
|----------|------------------|------------------------|
| R² Score | ~65% | ~65% |
| MAE | ~9.5 Lakhs | ~9.5 Lakhs |

### Performance Summary
Both models achieved:

- **R² Score:** Approximately 65%
- **Mean Absolute Error (MAE):** Approximately ₹9.5 Lakhs

These results indicate moderate but consistent predictive accuracy.

---

## 💡 Key Insights

The correlation analysis and feature importance study revealed:

✅ **Area** has a strong positive impact on house prices.

✅ **Number of Bathrooms** significantly influences property value.

✅ **Air Conditioning** contributes positively to higher selling prices.

⚠️ Features such as:

- Basement
- Guestroom

showed relatively weaker correlations with price compared to other major features.

### Business Recommendation

Real estate marketing campaigns should emphasize:

- Larger property area
- Multiple bathrooms
- Air conditioning facilities

These features command a noticeable premium in the housing market and can significantly influence buyer decisions.

---

## 💻 Technologies Used

### Programming Language
- Python

### Data Manipulation
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-Learn

---

## 🚀 Project Outcome

This project demonstrates how machine learning can be applied to real-world real estate problems by transforming raw housing data into meaningful price predictions. The developed models provide valuable insights for buyers, sellers, and real estate professionals, helping them make more informed decisions.

---

### ⭐ If you found this project useful, consider giving it a star on GitHub!
