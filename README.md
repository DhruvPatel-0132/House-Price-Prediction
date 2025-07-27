# 🏠 House Price Prediction using Machine Learning

A complete machine learning pipeline that predicts house prices based on property features. This project includes data cleaning, EDA, model building, evaluation, and a prediction interface using user input.

---

## 📂 Project Files

- `House-Price-Prediction.ipynb` — Main Jupyter Notebook with the full pipeline
- `Housing.csv` — Raw housing dataset
- `README.md` — Project documentation

---

## 📊 Dataset Overview

The dataset contains information about residential properties including:

| Feature           | Description                      |
|------------------|----------------------------------|
| `area`           | Area of the house (in sq. ft.)   |
| `bedrooms`       | Number of bedrooms               |
| `bathrooms`      | Number of bathrooms              |
| `stories`        | Number of stories                |
| `parking`        | Car parking capacity             |
| `furnishingstatus` | Furnished / Semi / Unfurnished |
| `mainroad`, `guestroom`, `basement`, `hotwaterheating`, etc. | Categorical features indicating amenities |

---

## 🔁 Workflow Summary

1. **Load & Clean Data**  
   - Handle missing values  
   - Encode categorical variables  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize distributions  
   - Correlation analysis using heatmaps and pairplots  

3. **Train Models**
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  

4. **Evaluate Models**  
   Using metrics:
   - R² Score
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)

5. **Select Best Model**  
   Random Forest chosen based on best accuracy and error performance

6. **User Input Prediction**  
   User can enter custom values and get price prediction from the trained model

---

## 🧠 Model Comparison

| Model               | R² Score | MAE (₹)     | RMSE (₹)     |
|---------------------|----------|-------------|--------------|
| Linear Regression   | 0.65     | 9,70,043     | 13,24,506    |
| Decision Tree       | 0.48     | 11,93,981    | 16,24,840    |
| **Random Forest** ✅| **0.75** | **8,30,000** | **10,10,000**|

---

## 🛠️ Tech Stack

- Python 3.8+
- Jupyter Notebook
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn

---

## 🚀 How to Run the Project

### 1. Clone this repository
```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
