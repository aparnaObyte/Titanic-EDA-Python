# 🚢 Task 5 — Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** 
on the famous Titanic dataset using Python. The goal is to uncover patterns, 
relationships, and insights related to passenger survival using 
statistical analysis and data visualization techniques.

---

## 🎯 Objective
Perform end-to-end EDA to understand the structure of the data, handle 
missing values, and discover key factors that influenced survival rates 
on the Titanic.

---

## 🗂️ Dataset
- **Name:** Titanic Dataset (train.csv)
- **Source:** Kaggle
- **Size:** 891 rows, 12 columns
- **Features:** PassengerId, Survived, Pclass, Name, Sex, Age, 
SibSp, Parch, Ticket, Fare, Cabin, Embarked

---

## 🛠️ Tech Stack
- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas` — data manipulation
  - `numpy` — numerical operations
  - `matplotlib` — data visualization
  - `seaborn` — statistical visualizations

---

## 📊 EDA Sections Covered

### Section 1 — Import Libraries & Load Data
- Imported all required libraries
- Loaded train.csv into a pandas DataFrame

### Section 2 — Data Overview
- `.shape` — 891 rows, 12 columns
- `.info()` — column datatypes and null counts
- `.describe()` — statistical summary

### Section 3 — Missing Value Analysis & Cleaning
- Visualized missing values using a **heatmap**
- **Age** (19.87% missing) → filled with **median**
- **Embarked** (0.22% missing) → filled with **mode**
- **Cabin** (77.10% missing) → **dropped** entirely

### Section 4 — Univariate Analysis
- Survival count distribution
- Gender distribution
- Age histogram
- Passenger class distribution

### Section 5 — Bivariate Analysis
- Survival rate by Gender
- Age vs Survival boxplot

### Section 6 — Multivariate Analysis
- Correlation heatmap
- Pairplot across key features

### Section 7 — Key Findings & Conclusion
- Summary of all insights discovered

---

## 🔍 Key Findings
- Only **38% of passengers survived** (342 out of 891)
- **Women had significantly higher survival rates** than men
- **1st class passengers** survived more than 2nd and 3rd class
- **Age was not a strong predictor** of survival
- **Fare and Pclass were strongly correlated** (-0.55)
- **Cabin was dropped** due to 77.10% missing values

---

## 📁 Repository Structure
-Titanic_EDA.ipynb    → Main Jupyter Notebook with full EDA

-train.csv            → Titanic dataset

-README.md            → Project documentation
