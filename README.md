Project Overview

This project is a comprehensive AI-powered tool for students and job seekers, combining placement prediction, ATS checking, and AI-based resume building. It leverages machine learning and intelligent heuristics to improve placement chances and optimize resumes for real-world recruitment scenarios.

Modules
1️⃣ Placement Prediction

Uses Random Forest Classifier to predict student placement (0 or 1)

Features: CGPA, IQ, Gender, Internship, BranchFactor

Hyperparameter-tuned for 96% accuracy

Handles class imbalance effectively

Provides placement probability for each student

Includes branch-wise visualizations and insights

2️⃣ ATS (Applicant Tracking System) Checker

Analyzes resumes against job-specific criteria

Highlights keywords, formatting, and content issues

Scores resumes for ATS compatibility

3️⃣ AI Resume Builder

Generates professional resumes using AI templates

Optimizes for placement predictions and ATS friendliness

Allows users to customize sections while keeping AI suggestions

Technologies Used

Python (Pandas, NumPy, Scikit-learn, Joblib)

NLP & AI for resume analysis and generation

Matplotlib / Seaborn for visualizations

Flask / Streamlit (optional) for app interface
