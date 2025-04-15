# SleepSmart
Uncovering Lifestyle Patterns Behind Sleep Health

# 💤 Sleep Health & Lifestyle Analysis

This project explores how lifestyle factors, demographics, and health conditions influence sleep quality and duration using a synthetic sleep dataset of 374 individuals.

---

## 📊 Objectives

- Understand sleep behaviors across different occupations, age groups, and genders
- Identify associations between physical activity, stress levels, and sleep
- Evaluate the impact of sleep disorders like Insomnia and Sleep Apnea
- Use inferential statistics to validate key hypotheses

---

## 📁 Dataset Overview

The dataset includes 13 columns:

- **Demographics**: Age, Gender, Occupation, BMI Category
- **Health & Lifestyle**: Sleep Duration, Sleep Quality, Stress Level, Heart Rate, Physical Activity, Daily Steps
- **Medical**: Sleep Disorder (None, Insomnia, Sleep Apnea)

---

## 📌 Key Descriptive Insights

| Category | Question |
|----------|----------|
| Demographic Insights | 1. What is the gender distribution? <br> 2. What is the age distribution? <br> 3. Most common occupations? <br> 4. Differences in sleep across occupations? |
| Sleep Patterns | 5. Average sleep duration & quality? <br> 6. Sleep by gender or age group? <br> 7. Who sleeps <6h or >8h? |
| Lifestyle Factors | 8. Avg. stress & physical activity? <br> 9. Stress vs. sleep quality? <br> 10. Physical activity vs. sleep duration? <br> 11. BMI category distribution? |
| Cardiovascular & Activity | 12. Average heart rate and steps? <br> 13. Differences in heart rate/steps by BMI? <br> 14. Daily steps vs. activity minutes? |

---

## 📈 Inferential Analysis Summary

| Hypothesis | Result |
|------------|--------|
| Do individuals with sleep disorders sleep less? | ✅ Yes. Statistically significant. |
| Do Sleep Apnea cases have higher heart rate? | ✅ Yes. Higher heart rate observed. |
| Do sleep disorders reduce daily steps? | ❌ No significant difference. |
| Is insomnia linked to gender? | ❌ No significant association. |
| Does stress level predict sleep quality or duration? | ✅ Yes. Strong negative predictor. |
| Are stress levels different by occupation? | ✅ Yes. Confirmed by ANOVA & Tukey HSD. |
| Is activity related to sleep duration? | ✅ Weak but significant correlation (r = 0.21). |
| Is sleep quality different between genders? | ✅ Yes. Females reported higher quality. |

---

## 📊 Statistical Methods Used

- Independent Samples **t-test**
- One-way **ANOVA** and **Tukey HSD**
- **Chi-Square Test** for categorical relationships
- **OLS Regression**
- **Pearson Correlation**

---

## 📌 Visualizations

- Histograms & KDE for Age, Sleep Duration
- Bar Charts for Occupation, Gender, BMI
- Boxplots for Stress Level by Occupation
- Regression plots for Physical Activity vs. Sleep
- Stacked Bar Plot for Insomnia by Gender
- Heatmap for Correlation Matrix

---

## 📦 Requirements

```bash
pip install pandas seaborn matplotlib scipy statsmodels
