📊 Diabetes Risk Analysis & Prediction System

📌 Project Overview

The Diabetes Risk Analysis & Prediction System is a data analytics and machine learning project developed to analyze patient health data and predict the likelihood of diabetes. The project combines data preprocessing, exploratory data analysis (EDA), machine learning modeling, and business intelligence visualization to provide meaningful healthcare insights.

The objective of this project is to identify important health factors associated with diabetes and build predictive models that can assist in early risk assessment. The project demonstrates a complete data analytics workflow, from raw data processing to interactive dashboard creation.

🎯 Objectives

Analyze diabetes-related health data.
Identify factors that contribute to diabetes risk.
Perform data cleaning and preprocessing.
Explore patterns and relationships through visualizations.
Build machine learning models for diabetes prediction.
Evaluate model performance using standard metrics.
Create an interactive Power BI dashboard for data-driven insights.

📂 Dataset

The project uses the Pima Indians Diabetes Dataset, a widely used healthcare dataset for machine learning and predictive analytics.

Dataset Features

Feature	Description
Pregnancies	Number of pregnancies
Glucose	Plasma glucose concentration
BloodPressure	Diastolic blood pressure
SkinThickness	Triceps skin fold thickness
Insulin	2-Hour serum insulin
BMI	Body Mass Index
DiabetesPedigreeFunction	Diabetes hereditary risk score
Age	Age of patient
Outcome	Diabetes status (0 = No, 1 = Yes)
🛠 Technologies Used
Programming & Analysis
Python
Jupyter Notebook
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Visualization
Power BI
Version Control
Git
GitHub

🔄 Project Workflow

1. Data Loading
   
The dataset was imported into Python using Pandas and examined through:

Head()
Info()
Describe()
Shape Analysis

This step provided an understanding of the dataset structure and feature distribution.

2. Data Cleaning

Several preprocessing techniques were applied:

Missing Value Handling

Missing and invalid values were identified and replaced using median values.

Duplicate Removal

Duplicate records were removed to improve data quality.

Data Validation

Medical attributes containing invalid zero values were corrected.

Examples include:

Glucose
Blood Pressure
Insulin
BMI
3. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to identify patterns and relationships within the dataset.

Visualizations Created
Age vs Diabetes Analysis

Examined the relationship between patient age and diabetes occurrence.

BMI Distribution

Analyzed obesity trends among patients.

Glucose Level Analysis

Investigated the impact of glucose levels on diabetes risk.

Correlation Heatmap

Visualized relationships among all features.

Outcome Distribution

Compared diabetic and non-diabetic patient counts.

4. Feature Selection

Input features and target variables were separated:

Features (X)
Pregnancies
Glucose
BloodPressure
SkinThickness
Insulin
BMI
DiabetesPedigreeFunction
Age
Target Variable (Y)
Outcome
5. Machine Learning Model Development

Two machine learning classification models were developed and evaluated.

Logistic Regression

A statistical classification model used as a baseline for diabetes prediction.

Random Forest Classifier

An ensemble learning algorithm used to improve prediction performance.

6. Model Evaluation

Model performance was evaluated using:

Accuracy Score

Measures overall prediction accuracy.

Confusion Matrix

Provides detailed information about:

True Positives
True Negatives
False Positives
False Negatives
Classification Report

Includes:

Precision
Recall
F1-Score
📈 Results
Logistic Regression
Accuracy: 75.32%
Demonstrated strong performance for binary classification.
Random Forest
Accuracy: 73.38%
Produced competitive prediction results with balanced performance.
Key Findings
Glucose level is one of the strongest indicators of diabetes.
Higher BMI values are associated with increased diabetes risk.
Age contributes significantly to diabetes occurrence.
Feature correlations help identify critical health factors.
📊 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize healthcare insights and support data-driven decision-making.

Dashboard Features
KPI Cards
Total Patients
Diabetic Patients
Non-Diabetic Patients
Average Age
Average BMI
Interactive Charts
Age vs Diabetes Analysis
BMI Distribution
Glucose Impact Analysis
Diabetes Outcome Distribution
Correlation Insights
Filters (Slicers)
Age
BMI
Outcome
🚀 Future Improvements

Potential enhancements for future versions include:

Hyperparameter tuning
Feature engineering
Advanced ensemble models
Streamlit web application deployment
Real-time patient prediction interface
Integration with healthcare databases
📁 Repository Structure
Diabetes-Risk-Analysis-Prediction/
│
├── data/
│   └── diabetes.csv
│
├── notebooks/
│   └── diabetes_analysis.ipynb
│
├── powerbi/
│   └── diabetes_dashboard.pbix
│
├── screenshots/
│   └── dashboard_preview.png
│
├── requirements.txt
│
└── README.md
📚 Learning Outcomes

Through this project, I gained practical experience in:

Data Cleaning and Preprocessing
Exploratory Data Analysis
Data Visualization
Machine Learning Classification
Model Evaluation
Business Intelligence Reporting
Power BI Dashboard Development
Git and GitHub Project Management
👩‍💻 Author
Samavia Naeem
Aspiring Data Analyst | AI & Machine Learning Enthusiast | Python | SQL | Power BI | Flutter Developer
