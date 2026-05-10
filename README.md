# 🦠 Covid-19 India — Case Study & Analysis using Python

A state-wise exploratory data analysis of Covid-19 cases across India, covering confirmed cases, deaths, recoveries, and time-series trends for key states — with a Linear Regression model to predict future case counts.

---

## 📌 Project Overview

This project analyzes India's Covid-19 data (`covid_19_india.csv`) to understand the spread and impact of the pandemic across different states and union territories. It includes state-wise comparisons as of **May 17, 2021** and time-series analysis for **Maharashtra, Kerala, and Jammu & Kashmir**, along with a basic predictive model for Maharashtra.

---

## 📂 Dataset

- **Source:** [Kaggle — Covid-19 India Dataset](https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india)
- **File used:** `covid_19_india.csv`
- **Columns used:** `Date`, `State/UnionTerritory`, `Cured`, `Deaths`, `Confirmed`

---

## 🔍 Analysis Breakdown

### 📊 State-wise Snapshot (as of May 17, 2021)
- Top 5 states by **confirmed cases** — bar chart
- Top 5 states by **deaths** — bar chart
- Top 5 states by **cured/recovered cases** — bar chart

### 📈 Time-Series Analysis by State

#### 🏙️ Maharashtra
- Line plot of confirmed cases over time
- Line plot of deaths over time

#### 🌴 Kerala
- Line plot of confirmed cases over time
- Line plot of deaths over time

#### 🏔️ Jammu & Kashmir
- Line plot of confirmed cases over time
- Line plot of deaths over time

### 🤖 Predictive Modeling (Maharashtra)
- Built a **Linear Regression** model using `sklearn`
- Split data into train/test sets (70/30)
- Trained on date (ordinal) vs confirmed cases
- Predicted future confirmed case counts

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualizations |
| Seaborn | Statistical bar & line plots |
| Scikit-learn | Linear Regression model |
| Google Colab | Development environment |

---

## 🚀 How to Run

### Option 1 — Open in Google Colab
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

*(Replace with your actual Colab notebook link)*

### Option 2 — Run Locally
```bash
git clone https://github.com/anshu1516/Covid19-India-Analysis.git
cd Covid19-India-Analysis

pip install pandas numpy matplotlib seaborn scikit-learn

jupyter notebook Covid_19_India_case_study.ipynb
```

> **Note:** Download `covid_19_india.csv` from Kaggle and place it in the same directory before running.

---

## 💡 Key Insights

- **Maharashtra** had the highest confirmed cases and deaths among all states as of May 2021
- **Kerala** showed a steady rise in cases with comparatively lower death rates
- Time-series plots clearly show the impact of India's **second Covid wave** in early 2021

---

## 👤 Author

**Anshu** — [GitHub](https://github.com/anshu1516)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
