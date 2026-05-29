# 🚢 Task 1 — Titanic Passenger Survival Study

<p align="center">
  <img src="https://img.shields.io/badge/Internship-CodTech-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Task-1%20of%204-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Data%20Science-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-yellow?style=for-the-badge&logo=python" />
</p>

---

## 📌 Overview

A thorough investigation of the **RMS Titanic passenger dataset**, combining statistical analysis, visual exploration, feature engineering, and machine learning to understand the key factors that determined survival.

> **Intern:** Rahul Prasad  
> **Internship:** CodTech Data Science Internship  
> **Task:** 1 — Exploratory Data Analysis & Classification  

---

## 🎯 Objective

- Identify patterns and factors that influenced passenger survival
- Perform end-to-end EDA with rich visualizations
- Engineer meaningful new features from raw data
- Build and evaluate a **Random Forest Classifier** to predict survival

---

## 📂 File Structure

```
📁 Task1-Titanic/
 └── Titanic_Survival_Study.ipynb   ← Main notebook (run top to bottom)
```

---

## 📊 Dataset

| Property     | Details                                      |
|-------------|----------------------------------------------|
| Source       | Seaborn built-in (`sns.load_dataset('titanic')`) |
| Rows         | 891 passengers                               |
| Features     | 15 columns (age, sex, class, fare, etc.)     |
| Target       | `survived` — 0 (No) / 1 (Yes)               |
| No download  | Auto-loads on first run ✅                   |

---

## 🔬 Notebook Structure

| Section | Description |
|---------|-------------|
| 1 | Import Libraries |
| 2 | Load Dataset |
| 3 | Data Overview (types, stats, missing values) |
| 4 | Data Cleaning |
| 5 | Exploratory Data Analysis — 7 visualizations |
| 6 | Feature Engineering (family_size, age_bin, fare_bin, is_alone) |
| 7 | Model Preparation & Train/Test Split |
| 8 | Random Forest Classifier (200 trees) |
| 9 | Model Evaluation (Accuracy, ROC-AUC, Confusion Matrix, Feature Importance) |
| 10 | Conclusions |

---

## 📈 Key Findings

| Factor | Finding |
|--------|---------|
| **Gender** | Females survived at ~74% vs males at ~19% |
| **Class** | 1st class: ~63% \| 2nd: ~47% \| 3rd: ~24% survival |
| **Age** | Children had higher survival rates |
| **Family Size** | Small families (2–4) survived better than solo travelers |
| **Fare** | Higher fare strongly correlated with survival |

---

## 🤖 Model Performance

| Metric | Value |
|--------|-------|
| Algorithm | Random Forest Classifier |
| Trees | 200 |
| Test Accuracy | ~82–84% |
| 5-Fold CV Accuracy | ~82% |
| AUC Score | ~0.88+ |

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

---

## ▶️ How to Run

```bash
# Option 1 — Jupyter Notebook
# Upload Titanic_Survival_Study.ipynb → Kernel → Restart & Run All

# Option 2 — Install dependencies if needed
pip install pandas numpy matplotlib seaborn scikit-learn
```

> ✅ No dataset download required — auto-loads from seaborn.

---

## 📜 License

This project is part of the **CodTech Data Science Internship** program.

---

<p align="center">Made with ❤️ by <b>Rahul Prasad</b> | CodTech Internship 2026</p>

