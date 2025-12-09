# Predict Candidate Fit Score
# Analyzation-of-candidate-profilies-
Creating a Python-based solution that analyzes candidate profiles and job descriptions to generate a compatibility score (0-100%).
<br>
#...AI-Based Candidate Fit Score — Resume vs Job Role Matching....
Built by Harshith S — Python & Machine Learning Developer(FRESHER)
<br>
Why I built this project?<br>
A Recruiter asked me to buil a Predict Candidate Fit Score model which helps recruiter.
Recruiters spend hours reading resumes. 
Candidates apply to jobs even if they don’t match the requirements.Both sides lose time.
This helps in filtering of resumes while recruiting.
<br>
||Predict Candidate Fit Score||
<br>
Takes Resume text.Takes job description.uses NLP & Machine learing to understand them.Returns to compatibility score.
<br>
This helps "HR" to shortlist the resumes.And also help candidates to understand where they stand.
<br>
PROJECT STRUCTURE  
<br>
candidate_fit_project/
<br>
│── main.py
<br>
│── sample_data.csv
<br>
│── model.pkl (after training)
<br>
│── vectorizer.pkl (after training)
<br>
│── README.md
<br>
How It Works
<br>
Data Processing
<br>
Loads example job description & candidate text.
<br>
Feature Engineering
<br>
Converts text into numeric features using TF-IDF.
<br>
Model Training
A Linear Regression model learns how text patterns relate to match scores.
<br>
Prediction
The predict() function evaluates new candidate + job text and produces a score.
<br>
How to Run the Project
<br>
Create a Virtual Environment<br>python3 -m venv venv
source venv/bin/activate
<br>Install Dependencies<br>
pip install pandas scikit-learn joblib

