
# 🎓 Student Dropout Risk Analysis - EDA

This project presents an Exploratory Data Analysis (EDA) of a synthetic dataset focused on student performance and habits to identify key factors contributing to dropout risk. The analysis is designed to help educators and institutions recognize early warning signs and take proactive measures to support students.

---

## 📌 Objective

To explore academic, behavioral, and demographic variables that correlate with student dropout risk and provide visual and statistical insights that can guide early interventions.

---

## 🧹 Data Cleaning

- Replaced empty strings with `NaN` and verified missing data
- Dropped duplicate records
- Removed the `student_id` column as it holds no predictive value
- Ensured dataset integrity before analysis

---

## 📊 Visualizations

EDA was conducted using Python libraries like **Pandas**, **Seaborn**, and **Matplotlib**, including:

- **Histogram and KDE**: Exam score distribution
- **Countplot**: Dropout risk class distribution
- **Barplots**: Mean values of numerical features grouped by dropout risk and gender
- **Countplots**: Categorical feature distributions with dropout risk overlay
- **Boxplot**: Exam scores grouped by dropout risk
- **Correlation Plot**: Feature correlation with dropout risk (encoded numerically)

---

## 🔍 Key Findings

### 🧠 Academic and Study Habits
- **Exam score** is the most influential factor: lower scores strongly correlate with dropout.
- **Study hours** and **attendance rate** show a clear protective effect — students investing more time are less likely to drop out.
- **Parental involvement** improves outcomes; students with involved parents are more academically stable.

### 🩺 Health & Wellness
- Students reporting **health issues**, **high stress**, and **poor sleep** show significantly higher dropout risk.
- **Mental health** and **exam anxiety** are important to monitor as emotional well-being impacts retention.

### 🕒 Time & Motivation
- Poor **time management** and **low motivation levels** are strongly associated with higher risk.
- **Screen time** and **social media hours** slightly increase risk, indicating possible distractions.

### 🌐 Categorical Features
- Students with **part-time jobs** ,**poor diet quality** and **lower parental education levels** are more vulnerable.
- Lack of **extracurricular participation** also increases dropout likelihood.

### ⚖️ Class Imbalance
- Majority of students are not at risk, creating a **class imbalance** that should be addressed when building predictive models.

---

## 📁 Files Included

- `task2.py` – Python script containing data cleaning and EDA
- `enhanced_student_dataset.csv` – Input dataset (synthetic)
- `README.md` – Project summary and documentation

---

## 📚 Dataset Source

This is a **synthetic dataset** created for educational and analytical practice. It is not based on real student data.

---

## 🛠️ Tools Used

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Google Colab 

---

Feel free to explore or expand this analysis into a predictive modeling project!
