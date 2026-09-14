# DERIVABLE_JUDGMENT_PR2MATH# 🏥 

## 📌 Project Overview

This project presents a statistical analysis of a **Health Record Dataset** containing 200 health-related records. The main objective is to explore the dataset, understand important health variables, and apply statistical techniques to identify significant relationships and differences between groups.

The analysis was performed using **Python and Google Colab** with libraries such as **Pandas, NumPy, SciPy, and Matplotlib**.

---

## 📂 Dataset Information

* **Dataset Name:** Health Record Dataset
* **Number of Records:** 200
* **Number of Columns:** 15
* **Data Type:** Health-related demographic and medical data
* **Analysis Tool:** Google Colab
* **Programming Language:** Python

### Important Variables

The dataset contains variables related to:

* Age
* Gender
* Weight
* BMI
* Blood Pressure
* Cholesterol Level
* Glucose Level
* Smoking Status
* Exercise Frequency
* Diabetes
* Hypertension
* Age Groups
* Other health-related attributes

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Understand and explore the health dataset.
2. Calculate descriptive statistics for numerical variables.
3. Calculate 95% confidence intervals for important numerical variables.
4. Formulate statistical hypotheses.
5. Perform Chi-Square tests on categorical variables.
6. Perform ANOVA to compare disease rates across age groups.
7. Perform a Z-test to compare mean values between groups.
8. Calculate covariance and correlation between continuous variables.
9. Create a scatter plot to visualize the relationship between Age and BMI.
10. Interpret the statistical results using p-values and critical values.

---

## 🧪 Statistical Tests Performed

### 1. Chi-Square Test — Smoking Status vs Diabetes

**H₀:** Smoking status and diabetes are not associated.

**H₁:** Smoking status and diabetes are associated.

* Chi-Square Statistic: **0.2462**
* Degrees of Freedom: **2**
* Critical Value: **5.991**
* P-value: **0.8842**
* Significance Level: **0.05**

### Result

Since the calculated Chi-Square value is less than the critical value:

**0.2462 < 5.991**

and:

**0.8842 > 0.05**

### Decision

**Fail to Reject H₀**

### Interpretation

There is no statistically significant association between **smoking status and diabetes** in the dataset.

---

## 2. Chi-Square Test — Exercise Frequency vs Hypertension

**H₀:** Exercise frequency and hypertension are not associated.

**H₁:** Exercise frequency and hypertension are associated.

* Chi-Square Statistic: **0.9020**
* Degrees of Freedom: **3**
* Critical Value: **7.815**
* P-value: **0.8249**
* Significance Level: **0.05**

### Decision

**Fail to Reject H₀**

### Interpretation

There is no statistically significant association between **exercise frequency and hypertension** in the dataset.

---

## 3. One-Way ANOVA — Age Groups vs Diabetes Rate

**H₀:** All age groups have the same diabetes rate.

**H₁:** At least one age group has a different diabetes rate.

* F-statistic: **4.5184**
* P-value: **0.0016**
* Significance Level: **0.05**

### Decision

**Reject H₀**

### Interpretation

Since the p-value is less than 0.05, there is a **statistically significant difference in diabetes rates across age groups**.

The older age groups, particularly the **60+ group**, showed higher diabetes rates in the dataset.

---

## 4. Two-Sample Z-Test — Male vs Female Weight

**H₀:** There is no significant difference between the mean weight of males and females.

**H₁:** There is a significant difference between the mean weight of males and females.

* Male Sample Size: **87**
* Female Sample Size: **111**
* Male Mean Weight: **78.86 kg**
* Female Mean Weight: **72.03 kg**
* Z-statistic: **3.48**
* Critical Value: **±1.96**
* P-value: **0.0005**
* Significance Level: **0.05**

### Decision

**Reject H₀**

### Interpretation

Since the absolute Z-statistic is greater than the critical value and the p-value is less than 0.05, there is a **statistically significant difference in mean weight between males and females**.

---

## 5. Covariance and Correlation — Age vs BMI

Covariance and Pearson correlation were calculated between **Age and BMI**.

### Purpose

* **Covariance** shows the direction in which two variables move together.
* **Correlation** measures the strength and direction of their linear relationship.
* A **scatter plot** was created to visually examine the relationship between Age and BMI.

The correlation result should be interpreted using the calculated correlation coefficient and its statistical significance.

---

## 📊 Confidence Interval Analysis

A **95% Confidence Interval** was calculated for the key numerical variables.

| Variable          |   Mean | 95% Confidence Interval |
| ----------------- | -----: | ----------------------: |
| Age               |  45.74 |           43.44 – 48.04 |
| Weight            |  74.91 |           72.93 – 76.90 |
| BMI               |  26.69 |           25.95 – 27.43 |
| Blood Pressure    | 133.18 |         131.21 – 135.15 |
| Cholesterol Level | 189.75 |         185.35 – 194.14 |
| Glucose Level     |  97.39 |           95.18 – 99.60 |

A 95% confidence interval provides a range of plausible values for the true population mean.

---

## 📋 Summary of Test Results

| Statistical Test         |           Statistic |             P-value | Decision          |
| ------------------------ | ------------------: | ------------------: | ----------------- |
| Smoking vs Diabetes      |         χ² = 0.2462 |              0.8842 | Fail to Reject H₀ |
| Exercise vs Hypertension |         χ² = 0.9020 |              0.8249 | Fail to Reject H₀ |
| Age Groups vs Diabetes   |          F = 4.5184 |              0.0016 | Reject H₀         |
| Male vs Female Weight    |            Z = 3.48 |              0.0005 | Reject H₀         |
| Age vs BMI               | Pearson Correlation | Calculated in Colab | Based on p-value  |

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Pandas** — Data loading and manipulation
* **NumPy** — Numerical calculations
* **SciPy** — Statistical tests
* **Matplotlib** — Data visualization

---

## 📁 Project Structure

```text
Health-Record-Statistical-Analysis/
│
├── HEALTH_RECORD_DATASET.CSV
├── Health_Record_Analysis.ipynb
└── README.md
```

---

## 🔍 Key Findings

* No statistically significant association was found between **smoking status and diabetes**.
* No statistically significant association was found between **exercise frequency and hypertension**.
* **Diabetes rates significantly differ across age groups**.
* **Male and female mean weights differ significantly**.
* Age and BMI were analyzed using covariance, correlation, and a scatter plot to understand their linear relationship.
* Confidence intervals provided useful estimates of population means for major numerical health variables.

---

## 📝 Conclusion

The statistical analysis of the Health Record Dataset provided useful insights into relationships and differences among demographic and health-related variables.

The hypothesis tests showed that some categorical factors did not have statistically significant associations with diseases, while **age groups showed significant differences in diabetes rates**. The Z-test also identified a significant difference in mean weight between male and female groups.

Overall, this project demonstrates the practical application of **inferential statistics, hypothesis testing, confidence intervals, correlation, covariance, and data visualization** to analyze real-world health data.

---

## 👤 Project Author

**Sahil Pathan**

### Project Type

**Statistical Data Analysis Project**

## ⭐ Final Statement

This project demonstrates how statistical methods can be used to transform raw health data into meaningful insights and support data-driven interpretation of health-related variables.
