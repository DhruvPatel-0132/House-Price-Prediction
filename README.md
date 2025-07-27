🏠 House Price Prediction using Machine Learning
This project focuses on building a predictive model to estimate house prices using various machine learning algorithms. The dataset includes several housing features such as location, size, number of bedrooms, etc. The goal is to select the best-performing model and allow users to input house details to get a predicted price.

📁 Project Structure
bash
Copy
Edit
├── House-Price-Prediction.ipynb  # Main notebook with EDA, model training & prediction
├── Housing.csv                   # Dataset used for model training
└── README.md                     # Project documentation
📊 Dataset
File: Housing.csv

Size: ~500 entries

Features:

Area

Bedrooms

Bathrooms

Stories

Parking

Furnishing Status

Main Road / Guest Room / Basement, etc.

Price (Target)

🔍 Workflow
Data Loading

Data Cleaning & Preprocessing

Handling missing values

Label encoding categorical features

Exploratory Data Analysis (EDA)

Visualizations using Seaborn & Matplotlib

Correlation analysis

Model Training

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Model Evaluation

R² Score

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

Model Selection

Choose the model with best performance metrics

User Prediction Interface

Input features from the user

Output predicted house price

🧠 Best Model
After comparing models:

Model	R² Score	MAE	RMSE
Linear Regression	0.65	₹9.7L	₹13.2L
Decision Tree	0.48	₹11.9L	₹16.2L
Random Forest	0.75	₹8.3L	₹10.1L

✅ Final Model Used: Random Forest Regressor

📌 How to Use
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
Open the Jupyter Notebook

bash
Copy
Edit
jupyter notebook House-Price-Prediction.ipynb
Run all cells or modify the "User Input" cell to predict price for your custom inputs.

🔧 Requirements
Python 3.8+

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

Install all dependencies with:

bash
Copy
Edit
pip install -r requirements.txt
You can generate a requirements.txt file using:

bash
Copy
Edit
pip freeze > requirements.txt
✍️ Author
Dhruv Patel

GitHub: @DhruvPatel-0132

📜 License
This project is licensed under the MIT License. Feel free to use and modify as per your need.
