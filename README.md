# Student Performance Analysis

A beginner data analysis project using NumPy, Pandas, Matplotlib, and Seaborn to explore what affects student scores.

## 📌 Objective
Analyze how study hours, attendance, gender, and grade level relate to student performance.

##  Dataset
`data/students.csv` — 200 students with the following columns:
- `study_hours_per_day` — average hours studied per day
- `attendance_pct` — class attendance percentage
- `math`, `science`, `english` — subject scores
- `average` — average score across subjects
- `gender`, `grade_level` — student demographics
- `passed` — 1 if passed, 0 if failed

##  Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## What I Did
- Loaded and inspected the dataset
- Checked for missing values and data types
- Calculated summary statistics (mean, median, std)
- Visualized relationships with:
  - Regression plot (study hours vs. score)
  - Boxplot (score by gender)
  - Correlation heatmap
  - Histogram (score distribution)
  - Bar chart (score by grade level)

## 📊 Key Findings
- Students who study more tend to score higher
- Higher attendance is linked to better scores
