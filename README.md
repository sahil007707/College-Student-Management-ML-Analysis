# 🎓 College Student Risk Prediction & Management 📊

> An interactive EDA + ML project to analyze and predict student risk levels using behavioral and academic data.

---

## 🧠 Project Overview

This project aims to help colleges and educators proactively identify students who are at academic risk by analyzing various factors such as GPA, attendance, LMS activity, assignment submission, and more.

🔍 The workflow includes:
- In-depth **Exploratory Data Analysis (EDA)** of student behavior and performance
- Building a machine learning model to **predict risk level** (High / Medium / Low)
- Interactive and beautiful **visualizations** using Plotly and Seaborn
- Data-driven insights to improve **student success strategies**

---

## 📂 Notebooks Included

1. **📊 College Student Management EDA Analysis**
   - Data overview & cleaning
   - Statistical summaries
   - Gender-wise and major-wise visualizations
   - Risk level breakdowns
   - Correlation heatmap & relationship exploration

2. **🧠 College Student Management Risk Prediction ML Analysis**
   - Feature engineering & preprocessing
   - Train-test split & scaling
   - Model building using RandomForestClassifier
   - Evaluation metrics: accuracy, classification report, confusion matrix
   - Feature importance visualization

---

## 📈 Dataset Description

| Column                       | Description |
|-----------------------------|-------------|
| `age`                       | Age of the student |
| `gender`                    | Gender (Male/Female) |
| `major`                     | Student's major field |
| `GPA`                       | Grade Point Average |
| `course_load`              | Number of courses enrolled |
| `avg_course_grade`         | Mean grade across all enrolled courses |
| `attendance_rate`          | Attendance percentage |
| `enrollment_status`        | Full-time / Part-time status |
| `lms_logins_past_month`    | Count of LMS logins in past month |
| `avg_session_duration_minutes` | Average LMS session time |
| `assignment_submission_rate` | Percentage of assignments submitted |
| `forum_participation_count` | Number of forum posts/replies |
| `video_completion_rate`    | Percent of educational videos watched |
| `risk_level`               | Target variable (Low, Medium, High) |

---

## 📊 Key Visualizations

- Pie charts for **Gender & Risk Levels**
- Histograms for GPA, Attendance, Video Completion
- Boxplots comparing risk level vs GPA, LMS activity, submissions
- Correlation heatmap of numerical features
- Pairplot for relationship analysis
- Feature importance graph for top predictors

---

## 🤖 Machine Learning Model

| Metric         | Score |
|----------------|-------|
| Model          | Random Forest Classifier |
| Accuracy       | ~91% |
| Key Features   | GPA, Attendance, Submission Rate, LMS logins |

🧪 Evaluation includes:
- Confusion Matrix
- Classification Report
- Feature Importance Bar Chart

---

## 🧰 Tech Stack

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for static plots
- Plotly for interactive visualizations
- Scikit-learn for ML modeling
- Jupyter Notebook

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone https://github.com/sahil007707/college-student-risk-prediction.git
cd college-student-risk-prediction

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
