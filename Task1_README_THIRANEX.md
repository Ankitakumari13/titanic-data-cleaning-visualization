# 🚢 Data Cleaning & Visualization Project — Titanic Dataset

**Internship:** Data Science Internship @ [Thiranex](https://thiranex.in)
**Author:** Ankita Kumari
**Task:** 1 of 4 — Data Cleaning & Visualization Project

## 📌 Project Overview

This project applies core data cleaning and exploratory visualization techniques to the famous **Titanic dataset**, which contains details of passengers aboard the Titanic — including age, gender, passenger class, fare, and survival status.

The goal was to clean a raw, real-world dataset and uncover meaningful patterns about passenger demographics and survival through visualizations.

## 🎯 Objectives

- Understand the structure of the Titanic dataset
- Identify and handle missing values
- Remove duplicate records and irrelevant columns
- Visualize key passenger attributes and survival trends
- Extract actionable insights from cleaned data

## 🗂️ Dataset

The dataset includes the following columns:

`PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

## 🧹 Data Cleaning Steps

| Step | Action |
|------|--------|
| Missing `Age` values | Filled with the **median** age |
| Missing `Embarked` values | Filled with the **mode** (most frequent port) |
| `Cabin` column | Dropped — too many missing values |
| Duplicate rows | Removed to keep one record per passenger |

## 📊 Visualizations Created

1. **Survival Count** — overall count of survivors vs. non-survivors
2. **Passenger Class Distribution** — passenger split across 1st, 2nd, 3rd class
3. **Age Distribution** — histogram showing age spread of passengers
4. **Gender Distribution** — male vs. female passenger counts
5. **Survival by Gender** — survival comparison across genders

## 🔍 Key Insights

- Female passengers had a **significantly higher survival rate** than male passengers
- The majority of passengers traveled in **Third Class**
- Most passengers were aged between **20–40 years**
- Passenger class showed a strong relationship with survival outcome
- Cleaning the data (handling nulls/duplicates) led to more reliable analysis

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — data manipulation & cleaning
- **Matplotlib** & **Seaborn** — data visualization
- **Kaggle Notebook** — development environment

## 📁 Repository Structure

```
├── task-1-internship.ipynb     # Jupyter notebook with code, cleaning steps & charts
├── Data_Cleaning_and_Visualization_Report.docx   # Detailed project report
└── README.md                    # Project summary (this file)
```

## ▶️ How to Run

1. Clone this repository
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open `task-1-internship.ipynb` in Jupyter Notebook / Google Colab / Kaggle
4. Run all cells

## ✅ Outcome

This project strengthened practical skills in **data preprocessing, exploratory data analysis, and storytelling through visualization** — core foundations for any Data Science role.

---
*This project was completed as part of the Data Science Internship at [Thiranex](https://thiranex.in).*
