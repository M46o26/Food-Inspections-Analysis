# 🍽️ Chicago Food Inspections Analysis

Welcome to my end-to-end Data Analysis project using real-world open data from the **City of Chicago Food Inspections**.

This project was part of the **Data Analysis Using Python** course at **Inno Code**, under the guidance of **Eng. Ahmed Othman**. It covers the full data workflow from cleaning to modeling to real-world business recommendations.

---

## 📁 Dataset
- Source: [Kaggle - Chicago Food Inspections](https://www.kaggle.com/datasets/ahmedosman5/chicago-food-inspections-2025-06-28)
- Size: ~292,000 inspection records
- Features: Facility type, Risk level, Inspection type, Violation reports, Geographic data, Results

---

## 📊 Project Workflow

### 🔹 1. Data Cleaning
- Removed nulls and inconsistent values
- Engineered new features like `Has_Violations`
- Handled data types and formatting issues

### 🔹 2. Exploratory Data Analysis (EDA)
- Investigated patterns in failure rates by:
  - Risk level
  - Facility type
  - Inspection type
- Uncovered strong correlation between violations and failures

### 🔹 3. Predictive Modeling
- Built a **Logistic Regression** model to predict inspection outcomes (Pass/Fail)
- Evaluated performance using confusion matrix and classification report
- Accuracy: **~73%**
- High recall for "Pass", lower for "Fail" (class imbalance issue)

### 🔹 4. Business Insights & Recommendations
- High-risk facilities more likely to fail
- Restaurants and daycare centers have highest failure rates
- Recommended focusing inspections on high-risk & repeat violators

---

## 📌 Key Tools & Libraries
- `Python`
- `Pandas`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`

---

## 📎 Final Thoughts

This project shows how public health data can be transformed into **actionable insights** using data science tools.  
It also demonstrates how **predictive analytics** can help cities like Chicago optimize inspection scheduling and resource allocation.

---

## 🙌 Acknowledgment

Special thanks to **Inno Code** and **Eng. Ahmed Othman** for the incredible guidance throughout the course.

---

## 🔗 Project Files

- 📘 `Food_Inspection_Project.ipynb` — Full notebook with analysis
- 📝 `README.md` — You're reading it! 
---

## ⭐ GitHub Stars Welcome!

If you found this project useful or insightful, consider giving it a ⭐ on GitHub. It helps more people discover the work and gives me motivation to share more like this 🙏
