# 🚀 Automated Resume Screening Tool using NLP & Machine Learning

## 📌 Overview

The **Automated Resume Screening Tool** is a Python-based project that simulates how modern **Applicant Tracking Systems (ATS)** work in real-world recruitment.

This tool automatically analyzes resumes, compares them with a given job description, and ranks candidates based on relevance using **Natural Language Processing (NLP)** and **Machine Learning techniques**.

## 🎯 Problem Statement

Recruiters often receive hundreds of resumes for a single job opening. Manually screening them is:

* Time-consuming
* Prone to human bias
* Inefficient

👉 This project solves the problem by automating resume evaluation and candidate shortlisting.

## 💡 Key Features

* 📄 Resume parsing (TXT / PDF / DOCX support)
* 🧹 Text cleaning and preprocessing
* 🔍 Keyword & skill matching
* 🤖 TF-IDF vectorization
* 📊 Cosine similarity scoring
* 🏆 Candidate ranking system
* ✅ Shortlist / Reject decision
* 📁 CSV report generation
* 📊 Excel dataset for structured analysis


## 🧰 Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * scikit-learn
  * pdfplumber
  * python-docx
  * re (Regex)


## 🏗️ Project Structure

Automated-Resume-Screening-Tool/
│
├── resumes/            # Sample resumes (TXT/PDF/DOCX)
├── data/               # Job description & skills list
├── outputs/            # Generated results (CSV)
├── images/             # Screenshots for documentation
├── docs/               # Additional notes/documentation
│
├── main.py             # Main execution script
├── requirements.txt    # Dependencies
├── README.md           # Project documentation
└── .gitignore


## ⚙️ How It Works

1. Upload resumes
2. Extract text from files
3. Clean and preprocess text
4. Convert text into vectors using **TF-IDF**
5. Compare resumes with job description using **cosine similarity**
6. Generate scores for each candidate
7. Rank and shortlist candidates
8. Export results as CSV


## ▶️ How to Run

## 1️⃣ Clone Repository


git clone https://github.com/your-username/Automated-Resume-Screening-Tool.git
cd Automated-Resume-Screening-Tool


### 2️⃣ Install Dependencies

pip install -r requirements.txt


### 3️⃣ Run the Project

python main.py


## 📊 Sample Output

| Resume             | Score | Status      |
| ------------------ | ----- | ----------- |
| resume_alice.txt   | 0.78  | Shortlisted |
| resume_diana.txt   | 0.72  | Shortlisted |
| resume_charlie.txt | 0.45  | Consider    |
| resume_eve.txt     | 0.20  | Rejected    |
| resume_bob.txt     | 0.10  | Rejected    |


## 📈 Results Summary

* Total resumes processed: **5**
* Shortlisted candidates: **2**
* Rejected candidates: **2**
* Borderline candidates: **1**

👉 **Top Candidate:** Alice Johnson
👉 **Second Best:** Diana Prince


## 📚 Learning Outcomes

* Understanding of **NLP fundamentals**
* Implementation of **TF-IDF & cosine similarity**
* Working with **unstructured and structured data**
* Real-world simulation of **ATS systems**
* Hands-on experience with **Python automation**


## 🔮 Future Improvements

* 🔍 Advanced NLP using spaCy or BERT
* 🌐 Streamlit dashboard for UI
* 📊 Visualization dashboard (Power BI)
* 📑 Resume skill extraction using Named Entity Recognition
* ☁️ Deployment as a web application



