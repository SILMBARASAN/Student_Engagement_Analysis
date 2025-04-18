# 📊 Data Analyst Intern Assignment - Student_Engagement_Analysis

## 🧠 Problem Statement

Zylentrix is an online learning platform offering various courses like Digital Marketing, Python, and UI/UX. The platform records user behavior such as login activity, time spent on courses, and feedback ratings. The goal of this assignment is to analyze student engagement and satisfaction using provided data and identify the top-performing student segments.

---

## 📁 Dataset Description

You are provided with three CSV files:

1. **students.csv**  
   Contains student demographics and enrollment info.  
   **Columns:**  
   - Student_ID  
   - Name  
   - Age  
   - Gender  
   - Location  
   - Enrolment_Date

2. **course_activity.csv**  
   Tracks student activity across courses.  
   **Columns:**  
   - Student_ID  
   - Course_ID  
   - Date  
   - Time_Spent_Minutes 
   - Completion_Percentage

3. **feedback.csv**  
   Contains student ratings and feedback.  
   **Columns:**  
   - Student_ID  
   - Course_ID  
   - Rating
   - Feedback_Text

---

## ✅ Tasks Performed

- Read and cleaned all three datasets.
- Standardized column names for consistency.
- Merged the datasets on `Student_ID` and `Course_ID`.
- Created a new metric:  
  `Engagement + Satisfaction = (Time Spent * 0.7) + (Rating * 0.3)`
- Grouped students by demographics (Age, Location).
- Identified top 3 segments based on average engagement-satisfaction score.

---

## 📌 Insights

Students from specific age groups and locations tend to show higher engagement and satisfaction.

The Engagement + Satisfaction metric helps identify which segments are most effectively interacting with the platform.

## 📬 Author

Silmbarasan Senthilkumar

Email: sibisaran03@gmail.com
