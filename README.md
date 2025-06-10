Data Science Salary Prediction Project:
 1. Objective:

This project aims to predict salary ranges for Data Science roles across different U.S. states using real-world job listing data.
It follows the complete data science lifecycle from business understanding to model deployment.

 2. Project Phases:
 
    2.1 Business Understanding
    Identify salary trends for Data Science roles in the U.S. job market.

    2.2 Data Understanding
    Explore the structure and content of the dataset collected from Glassdoor job listings.

    2.3 Data Preparation (Cleaning & Preprocessing)
    Removed missing or invalid entries (e.g., -1 salaries, "Per Hour" values).

    Cleaned and parsed salary estimates.

    Extracted min, max, and average salary fields.

    Encoded categorical features for modeling.

    2.4 Modeling
    Trained and compared several machine learning models:

    ✅ Linear Regression

    ✅ Logistic Regression

    ✅ K-Nearest Neighbors (KNN)

    ✅ Decision Tree

    ✅ Random Forest

    2.5 Evaluation
    Models were evaluated using the following metrics:

    Mean Absolute Error (MAE)

    Accuracy Score

    Confusion Matrix

    Classification Report

   2.6 Deployment
   Serialized the final trained model using pickle for reuse in applications.
   
3. Libraries Used:
    
pandas

numpy

matplotlib

seaborn

scikit-learn

pickle

4. Code Sections Overview
    4.1 Data Upload & Cleaning
    Load the dataset

    Filter invalid salary entries

    Clean and split salary fields into min, max, and average

    Prepare features for machine learning

    4.2 Feature Engineering & Modeling
    Split the dataset into training and testing sets

Implement and train the following models:

Linear Regression

Logistic Regression

K-Nearest Neighbors

Decision Tree

Random Forest

   4.3 Model Evaluation
   Measure performance using:

   Accuracy Score

   Confusion Matrix

   Classification Report

   MAE



