# Nutritional-most-common-foods
Analyze food nutrition data and predict calorie content using regression models. Includes data cleaning, visualizations, and machine learning with scikit-learn. Suitable for food science and health analytics projects.
# 🥗 Nutritional Data Analysis & Calorie Prediction

> A data-powered exploration of food nutrients and machine learning models to predict calorie content. Built with care to understand the nutritional universe in simple, visual, and predictive ways.

---

## 📦 Project Overview

**Nutritional Data Analysis & Calorie Prediction** is a comprehensive data science notebook that dives deep into the nutritional makeup of food items. Using a structured approach combining EDA and predictive modeling, this project helps:

* Understand what makes certain foods calorie-dense
* Visualize nutrient distributions and trends
* Build models to predict calories using protein, fat, carbs, etc.

---

## 🧰 Features

* ✅ Data Cleaning & Preprocessing
* 📊 In-depth Exploratory Data Analysis (EDA)
* 📈 Graphical Visualizations (Bar, Pie, Scatter, Funnel Charts)
* 🤖 ML Models: Linear Regression, Random Forest
* 🧪 Model Evaluation using R² and RMSE
* 🧠 Insightful Summary + Future Roadmap

---

## 📁 Dataset Used

* File: `nutrients_csvfile.csv`
* Total Features: 6 numeric nutrient values and 2 descriptors
* Key Columns:

  * `Food`: Food item name
  * `Category`: Type of food (e.g., Dairy, Meat, Fruits)
  * `Calories`, `Protein`, `Fat`, `Sat.Fat`, `Carbs`, `Fiber`

---

## 🧹 Step-by-Step Data Cleaning

1. Dropped null/missing rows to maintain integrity
2. Ensured nutrient columns were numeric
3. Cleaned outliers and standardized category names
4. Filtered data for analysis-ready structure

---

## 🔍 Exploratory Data Analysis (EDA)

Multiple visualizations were created to understand:

* 🔝 Top 10 foods in each nutrient
* 📊 Category-wise nutrient distribution (via pie charts)
* 📉 Carbs vs Protein/Fat/Fiber plots
* 🎯 Highlighting high-fat and high-calorie desserts and meats

---

## 🧠 ML Model Development

### 🎯 Objective:

Use features like Protein, Fat, Sat.Fat, Carbs, Fiber to predict `Calories`

### 🔧 ML Pipeline:

* **Train-Test Split** (80/20)
* **Models Used**:

  * Linear Regression (simple baseline)
  * Random Forest Regressor (non-linear, more robust)

---

## 📈 Model Performance

* Metrics Used:

  * **R² Score** – Variance explanation
  * **RMSE** – Root Mean Square Error

### Results:

| Model             | R² Score | RMSE   |
| ----------------- | -------- | ------ |
| Linear Regression | 0.69     | \~38.1 |
| Random Forest     | 0.91     | \~17.5 |

✅ Random Forest performed best due to its ability to capture complex relationships.

---

## 🔮 What’s Next?

* 🏷️ Binary classification: High vs Low calorie food
* 🍽️ Incorporate portion sizes into the analysis
* 🖥️ Build Streamlit or Gradio app for interaction
* 💾 Save trained models using joblib for future use

---

## ⚙️ Installation Guide

To run this project locally:

```bash
# Clone the repo
https://github.com/yourusername/nutrition-calorie-analysis.git

# Move to directory
cd nutrition-calorie-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

---

##
