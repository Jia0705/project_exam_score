# 🎓 Predicting Student Exam Score Using Academic and Behavioral Data

---

## 📌 Purpose

The purpose of this project is to analyze student data and build a machine learning model that predicts exam score, helping to identify the key factors that influence academic performance

---

## 🧪 Null Hypothesis

- **H0** – There is no significant relationship between student behavioral / academic factors and their exam score  
- **H1** – There is significant relationship between student behavioral / academic factors and their exam score

---

## 📊 What This Project Includes

- Clean and explore the dataset  
- Understand habits like study time, sleep, social media use, etc.  
- Test relationships using slope and p-values  
- Train 9 different machine learning models  
- Choose the best 3 models and combining them  
- Build a demo to let others try the model

---

## 📂 Project Files

- `project_score.ipynb` – Main notebook  
- `student_habits_performance.csv` – Dataset used  
- `exam_score_model.joblib` – Base model (Linear Regression)  
- `exam_score_model2.joblib` – Final Voting Regressor model  
- `README.md` – This file  

---

## 📊 Dataset Source and Structure

- Dataset: [Student Habits vs Academic Performance – Kaggle](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)  
- Total Data: 1,000 students  
- Columns:

  - `student_id`  
  - `age`  
  - `gender`  
  - `study_hours_per_day`  
  - `sleep_hours`  
  - `social_media_hours`  
  - `netflix_hours`  
  - `exercise_frequency`  
  - `diet_quality`  
  - `mental_health_rating`  
  - `attendance_percentage`  
  - `internet_quality`  
  - `part_time_job`  
  - `extracurricular_participation`  
  - `parental_education_level`  
  - `exam_score` (target)

---

## 🔍 Main Findings

- Students who study more, sleep well, and have good mental health score higher  
- Watching too much netflix or using social media will have lower scores  
- Gender and part-time job have very little to no effect  
- Final model (Voting Regressor) gives 86.6% accuracy

---

## 📈 Final Model Result

| Model               | R² Score | MSE     |
|--------------------|----------|---------|
| Voting Regressor   | 0.8661   | 35.67   |

---
