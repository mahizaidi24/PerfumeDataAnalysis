# 🌸 Noon Perfumes Price Prediction using Machine Learning

---

## 📌 Project Overview

This project analyzes the **Noon Perfumes dataset** to predict perfume prices using Machine Learning techniques.  
The dataset includes perfume details such as brand, concentration, department, size (ml), ratings, reviews, seller ratings, old price, and new price.

The main goal is to identify price patterns and build predictive models that can estimate perfume prices accurately.

---

## 🎯 Objectives

- Analyze perfume product data from Noon
- Perform data preprocessing and cleaning
- Handle missing values and remove outliers
- Apply feature engineering
- Build Machine Learning models
- Compare model performance
- Predict perfume prices using trained models

---

## 📊 Dataset

The dataset contains product-related attributes including:

- Brand Name
- Perfume Concentration
- Department
- Product Size (ml)
- Old Price
- New Price
- Product Ratings
- Number of Reviews
- Seller Rating
- Discount %

**Target Variable:** `new_price`

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed null values
- Converted text values into numeric form
- Cleaned seller rating values (K format)
- Removed outliers using IQR method
- Encoded categorical columns using Label Encoding
- Standardized numerical features using StandardScaler
- Split dataset into training and testing sets

---

## 🔍 Exploratory Data Analysis (EDA)

Visualizations used:

- Histogram plots
- Boxplots
- Correlation Heatmap
- Scatter plots
- Count plots

### Key Findings:

- Higher ml perfumes generally have higher prices
- Some brands are more expensive than others
- Discounts strongly affect new prices
- Ratings have weak effect on price

---

## 🛠️ Feature Engineering

Created new useful features:

- `discount_percent`
- `price_per_ml`

These features improved model learning and prediction performance.

---

## 🤖 Machine Learning Models

Models implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Model Performance

| Model | Performance |
|------|------------|
| Linear Regression | Good |
| Decision Tree | Better |
| Random Forest | Best |

### Best Model: 🌟 Random Forest Regressor

Because it achieved highest R² score and lowest prediction error.

---

## 📌 Important Features

Top important features affecting price:

- Old Price
- Brand
- ml
- Discount %
- Price per ml

---

## ✅ Results

The machine learning models successfully learned perfume pricing patterns.

Random Forest gave the most accurate predictions and handled complex relationships better than other models.

This model can be used for:

- Product price estimation
- Discount analysis
- E-commerce pricing strategy
- Competitive product comparison

---

## ⚠️ Limitations

- Dataset size was limited
- Real-time market prices may change
- Some categorical values may affect results differently

---

## 🚀 Future Improvements

- Use XGBoost / Gradient Boosting
- Hyperparameter tuning with GridSearchCV
- Deploy as Web App using Streamlit
- Use larger real-time dataset

---

## 👨‍💻 Project By

**Mahnoor(22)**
---
## 👨‍💻 Project Report By
**Kosar Tawassoli(14)**
## 🔗 Links
 
- Dataset Source: *(https://www.kaggle.com/datasets/monirahabdulaziz/noon-perfume)*

---
