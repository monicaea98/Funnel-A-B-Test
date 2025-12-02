User Funnel & A/B Test Analysis

A Python-based project focused on analyzing user behavior through a conversion funnel and evaluating the results of an A/A/B experiment. The objective is to identify where users drop off in the app onboarding process and determine whether the interface changes introduced in the experimental group have a measurable impact on user conversion.

---

## 🎯 Project Overview

This project includes two main analytical components:

### 1. User Funnel Analysis
The goal is to measure user progression through the main stages of the app and identify bottlenecks. The funnel steps include:

- App Launch  
- Main Screen Appearance  
- Offers Screen View  
- Cart Screen View  
- Purchase Completion  

This analysis reveals where the largest drop-offs occur and provides insights to improve overall user experience and conversion.

### 2. A/A/B Experiment Evaluation
An experiment was conducted using two control groups (A1, A2) and one experimental group (B). The objectives are:

- Validate whether A1 and A2 are statistically identical  
- Compare group B against control groups  
- Measure differences in user behavior and conversion  
- Evaluate the impact of UI changes introduced to group B  

---

## 🧩 Problem it Solves

This project helps businesses:

- Understand how users move through the product  
- Identify drop-off points and UX bottlenecks  
- Validate whether changes in the interface affect user behavior  
- Make decisions based on statistically valid evidence  
- Avoid implementing UI changes that show no real impact  

---

## 🛠️ Technologies Used

- 🐍 Python  
- 📊 Pandas — data preprocessing and user-level aggregation  
- 📈 Matplotlib & Seaborn — funnel and experiment visualizations  
- 🧮 SciPy — statistical significance testing  
- 📘 Jupyter Notebook — step-by-step interactive analysis  

---

## 📊 Key Visuals

- Funnel step conversion charts  
- Comparison plots between A1, A2, and B  
- Distribution plots of user actions  
- Statistical test summaries  
- Retention and conversion metrics per group  

---

## 📈 Key Insights

- Groups A1 and A2 show no statistically significant differences, confirming proper experiment randomization.  
- Group B does **not** significantly outperform control groups in major funnel metrics.  
- The biggest drop-off occurs between viewing the main screen and the offers screen.  
- UI changes tested in group B do not justify implementation due to lack of measurable improvement.

---

## 🧠 Conclusion

This analysis demonstrates the importance of funnel measurements and statistically validated A/B tests before modifying the product.  
While the new UI design (group B) did not lead to significant improvements, the funnel analysis highlights key areas where optimization efforts should be focused.
