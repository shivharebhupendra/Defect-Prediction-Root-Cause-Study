# Defect-Prediction-Root-Cause-Study

---

## 📘 Project Overview

This project focuses on analyzing defect trends and predicting repair costs in a manufacturing dataset.
Using Python (Pandas, Matplotlib, Seaborn) for data exploration and Machine Learning models for prediction,
the project demonstrates a full workflow — from data cleaning to modeling and insights.
A detailed summary is documented in a Word report that covers every step from start to end.

---

## 🎯 Objective

- Identify key defect patterns and trends.

- Understand how defect type, severity, and inspection method affect repair cost.

- Build a predictive model to estimate repair cost.

- Present insights and recommendations in a Word report.

---

## 🧹 Data Preprocessing

- Removed missing and duplicate records.

- Converted defect_date to datetime format.

- Standardized categorical variables and encoded them using LabelEncoder.

---

## 📊 Exploratory Data Analysis (EDA)

- Key findings:

  - January and March showed the highest defect counts.

  - Structural defects occurred most frequently.

  - Manual Testing had the highest average repair cost.

  - Critical defects were mainly caught in manual inspections.

  - Surface and Component areas reported the majority of issues.

---

## 🤖 Modeling
- Model	                      MAE	    RMSE	   R² Score
- Linear Regression	          258.89	297.72	 -0.004
- Random Forest Regressor	    260.77	302.62	-0.037
- Gradient Boosting Regressor	259.74	297.72	-0.035

🔹 All models performed similarly due to limited dataset size (~1,000 rows).

🔹 The models serve as a baseline for future improvement.

## 💡 Insights

- Minor defects occur most often but contribute significantly to total repair cost.

- Manual inspections are more reliable but increase cost — automation could reduce expenses.

- Surface/component issues suggest the need for stronger early-stage quality control.

---

## 🧠 Tech Stack

- Languages: Python, SQL

- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

- Documentation: Microsoft Word (Comprehensive Report)

- ML Algorithms: Linear Regression, Random Forest, Gradient Boosting

---

## 🚀 Future Scope

- Collect a larger dataset to enhance model accuracy.

- Apply feature selection and cross-validation for optimization.

- Integrate a real-time defect monitoring system using live production data.

- Deploy as an interactive web app using Streamlit or Flask.

---

## 📄 Documentation

- A complete Word Report is included, containing:

- Project Introduction

- Data Understanding & Preprocessing

- Exploratory Data Analysis (with visuals)

- Model Building & Evaluation

- Insights & Recommendations

- Future Work

- [Report Link](https://docs.google.com/document/d/1h9QRNWmmeJNg_wGxyCTA1L-ZjDDXgCFvMcKO-lZ5kik/edit?usp=sharing) 

---

## 📞 Contact

If you have any questions or feedback, feel free to reach out:

- **Email:** shivharebhupendra0@gmail.com  
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/bhupendra-shivhare-a8a02a25b/)

---

## ✍️ Author

Bhupendra Shivhare

Data Analyst | Aspiring Data Scientist




