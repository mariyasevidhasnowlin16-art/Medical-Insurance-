Medical Insurance Cost Analysis and Prediction System
Abstract
Health insurance companies manage large amounts of customer information, including age, gender, BMI, number of children, smoking habits, region, and insurance charges. Estimating insurance premiums manually is difficult and may lead to inaccurate premium calculations, poor risk assessment, and inefficient decision-making. This project aims to analyze medical insurance data using Exploratory Data Analysis (EDA) and Machine Learning techniques. Linear Regression, Multiple Linear Regression, and Logistic Regression models are used to predict insurance costs and classify customers based on risk levels. Interactive visualizations and dashboards help insurance providers understand customer behavior and make data-driven decisions.

Introduction
Medical insurance plays a vital role in protecting individuals from healthcare expenses. Insurance companies must accurately estimate premiums to maintain profitability while ensuring fairness to customers. Various factors such as age, BMI, smoking status, and family size significantly influence medical costs.

This project uses the Medical Cost Personal Dataset from Kaggle to analyze customer information and predict insurance charges. The system automates insurance cost estimation and risk classification using machine learning techniques.

Problem Statement
Health insurance companies collect large volumes of customer data, including age, gender, body mass index (BMI), number of children, smoking habits, region, and insurance charges. Analyzing this information manually to estimate insurance costs and identify high-risk customers is difficult, time-consuming, and prone to errors.

Incorrect premium estimation can result in:

Financial losses for insurance companies
Unfair premium charges for customers
Poor risk assessment and policy planning
Inefficient decision-making in the insurance sector
Therefore, an automated system is required to analyze customer information, identify factors affecting insurance costs, and predict future insurance charges.

Objectives
Perform Exploratory Data Analysis (EDA)
Analyze factors affecting insurance charges
Build Linear Regression models for prediction
Build Multiple Linear Regression models using multiple features
Classify customers using Logistic Regression
Identify high-risk customers
Create interactive dashboards for business insights
Support data-driven premium estimation
Features:

age : Age of customer
sex : Gender
bmi : Body Mass Index
children : Number of dependents
smoker : Smoking status
region : Residential region
charges : Medical insurance charges
Number of Records: 1338

Number of Features: 7

Methodology
Phase 1: Data Collection
The insurance dataset is loaded from Kaggle. Dataset structure and features are examined to understand customer demographics and insurance information.

Phase 2: Data Cleaning and Preprocessing
The following preprocessing operations are performed:

Missing value detection
Duplicate removal
Data type verification
Label Encoding of categorical variables
Feature preparation for machine learning
Phase 3: Exploratory Data Analysis
EDA helps understand customer characteristics and insurance charge patterns.

Analysis includes:

Average age
Average BMI
Average insurance charges
Average number of children
Group-based comparisons:

Smokers vs Non-Smokers
Male vs Female
Different Regions
Different BMI Categories
Phase 4: Visualization
Several visualizations are created:

Histograms
<img width="661" height="432" alt="image" src="https://github.com/user-attachments/assets/729c7158-db0d-4802-9a72-46b6b292f9cb" />
<img width="658" height="435" alt="image" src="https://github.com/user-attachments/assets/9c3994a7-1b2d-47c9-a321-ac58fafab3f0" />
<img width="675" height="435" alt="image" src="https://github.com/user-attachments/assets/d94b893a-03e3-475b-aca9-154a442b1d44" />
<img width="697" height="436" alt="image" src="https://github.com/user-attachments/assets/7440de2f-467d-4a70-9ab0-459d0a336d01" />
<img width="708" height="437" alt="image" src="https://github.com/user-attachments/assets/69bbc230-f129-4f77-bab9-aaaa5887b4cf" />
<img width="707" height="432" alt="image" src="https://github.com/user-attachments/assets/b85afb83-16a2-4742-a45e-ef6c58e9850d" />
<img width="692" height="438" alt="image" src="https://github.com/user-attachments/assets/15d6d654-e3a0-453e-9591-15a369a80c7b" />
<img width="735" height="482" alt="image" src="https://github.com/user-attachments/assets/d7270e4e-a5f1-4262-b125-b3107b131ff8" />
<img width="511" height="463" alt="image" src="https://github.com/user-attachments/assets/38a11a85-9820-4ace-a955-eb95fc9fef98" />









