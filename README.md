# Project1_Zomato_Rating
# 🍽️ Zomato Restaurant Rating Prediction – End-to-End ML Project

## 📌 Project Overview
This project builds a machine learning model to predict restaurant ratings on Zomato using Bangalore restaurant data. The pipeline includes data cleaning, EDA, feature engineering, model building, and business insights.

---

## 🔍 Key Features
- Cleaned and processed 50K+ rows and 17+ columns
- Performed extensive EDA (over 15+ visualizations)
- Built 3 regression models:
  - Linear Regression
  - Random Forest
  - XGBoost
- Achieved 0.90 R² using Random Forest
- Extracted business insights from feature importance

---

## 🧹 Data Cleaning
- Removed duplicates, cleaned `rate`, `cost`
- Merged rare categories into `"other"`
- Created `primary_cuisine`
- One-hot encoded categorical features

---

## 📊 EDA Insights
- Ratings peak between **3.2–4.2**
- Table booking and online order slightly increase ratings
- Most restaurants priced between **₹300–₹700**
- Premium cuisines (Sushi, Korean, French) have highest average ratings
- Popular locations: BTM, Koramangala, Indiranagar
- Votes strongly influence rating stability

---

## 🤖 Model Performance

| Model | MAE | RMSE | R² |
|-------|-------|--------|-------|
| Linear Regression | 0.268 | 0.345 | 0.384 |
| Random Forest | **0.067** | **0.134** | **0.906** |
| XGBoost | 0.173 | 0.244 | 0.692 |

**Winner: Random Forest (R² = 0.90)**

---

## 📈 Feature Importance
Top features influencing rating:
1. Votes
2. Cost
3. Primary Cuisine
4. Book Table
5. Online Order
6. Restaurant Type
7. Location

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- XGBoost

---

## 📁 Folder Structure
