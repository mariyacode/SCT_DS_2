# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **data cleaning and exploratory data analysis (EDA)** on the Titanic dataset.
The goal is to understand patterns, relationships, and factors that influenced passenger survival.

---

## 📂 Dataset

* Dataset: Titanic Dataset
* Source: Kaggle
* File used: `Titanic-Dataset.csv`

---

## 🎯 Objectives

* Clean the dataset (handle missing values, duplicates, etc.)
* Perform exploratory data analysis (EDA)
* Visualize relationships between features
* Identify key factors affecting survival

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 🧹 Data Cleaning Steps

* Handled missing values:

  * Filled `Age` with median values
  * Filled `Embarked` with mode
* Dropped `Cabin` column (too many missing values)
* Converted categorical data:

  * `Sex` → numeric
  * `Embarked` → numeric
* Removed duplicate records

---

## 📊 Exploratory Data Analysis (EDA)

### ✔ Survival Analysis

* Compared number of survived vs not survived passengers

### ✔ Gender vs Survival

* Analyzed survival rate based on gender

### ✔ Passenger Class vs Survival

* Studied how ticket class affected survival chances

### ✔ Age Distribution

* Visualized age spread of passengers

### ✔ Fare Distribution

* Examined ticket fare patterns

### ✔ Correlation Analysis

* Used heatmap to find relationships between variables

---

## 🔍 Key Insights

* 👩 Female passengers had a much higher survival rate than males
* 🏆 First-class passengers had better survival chances
* 👶 Younger passengers showed slightly higher survival trends
* 💰 Higher fare is positively correlated with survival
* 🌍 Most passengers boarded from Southampton

---

## 📁 Project Structure

```
Titanic-EDA-Analysis/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── Titanic_EDA.ipynb
├── cleaned_titanic.csv
└── README.md
```

---

## ▶️ How to Run

1. Open Google Colab
2. Upload dataset (`Titanic-Dataset.csv` or ZIP file)
3. Run the notebook step by step
4. Perform cleaning and EDA

---

## 📌 Results

The analysis reveals that **gender, passenger class, and fare** are key factors influencing survival.

---

## 🚀 Future Improvements

* Apply Machine Learning models (Logistic Regression, Decision Tree)
* Improve feature engineering
* Build a prediction system for survival

---

## 🙌 Acknowledgement

* Dataset provided by Kaggle
* Project created for learning Data Analysis and building portfolio

---

## ⭐ Conclusion

This project demonstrates the complete workflow of:

* Data Cleaning
* Data Visualization
* Insight Extraction

It is a beginner-friendly project that builds a strong foundation in data analysis.

---
