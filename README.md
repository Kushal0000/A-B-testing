# A/B Testing - Marketing Campaign Analysis

## 📌 Project Overview

This project focuses on performing A/B Testing and Exploratory Data Analysis (EDA) to evaluate the effectiveness of a marketing campaign based on user behavior, ad exposure, and conversion patterns.

The objective is to identify whether showing different ad types (standard ads vs. public service announcements) and varying ad placements (time/day) significantly affect conversion rates. The project uses real-world marketing data and follows a structured approach to derive actionable business insights.

---

## 🛠️ Tools & Technologies

- **Python**  
- **Pandas** for data manipulation  
- **NumPy** for numerical operations  
- **Matplotlib & Seaborn** for data visualization  
- **Scipy** for statistical hypothesis testing  
- **Chi-Squared Test**, **Mann-Whitney U Test** for A/B comparison  

---

## 🔬 Project Workflow

1. **Data Cleaning & Preparation**  
   - Removed duplicates and unnecessary columns  
   - Verified categorical variables and levels  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distribution of test groups, conversion rates, ad placements (day/hour)  
   - Examined total ads distribution using histograms and boxplots  

3. **Bivariate Analysis**  
   - Assessed conversion rates across test groups, days, and hours using cross-tabulation  
   - Visualized conversion patterns with stacked bar charts  

4. **Statistical Significance Testing**  
   - **Chi-Squared Tests** for categorical variables to evaluate significant differences in conversion rates  
   - Normality and variance checks using **Shapiro-Wilk** and **Levene’s Test**  
   - Applied **Mann-Whitney U Test** for total ads due to non-normal distribution  

---

## 📊 Key Insights

- The type of ad shown (**test group**) significantly affects conversion rates (p < 0.05)  
- **Day of the week** and **hour of the day** also have a statistically significant impact on conversions  
- Users exposed to ads at certain times (e.g., 16:00 - 20:00) show higher conversion likelihood  
- Non-parametric testing confirmed significant differences in total ads exposure between converted and non-converted groups  

---

## ✅ Conclusion

This project demonstrates how structured A/B Testing and statistical analysis can provide critical insights for optimizing marketing strategies, improving ad targeting, and enhancing conversion performance.

---
