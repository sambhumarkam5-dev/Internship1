# Student Performance Prediction System

## Project Overview

The **Student Performance Prediction System** is a Machine Learning project designed to predict a student's final exam score based on academic performance, attendance, study habits, participation, and other personal factors. This project demonstrates the complete machine learning workflow, from data generation and preprocessing to model training, evaluation, and prediction.

The project uses a synthetic dataset containing **2,500 student records** and applies regression algorithms to estimate students' final examination scores.

---

# Problem Statement

Educational institutions collect a large amount of student-related data every year. Analyzing this data can help identify students who may require additional academic support.

The objective of this project is to build a predictive model that estimates a student's final exam score using various academic and behavioral features, enabling data-driven educational decision-making.

---

# Objectives

* Generate a realistic synthetic student dataset.
* Perform data cleaning and preprocessing.
* Explore relationships between different academic factors.
* Visualize student performance trends.
* Train machine learning regression models.
* Evaluate model performance using standard metrics.
* Build an interactive prediction system for new student data.

---

# Dataset Information

The dataset contains **2,500 synthetic student records** with the following features:

| Feature                   | Description                                          |
| ------------------------- | ---------------------------------------------------- |
| StudentID                 | Unique identifier for each student                   |
| Age                       | Student age                                          |
| Gender                    | Male or Female                                       |
| AttendancePercentage      | Attendance percentage                                |
| StudyHoursPerWeek         | Weekly study hours                                   |
| AssignmentCompletionRate  | Assignment completion percentage                     |
| PreviousExamScore         | Previous examination score                           |
| ParticipationScore        | Classroom participation score                        |
| ExtracurricularActivities | Participation in extracurricular activities (Yes/No) |
| InternetAccessAtHome      | Internet availability at home (Yes/No)               |
| ParentEducationLevel      | High School / Graduate / Postgraduate                |
| FinalExamScore            | Target variable                                      |

---

# Dataset Generation

The dataset was generated using **NumPy** and **Pandas** with realistic distributions.

The Final Exam Score was calculated using weighted contributions from:

* Attendance Percentage
* Study Hours
* Assignment Completion Rate
* Previous Exam Score
* Participation Score
* Extracurricular Activities
* Internet Access
* Parent Education Level

Random noise was added to simulate real-world variability.

---

# Data Preprocessing

The following preprocessing steps were performed:

* Checked missing values
* Removed duplicate records
* Validated numerical ranges
* Encoded categorical variables
* Feature selection
* Prepared data for machine learning
* Optional feature scaling

---

# Exploratory Data Analysis (EDA)

EDA was performed to understand the relationships between variables.

### Analysis Included

* Attendance vs Final Exam Score
* Study Hours vs Performance
* Assignment Completion Rate Analysis
* Parent Education Level Comparison
* Correlation Analysis
* Distribution of Final Scores

### Key Observations

* Higher attendance generally resulted in higher final exam scores.
* Students who studied more hours per week tended to perform better.
* Previous exam performance showed a strong positive relationship with final exam scores.
* Higher assignment completion rates positively influenced student performance.
* Students whose parents had higher education levels showed slightly better average performance.

---

# Data Visualization

The project includes the following visualizations:

* Scatter Plot: Attendance Percentage vs Final Exam Score
* Bar Chart: Average Score by Parent Education Level
* Heatmap: Correlation Matrix
* Histogram: Final Exam Score Distribution

Optional visualizations include:

* Study Hours vs Final Score
* Participation Score Analysis
* Assignment Completion Trends
* Box Plot of Final Scores

Libraries used:

* Matplotlib
* Seaborn

---

# Machine Learning Models

The following regression algorithms were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

Random Forest Regressor achieved the best prediction performance for this dataset.

---

# Model Evaluation

The models were evaluated using the following metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics were used to compare model performance and prediction accuracy.

---

# Interactive Prediction System

The project includes a console-based prediction interface where users can enter:

* Attendance Percentage
* Study Hours Per Week
* Assignment Completion Rate
* Previous Exam Score
* Participation Score
* Parent Education Level
* Extracurricular Activity Status

### Example Output

```
Predicted Final Exam Score : 86.54 %
```

---

# Error Handling

The application includes input validation to:

* Prevent invalid numerical values
* Handle missing inputs
* Validate percentage ranges
* Display meaningful error messages
* Prevent runtime crashes

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Project Structure

```
Student-Performance-Prediction/
│
├── student_prediction.ipynb
├── student_prediction.py
├── student_performance_dataset.csv
├── README.md
├── requirements.txt
├── images/
│   ├── attendance_vs_score.png
│   ├── parent_education_bar.png
│   ├── correlation_heatmap.png
│   └── score_distribution.png
└── output/
    └── prediction_result.txt
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Student-Performance-Prediction.git
```

Navigate to the project folder:

```bash
cd Student-Performance-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

# How to Run

Run the Jupyter Notebook:

```bash
jupyter notebook student_prediction.ipynb
```

Or execute the Python script:

```bash
python student_prediction.py
```

---

# Results

* Successfully generated a dataset of 2,500 student records.
* Performed preprocessing and feature engineering.
* Conducted exploratory data analysis with meaningful visualizations.
* Trained multiple regression models.
* Evaluated model performance using standard regression metrics.
* Developed an interactive prediction system capable of estimating final exam scores.

---

# Future Enhancements

* Deploy the model using Flask or Streamlit.
* Use real-world educational datasets.
* Build a web-based dashboard for predictions.
* Integrate deep learning models.
* Add student performance monitoring and reporting features.

---

# Author

**Bharti**

GitHub: https://github.com/gitanjalibhoi845-svg

---

# License

This project is developed for educational and internship purposes.
