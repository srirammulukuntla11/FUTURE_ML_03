📄 Resume Screening & Candidate Ranking System (Task 3)

📌 Project Overview

This project is a Machine Learning–based Resume Screening System that automatically analyzes resumes and ranks candidates based on how well they match a given job role.
It also identifies missing skills (skill gaps) for each candidate.

This helps recruiters and HR teams save time by quickly shortlisting suitable candidates.

🎯 Objectives

Read and process resume text data

Clean and preprocess resume content

Extract relevant skills using NLP

Compare resumes with required job skills

Rank candidates based on role match

Identify missing skills (skill gap analysis)

🗂️ Dataset Used

Resume Dataset (Kaggle)

File: Resume.csv

Contains resume text and job categories

Used to extract skills and analyze candidate profiles

🛠️ Tools & Technologies Used

Python – core programming language

Jupyter Notebook – development & experimentation

Pandas – data handling

NumPy – numerical operations

NLTK – text preprocessing (stopwords, cleaning)

Scikit-learn – TF-IDF vectorization & similarity scoring

VS Code – development environment

GitHub – version control & project sharing

📂 Project Folder Structure
FUTURE_ML_03/
│
├── data/
│   └── Resume.csv
│
├── notebooks/
│   └── resume_screening.ipynb
│
├── outputs/
│   ├── ranked_resumes.csv
│   └── skill_gap_analysis.csv
│
├── README.md
├── requirements.txt
└── LICENSE

🔍 Key Features Implemented

Resume text cleaning and preprocessing

Skill extraction using keyword matching

Resume-to-job similarity scoring

Candidate ranking based on match score

Skill gap identification (missing skills per candidate)

Results saved as CSV files for easy analysis

📊 Output Files

ranked_resumes.csv → Ranked list of candidates with match scores

skill_gap_analysis.csv → Present and missing skills for each candidate

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/srirammulukuntla11/FUTURE_ML_03.git


Install dependencies:

pip install -r requirements.txt


Open the notebook:

notebooks/resume_screening.ipynb


Run all cells step by step.

✅ Final Outcome

A working resume screening and ranking system that:

Scores resumes

Ranks candidates

Highlights missing skills
All results are clearly visible and exportable.

