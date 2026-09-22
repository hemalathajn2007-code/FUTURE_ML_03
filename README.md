# FUTURE_ML_03
# AI Resume / Candidate Screening System

## 📌 Project Overview

The **AI Resume / Candidate Screening System** is a machine learning and NLP-based project designed to help recruiters analyze and screen multiple resumes efficiently.

The system extracts relevant skills and keywords from candidate resumes, compares them with required job skills, calculates a matching score, identifies missing skills, and ranks candidates based on their relevance to the job requirements.

This project was developed as part of **Future Interns – Machine Learning Task 3 (2026)**.

---

## 🎯 Objectives

* Extract skills and keywords from resumes
* Analyze candidate resume information
* Compare candidate skills with job requirements
* Calculate a resume matching score
* Identify missing skills
* Rank candidates based on their matching score
* Help recruiters reduce manual resume screening effort

---

## 🚀 Key Features

* Resume data loading and preprocessing
* Text cleaning
* Skill extraction
* Keyword matching
* Job description comparison
* Candidate match score calculation
* Missing skill identification
* Candidate ranking
* Category-based candidate analysis
* Machine learning / NLP-based text processing

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **NLTK**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* **Jupyter Notebook**

---

## 📂 Project Structure

```text
Resume-Screening-System/
│
├── Resume_Screening_System.ipynb
├── Resume.csv
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── output.png
    └── ranking.png
```

---

## 🔄 Project Workflow

```text
Resume Dataset
      ↓
Data Loading
      ↓
Data Preprocessing
      ↓
Text Cleaning
      ↓
Skill / Keyword Extraction
      ↓
Job Requirement Comparison
      ↓
Match Score Calculation
      ↓
Missing Skills Identification
      ↓
Candidate Ranking
      ↓
Final Screening Results
```

---

## 📊 Output

The system generates a ranked list of candidates containing information such as:

* Candidate Rank
* Candidate Category
* Match Score
* Extracted Skills
* Missing Skills

Example:

```text
============================================================
Rank: 1
Category: ARTS
Match Score: 20.04 %

Skills:
leadership, c

Missing Skills:
artificial intelligence,
communication,
data science,
deep learning,
git,
machine learning,
nlp,
numpy,
pandas,
python,
scikit-learn,
sql,
tensorflow
============================================================
```

The ranking helps identify candidates whose resumes have a stronger match with the specified job requirements.

---

## 📈 Skills Matching

The system compares the skills found in each candidate's resume against the required skills.

For example:

```text
Required Skills:
Python
Machine Learning
Pandas
NumPy
SQL
NLP
Scikit-learn

Candidate Skills:
Python
Pandas
NumPy
SQL
```

The system identifies:

```text
Matched Skills:
Python
Pandas
NumPy
SQL

Missing Skills:
Machine Learning
NLP
Scikit-learn
```

---

## 💡 Benefits

* Reduces manual resume screening time
* Provides consistent skill-based comparison
* Quickly identifies missing skills
* Helps organize large numbers of candidates
* Provides an easy-to-understand candidate ranking system

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Resume-Screening-System.git
```

### 2. Open the notebook

Open:

```text
Resume_Screening_System.ipynb
```

You can run it using **Google Colab** or **Jupyter Notebook**.

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Upload the dataset

Make sure `Resume.csv` is available in the notebook environment.

### 5. Run the notebook

Execute the cells from top to bottom to reproduce the results.

---

## 📁 Dataset

The project uses a resume dataset containing candidate resume information and categories.

The dataset is used for:

* Resume text analysis
* Skill extraction
* Candidate categorization
* Resume matching
* Candidate ranking

> Dataset usage should follow the original dataset's license and terms.

---

## 🔮 Future Improvements

Future versions of the system can include:

* PDF resume upload
* Automatic resume text extraction
* Job description upload
* Advanced NLP models
* Semantic similarity using embeddings
* Interactive recruiter dashboard
* Candidate recommendation system
* Experience and education matching
* Web-based resume screening application

---

## 👩‍💻 Project Information

**Project:** Resume / Candidate Screening System
**Program:** Future Interns – Machine Learning Task 3
**Year:** 2026
**Domain:** Machine Learning / Natural Language Processing

---

## ⭐ Conclusion

The Resume / Candidate Screening System demonstrates how
