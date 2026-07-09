# 🍔☕🍗 Starbucks vs KFC vs McDonald's — Sales Analysis & AI Model

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Colab](https://img.shields.io/badge/Google%20Colab-Ready-orange?logo=googlecolab)
![Dataset](https://img.shields.io/badge/Dataset-Curated-20beff)
![AI](https://img.shields.io/badge/AI%20Model-scikit--learn-f7931e?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 👤 Student Information

| Field | Details |
|-------|---------|
| **Student Name** | M Abu Bakar |
| **SAP ID** | 80429 |
| **Subject** | Design and Analysis of Algorithms |
| **Instructor** | Sir Karar Haider |

---

## 📌 Overview

Data analysis + AI assignment comparing **McDonald's**, **KFC**, and **Starbucks** from 2015–2024: store count, employees, revenue, and systemwide sales. Answers the question **"kispar zyada sale ho rahi hai"** (who is selling more), and trains two AI models on the data:

1. **Regression model** — predicts systemwide sales from a company's scale (year, stores, employees), plus a 2025 forecast.
2. **Classification model** (Random Forest) — identifies which company a row of stats belongs to, with a confusion matrix and feature-importance chart.

---

## 🗂️ Files in This Repository

| File | Description |
|------|-------------|
| `Sales_Comparison_AI_Analysis.ipynb` | Main Google Colab notebook — EDA, 5+ charts, and 2 trained AI models |
| `fastfood_sales_data.csv` | Curated dataset (30 rows: 3 companies × 10 years, 8 features) |
| `README.md` | This file |

---

## 📊 Dataset Features

| Column | Description |
|--------|-------------|
| `Company` | McDonald's / KFC / Starbucks |
| `Year` | 2015–2024 |
| `Stores_Worldwide` | Total store count that year |
| `Employees` | Approximate global employee count |
| `Revenue_Million_USD` | Company-reported revenue |
| `Systemwide_Sales_Million_USD` | Total sales across all stores (incl. franchises) |
| `Country_HQ` | Headquarters country |
| `Founded` | Year the company was founded |

> ⚠️ Figures are approximate/illustrative, compiled from public annual-report ranges for educational analysis — not official investor data.

---

## 📈 Visualizations Included

- ✅ Chart 1 — Systemwide sales trend (2015–2024)
- ✅ Chart 2 — 2024 sales comparison (who is winning)
- ✅ Chart 3 — Store count growth
- ✅ Chart 4 — Revenue vs employees
- ✅ Chart 5 — Correlation heatmap
- ✅ Chart 6 — Confusion matrix (AI classifier)
- ✅ Chart 7 — Feature importance (AI classifier)

## 🤖 AI Models Trained

| Model | Type | Task |
|---|---|---|
| Linear Regression | Regression | Predict systemwide sales from year/stores/employees + 2025 forecast |
| Random Forest Classifier | Classification | Identify the company from its stats (with accuracy report + confusion matrix) |

---

## 🚀 How to Run

### Google Colab
1. Go to [colab.research.google.com](https://colab.research.google.com)
2. **File → Upload notebook** → select `Sales_Comparison_AI_Analysis.ipynb`
3. **Runtime → Run All**

### Local
```bash
pip install pandas matplotlib seaborn scikit-learn
jupyter notebook Sales_Comparison_AI_Analysis.ipynb
```

---

## ✅ Key Finding

Based on 2024 systemwide sales, **McDonald's** sells the most by far (~$135B), with **Starbucks** (~$36.2B) and **KFC** (~$36B) running a close second and third. McDonald's also runs the most stores worldwide.

---

> _"Comparing the world's biggest food & beverage chains — with data and AI."_ 🍔☕🍗
> **M Abu Bakar | SAP: 80429 | Design and Analysis of Algorithms | Sir Karar Haider**
