# 📊 Physical Fitness Predication & Analysis

> *A statistical analysis of lifestyle behaviors, physical activity,
> BMI, and diabetes risk using the NHANES 2017--2020 dataset.*

---

## 📌 Project Status
**Framework:** Complete ✅  
**Course:** DATA 608 – Probability & Statistics in Data Science  
**Instructor:** Dr. Zeynep Kacar 

---

## 👥 Team Meambers
- Soumya Bhate <ms77930@umbc.edu>
- Harikrishnan Sudheendran <lw43619@umbc.edu>

---

## 📌 Project Overview

This project was completed for **DATA 608 -- Probability & Statistics**
at UMBC. The objective is to investigate how lifestyle behaviors such as
physical activity, sleep, sedentary time, and body composition are
associated with diabetes status and overall physical fitness.

Using statistical inference techniques, the project explores
relationships within the **National Health and Nutrition Examination
Survey (NHANES 2017--2020)** dataset and answers key public health
questions through data analysis and predictive modeling.

---

## 🎯 Objectives

-   Perform exploratory data analysis (EDA) on health and lifestyle
    data.
-   Compare physical activity levels across BMI categories.
-   Determine whether diabetes status is associated with physical
    activity.
-   Identify significant predictors of diabetes using Logistic
    Regression.
-   Interpret statistical findings using hypothesis testing.

---

## 📂 Dataset

**Source:** National Health and Nutrition Examination Survey (NHANES
2017--2020)

The cleaned dataset contains **1,028 participants** and includes
demographic, health, and lifestyle variables such as:

-   Age
-   Gender
-   Height & Weight
-   BMI & BMI Category
-   Sleep Duration
-   Physical Activity Level
-   Sitting Time
-   Diabetes Status
-   Education

---

## 🛠️ Technologies Used

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   SciPy
-   Statsmodels
-   Scikit-learn

---

## 📈 Statistical Methods

### Exploratory Data Analysis (EDA)

-   Data cleaning and preprocessing
-   Missing value analysis
-   Distribution analysis
-   Correlation analysis
-   Boxplots and scatter plots
-   Summary statistics

### One-Way ANOVA

Research Question: \> Does Physical Activity Level differ across BMI
categories?

Result: - F-statistic = **2.3713** - p-value = **0.069** - No
statistically significant difference at α = 0.05.

### Post-hoc Analysis

Methods used: - Tukey HSD - Bonferroni Correction - Scheffé Test

The follow-up tests supported the ANOVA conclusion that differences
between BMI groups were weak.

### Logistic Regression

Target Variable: - Diabetes Status

Significant predictors: - Age - Weight - BMI - Height - Gender

### Welch Two-Sample t-Test

Research Question: \> Is Physical Activity Level different between
diabetic and non-diabetic individuals?

Results: - t = **4.8511** - p = **3.29 × 10⁻⁶**

Conclusion: Non-diabetic individuals exhibited significantly higher
physical activity levels.

---

## 📊 Key Findings

-   Physical activity is strongly associated with diabetes status.
-   Sitting time tends to have a negative relationship with activity
    levels.
-   Sleep duration shows a weak positive relationship with physical
    activity.
-   BMI alone was not sufficient to explain differences in fitness.
-   Lifestyle and demographic variables together improve diabetes
    prediction.

---

## 📁 Repository Structure

    ├── physical fitness(3).ipynb      # Main notebook
    ├── final_fitness_dataset.csv      # Cleaned dataset
    ├── Final Report.pdf               # Detailed report
    ├── Physical-Fitness-and-Diabetes-Analysis.pptx
    ├── requirements.txt
    └── README.md

---

## ▶️ Installation

``` bash
git clone <repository-url>

cd <repository-folder>

pip install -r requirements.txt

jupyter notebook
```

Open **physical fitness(3).ipynb** and run all cells.

---

🙏 Acknowledgements

We would like to express our sincere gratitude to Prof. Zeynep Kacar, instructor of DATA 608 – Probability & Statistics at UMBC, for her continuous guidance, encouragement, and valuable feedback throughout this project. Her teaching of statistical inference, hypothesis testing, and data analysis provided the foundation for successfully completing this work.

We also thank the Centers for Disease Control and Prevention (CDC) for making the NHANES 2017–2020 dataset publicly available, enabling this research and analysis.

---

📄 License

This repository is intended for educational and academic purposes.
