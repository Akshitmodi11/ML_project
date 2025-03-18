## End to End machine learning project
# Student Exam Performance Prediction - ML Project

## Table of Contents
1. [Overview](#overview)
2. [Project Objectives](#project-objectives)
3. [Technologies and Tools Used](#technologies-and-tools-used)
4. [Dataset Description](#dataset-description)
5. [Machine Learning Pipeline](#machine-learning-pipeline)
6. [Web Application](#web-application)
7. [Installation](#installation)
8. [Usage](#usage)
9. [Project Structure](#project-structure)
10. [Results](#results)
11. [Future Work](#future-work)
12. [Contributors](#contributors)
13. [License](#license)

## Overview
This project predicts students' performance on exams based on demographic, social, and educational factors using machine learning techniques. The project integrates model training, testing, and deployment to create a fully functional ML system accessible via a Flask web application.

## Project Objectives
- **Predict student performance:** Accurately forecast exam scores using a variety of factors.
- **Identify influential features:** Discover how gender, ethnicity, parental education, and test prep correlate with scores.
- **Deploy as a web app:** Provide a user-friendly interface for real-time predictions.

## Technologies and Tools Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, CatBoost
- **Web Framework**: Flask
- **Environment**: Jupyter Notebooks
- **Deployment**: Flask for local hosting, HTML/CSS for UI

## Dataset Description
The dataset includes the following columns:
- **Gender**: Male/Female
- **Ethnicity**: Group identifiers (A, B, C, D, E)
- **Parental Education Level**: Highest education level of a student's parent(s)
- **Lunch Type**: Free/reduced or standard
- **Test Preparation**: Whether the student completed test prep
- **Scores**: Reading and writing scores (target is the predicted math score)

## Machine Learning Pipeline
1. **Data Preprocessing**: Cleans, encodes categorical features, and scales numeric data.
2. **Feature Engineering**: Derives new features if necessary.
3. **Model Selection and Training**: Experiments with several algorithms (e.g., CatBoost, Random Forest).
4. **Evaluation**: Uses metrics like RMSE and accuracy to evaluate model performance.
5. **Hyperparameter Tuning**: Uses cross-validation to optimize model accuracy.

## Web Application
The Flask-based web app allows users to:
- Input data on a student’s demographics and academic background.
- Obtain predictions on math scores based on input features.
- Display results interactively for easy interpretation. 

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Akshitmodi11/ML_project.git
   cd ML_project
