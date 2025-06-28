# 🏡 House Price Prediction Using Supervised Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Regression-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📖 Overview

This project presents an end-to-end supervised machine learning solution to predict house prices based on multiple real-estate features such as living area, garage size, number of bedrooms, year built, and more. Using regression algorithms, the model helps forecast house prices and provides insights into which features impact property value the most.

---

## 🎯 Objectives

- 🔍 Understand and explore the dataset through EDA
- 🧹 Clean and preprocess the data including encoding categorical values
- 🧠 Build regression models using Linear Regression and Random Forest
- 📊 Evaluate model performance using RMSE, MAE, and R² score
- 📈 Visualize model predictions and feature correlations
- 📁 Organize the project with a professional folder structure

---

## 🧰 Tech Stack Used

| Category       | Tools / Libraries                          |
|----------------|---------------------------------------------|
| Language       | Python 3.8+                                 |
| Data Handling  | Pandas, NumPy                               |
| Visualization  | Matplotlib, Seaborn                         |
| ML Algorithms  | Scikit-learn (LinearRegression, RandomForestRegressor) |
| Encoding       | LabelEncoder                                |
| Evaluation     | R², MAE, RMSE                               |
| Notebook       | Jupyter Notebook                            |

---

## 📊 Dataset Details

- **Source**: [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- **Format**: `.xlsx`
- **Rows**: 500
- **Columns**: 10
- **Target**: `SalePrice`

**Features used**:
- `LotArea`
- `YearBuilt`
- `BedroomAbvGr`
- `GarageArea`
- `GrLivArea`
- `FullBath`
- `HalfBath`
- `OverallQual`
- `Neighborhood` (encoded)

---

## 🧠 ML Workflow

### 🔹 Step 1: Load & Explore the Data
- Loaded using `pandas.read_excel()`
- Verified data types, structure, and basic stats

### 🔹 Step 2: Data Cleaning
- No missing values in the sample
- Encoded `Neighborhood` using `LabelEncoder`

### 🔹 Step 3: EDA (Exploratory Data Analysis)
- Correlation Heatmap
- Scatter Plots for `GrLivArea`, `GarageArea` vs `SalePrice`
- Boxplot for `OverallQual` vs `SalePrice`

### 🔹 Step 4: Model Building
- **Linear Regression**
- **Random Forest Regressor**

### 🔹 Step 5: Model Evaluation

| Model              | R² Score | MAE         | RMSE        |
|-------------------|----------|-------------|-------------|
| Linear Regression | -0.049   | ₹86,483     | ₹100,146    |
| Random Forest     | -0.307   | ₹95,495     | ₹111,782    |

⚠️ *Note: This was a small sample dataset (500 rows), so performance is limited. Larger datasets and tuning would improve results.*

---

## 📈 Visualizations

| Plot Type                       | Description                            |
|----------------------------------|----------------------------------------|
| 📊 Correlation Heatmap          | To identify relationships between variables |
| 📉 Actual vs Predicted Plot     | To assess model predictions             |
| 📦 Boxplot                      | Showcasing Overall Quality vs Sale Price |
| 📈 Scatterplots                 | GarageArea / GrLivArea vs Sale Price    |

All charts are available in the `assets/` folder for preview.

---

## 📁 Project Structure

house-price-prediction-ml/
│
├── 📁 data/
│ └── house_price_sample.xlsx # Dataset
│
├── 📁 notebooks/
│ └── house_price_prediction.ipynb # Main notebook
│
├── 📁 assets/
│ ├── heatmap.png
│ ├── actual_vs_predicted.png
│ └── boxplot_overallqual.png # Visual outputs


---

## 🧪 Key Learnings

- ✅ Learned how to apply **Supervised Learning** for real-world problems
- ✅ Understood the difference in performance between **Linear** and **Ensemble** models
- ✅ Practiced **feature encoding** and **data visualization**
- ✅ Gained experience in **model evaluation** using multiple metrics
- ✅ Improved storytelling through **data plots and insights**

---

## 🚀 How to Run the Project

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/house-price-prediction-ml.git
cd house-price-prediction-ml

 Connect With Me
👩‍💼 LinkedIn: Neha Jhakra

💻 GitHub: @nehajhakra

“The best way to learn machine learning is to get your hands dirty with real projects
