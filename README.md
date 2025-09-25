
# Yulu Bike Rental Analysis

## 📌 Project Overview
This project analyzes the demand for shared electric bicycles provided by **Yulu**, India’s leading micro-mobility service provider. The goal is to identify factors affecting bike rental demand in India and provide actionable business recommendations to improve revenue and user experience.

---

## 🛴 About Yulu
Yulu offers sustainable and convenient commuting options through shared electric bikes, addressing the problem of traffic congestion in urban areas. Yulu zones are strategically located near metro stations, bus stands, offices, residential areas, and corporate spaces, enabling smooth first- and last-mile connectivity.

---

## 🎯 Problem Statement
Yulu recently experienced dips in revenue and aims to understand:

1. Which variables significantly predict the demand for shared electric cycles.
2. How these variables explain bike rental demand patterns.

---

## 🧰 Libraries Used
- `numpy`
- `pandas`
- `scipy`
- `matplotlib`
- `seaborn`
- `datetime`

---

## 🔍 Analysis Performed
1. **Data Cleaning**
   - Converted `datetime` to datetime type.
   - Converted categorical variables (`season`, `holiday`, `workingday`, `weather`) to category type.
   - Verified null values: none present.

2. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis of categorical and numeric variables.
   - Outlier detection using boxplots.
   - Correlation analysis using heatmaps.

3. **Time-Series Analysis**
   - Trend analysis of bike rentals over months.
   - Hourly and seasonal rental patterns.

4. **Hypothesis Testing**
   - **Effect of working day** on rentals: non-parametric tests used due to non-normal distribution.
   - **Effect of holidays** on rentals: Kruskal-Wallis H-test.
   - **Effect of weather and seasons** on rentals: Chi-square test and Kruskal-Wallis H-test.

5. **Key Insights**
   - Rentals vary significantly across seasons, weather, holidays, and working days.
   - Registered users contribute the majority of rentals (≈81%).
   - Temperature, "feels like" temperature, and user type show strong correlations with total rentals.

---

## 📈 Recommendations
1. **Seasonal Marketing:** Promote rentals during high-demand seasons (spring and summer) with discounts or special packages.
2. **Time-based Pricing:** Adjust rental rates based on peak and off-peak hours.
3. **Weather-based Promotions:** Offer discounts or incentives in favorable weather.
4. **User Segmentation:** Focus on improving casual user experience and promoting benefits to occasional riders.
5. **Collaborations with Weather Services:** Integrate real-time weather updates to influence rental behavior.
6. **Customer Feedback:** Use reviews and feedback to tailor services and improve user satisfaction.

---
