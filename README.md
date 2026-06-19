🏡 House Price Prediction - Machine Learning
Author: Sadi Daveed (@daveedreddy)
Role: AI & Data Science Intern at XYlofyAI

📌 Project Overview
This repository contains the complete Week 1 project for my Data Science Internship at XYlofyAI. The objective of this project is to eliminate guesswork in real estate evaluations by building a machine learning model capable of accurately predicting house prices based on various property features and amenities.

📊 Dataset & Features
The model is trained on a comprehensive real estate dataset containing various features such as:

Total Area (Square Feet)

Number of Bedrooms & Bathrooms

Number of Stories

Amenities (Air Conditioning, Guestroom, Basement, Parking, etc.)

Furnishing Status

🛠️ Data Processing & Methodology
Data Cleaning: Checked for null values and duplicates to ensure data integrity.

Exploratory Data Analysis (EDA): Created distribution histograms, scatter plots, and boxplots to visualize how different categorical features impact house prices.

Feature Engineering: Converted categorical text data ('yes'/'no', 'furnished') into numerical format using One-Hot Encoding (pd.get_dummies).

Train-Test Split: Divided the dataset into 80% training data and 20% testing data.

🤖 Machine Learning Models
To determine the best predictive approach, two different regression algorithms were trained and evaluated:

Linear Regression

Random Forest Regressor

Performance Metrics:
Both models achieved an R² score of ~65% and a Mean Absolute Error (MAE) of ~9.5 Lakhs, indicating moderate but consistent predictive accuracy.

💡 Key Insights
Through the Correlation Heatmap and feature analysis, the data revealed that:

Area, Bathrooms, and Air Conditioning have the highest positive correlation with the final property price.

Surprisingly, features often considered premium, like basements and guestrooms, showed a relatively weak correlation with the price.

Recommendation: Real estate marketing campaigns should heavily highlight properties with multiple bathrooms and AC, as buyers pay a substantial premium for these amenities.

💻 Technologies Used
Language: Python

Data Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn
