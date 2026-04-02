# intern-retention-project
Data analysis project exploring intern retention drivers using Python, visualization, and predictive modeling.

# Intern Retention Analysis

## Overview
This project analyzes intern retention to identify the key factors that influence whether interns are retained by the company.  
The analysis combines exploratory data analysis (EDA), feature engineering, and machine learning to uncover patterns and build a predictive baseline.

---

## Business Problem
Companies often struggle to understand why some interns are retained while others leave.  
This project aims to answer:

- What factors influence intern retention?
- Are there differences across departments or majors?
- Can we predict which interns are more likely to stay?

---

## Dataset
The dataset contains information about interns, including:

- Age  
- Department  
- Major  
- Salary  
- Attendance (%)  
- Supervisor evaluation  
- Internship duration (months)  
- Retention outcome (target variable)  

---

## Tools & Technologies
- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- ipywidgets

---

## Project Structure
<img width="294" height="259" alt="image" src="https://github.com/user-attachments/assets/d146bb2c-06bd-40ee-8c56-97f1486070f7" />

---

## Workflow

### 1. Data Preparation & EDA
- Data loading and inspection
- Handling duplicates and basic cleaning
- Feature engineering:
  - Salary-to-attendance ratio
  - Evaluation flag
  - Salary categories
- Visualization of key variables

---

### 2. Exploratory Analysis
Analysis focused on:
- Retention by department
- Retention by major
- Impact of internship duration
- Salary vs retention
- Supervisor evaluation vs retention
- Age distribution

---

### 3. Machine Learning
Built and compared multiple classification models:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- Cross-validation

---

### 4. Unsupervised Learning
- K-Means clustering
- Elbow method
- Silhouette score
- PCA visualization

Used to identify different intern profiles.

---

### 5. Automation
A reusable pipeline was created to:

- Load and clean the dataset
- Generate engineered features
- Create visualizations dynamically
- Allow user-driven exploration

---

## Key Insights

- Internship duration shows a positive relationship with retention  
- Retention varies across departments, with some showing lower retention rates  
- Salary alone is not a strong predictor of retention  
- Supervisor evaluation has limited direct impact on retention  
- Retention is influenced by a combination of factors rather than a single variable  

---

## Business Recommendations

- Improve retention strategies in low-performing departments  
- Enhance internship structure and duration planning  
- Implement mentorship and feedback programs  
- Monitor high-risk intern profiles  
- Focus on long-term growth opportunities rather than salary alone  

---

## Future Improvements

- Hyperparameter tuning for models  
- Handling class imbalance  
- Feature importance analysis improvements  
- Deployment as a simple app (Streamlit or similar)  
- Power BI dashboard version  

---

## Author
Sergio Oliveira  
Aspiring Data Analyst | SQL | Power BI | Excel | Python
