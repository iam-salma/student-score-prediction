## 🧠 Student Performance Prediction
This project is an end-to-end machine learning application that predicts a student's math score based on various performance-related inputs. It includes a trained model, a Flask web interface, and deployment setup using AWS (ECR, ECS, EC2, or GitHub Actions).

# 🔍 Problem Statement
The goal is to predict the math score of a student using features such as:
Gender
Race/Ethnicity
Parental Level of Education
Lunch type
Test Preparation Course
Reading Score
Writing Score

# 🚀 Tech Stack
Python
Flask for the web framework
Scikit-learn for model training
Docker for containerization
AWS ECS + ECR for deployment
GitHub Actions for CI/CD

## 🚀 Features
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Model Training & Evaluation  
- Model Packaging  
- CI/CD Pipeline with GitHub Actions  
- Dockerized & Deployed on AWS ECS  

Install dependencies: pip install -r requirements.txt
Run the Flask app: python app.py


🧠 ML Model Info
Algorithm: RandomForestRegressor
Evaluation: Trained on student dataset, evaluated using MAE & R² Score
Target: math_score

![Screenshot 2025-06-05 002843](https://github.com/user-attachments/assets/54296c5b-0baa-4c3b-aaae-4f72b3b79412)
