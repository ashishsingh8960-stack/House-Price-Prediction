🏠 House Price Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting house prices based on property features such as area, number of rooms, location, and age of the house.
It demonstrates how regression techniques can be used to solve real-world pricing problems in the real estate domain.

🎯 Objectives

Analyze house property data

Perform data preprocessing and feature engineering

Encode categorical variables

Build a regression model to predict house prices

Evaluate model performance using error metrics

Predict prices for new houses

🧰 Tools & Technologies

Python

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Visualization

Scikit-learn – Machine Learning

📂 Project Structure
house-price-prediction/
│
├── data/
│   └── house_data.csv
│
├── notebook/
│   └── house_price_prediction.ipynb
│
├── README.md
└── requirements.txt

📑 Dataset Description

The dataset contains information about houses with the following columns:

Column	Description
Area	House size (sq. ft.)
Bedrooms	Number of bedrooms
Bathrooms	Number of bathrooms
Location	City or Suburb
Age	Age of the house (years)
Price	House price (Target variable)
🔍 Data Preprocessing

Checked data types and missing values

Converted categorical column Location into numeric using one-hot encoding

Selected relevant features for modeling

📊 Exploratory Data Analysis (EDA)

Analyzed correlation between numeric features and price

Visualized feature relationships using correlation heatmaps

🤖 Machine Learning Model

Algorithm Used: Linear Regression

Type: Supervised Regression

Input Features: Area, Bedrooms, Bathrooms, Age, Location

Target Variable: Price

📐 Model Evaluation

The model was evaluated using:

MAE (Mean Absolute Error) – Average prediction error

RMSE (Root Mean Squared Error) – Penalizes larger errors

🔮 Future House Price Prediction

The trained model is capable of predicting house prices for new properties by providing required house features.

🧠 Key Insights

Area and number of rooms strongly influence house prices

Location plays a significant role in determining price

Newer houses generally have higher prices

🏁 Conclusion

This project demonstrates how regression models can be used for real estate price estimation.
It strengthened my understanding of feature engineering, regression modeling, and evaluation metrics.

🚀 How to Run the Project

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn


Open house_price_prediction.ipynb

Run all cells

📌 Author

Ashish Singh

⭐ If you find this project useful, feel free to star the repository!
