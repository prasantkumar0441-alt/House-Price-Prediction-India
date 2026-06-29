# 🏠 House Price Prediction in India using Machine Learning

An end-to-end Machine Learning Regression project that predicts house prices in Bengaluru, India using property features such as location, area, BHK, bathrooms, and balconies.

---

## 📌 Project Overview

The objective of this project is to build an accurate regression model for predicting house prices using real-world housing data.

The project covers the complete Machine Learning workflow:

- Data Loading
- Data Cleaning & Preprocessing
- Outlier Detection & Removal
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation
- Feature Importance
- Business Insights

---

## 🎯 Objective

Develop a regression model that accurately predicts house prices based on different housing features and compare multiple Machine Learning algorithms to identify the best-performing model.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```text
House-Price-Prediction-India
│
├── data
├── notebook
├── report
├── images
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 📊 Dataset

**Dataset Name:** Bengaluru House Price Dataset

**Target Variable:** Price

### Features

- Area Type
- Availability
- Location
- Total Square Feet
- BHK
- Bathrooms
- Balcony
- Price

---

## 🔄 Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Outlier Removal
5. Feature Engineering
6. Exploratory Data Analysis
7. Model Building
8. Model Evaluation
9. Business Insights
---

# 📈 Exploratory Data Analysis (EDA)

## Distribution of House Prices

![House Price Distribution](images/01_house_price_distribution.png)

---

## Price vs Total Square Feet

![Price vs Total Sqft](images/02_price_vs_total_sqft.png)

---

## Price vs BHK

![Price vs BHK](images/03_price_vs_bhk.png)

---

## Top 10 Locations

![Top Locations](images/06_top_10_locations.png)

---

## Correlation Heatmap

![Correlation Heatmap](images/07_correlation_heatmap.png)

---

# 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

# 📊 Model Performance

| Model | MAE | RMSE | R² Score |
|------|------:|------:|------:|
| Linear Regression | 26.28 | 84.37 | 0.7358 |
| Decision Tree | 4.63 | 46.01 | 0.9214 |
| Random Forest | 2.27 | 32.26 | **0.9313** |

---

## 📷 Model Comparison

![Model Comparison](images/12_model_comparison_table.png)

---

# ⭐ Feature Importance

The Random Forest model identified the following features as the most influential in predicting house prices.

![Feature Importance](images/11_feature_importance.png)

---

# 💡 Key Business Insights

- Property location is one of the strongest factors affecting house prices.
- Larger properties generally have higher market value.
- The number of bedrooms and bathrooms significantly influences pricing.
- Removing outliers improved model performance.
- Random Forest achieved the highest prediction accuracy among all models.

---

# 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost and CatBoost implementation
- Model deployment using Flask or Streamlit
- Integration with real-time housing APIs
- Interactive prediction dashboard

---

# 👨‍💻 Author

**Prashant Kumar Nandi**

If you found this project useful, consider giving it a ⭐ on GitHub.
