# Automated-Resume-Relevance-Checker
AI-powered Automated Resume Relevance Check System for evaluating resumes against job descriptions with hybrid scoring, semantic analysis, and a web dashboard.

## 🔍 What is this?

This system automates resume evaluation so placement teams can select students faster and more consistently. Students upload resumes, placement teams upload or select job descriptions, and the system scores each resume per JD — giving a final relevance score, missing skills, and personalized feedback.  

## ✅ Features

| Feature                                   | Description                                                                 |
|-------------------------------------------|-----------------------------------------------------------------------------|
| 📂 Resume Upload                          | Accepts resumes in **PDF/DOCX** format uploaded at runtime                  |
| 📄 Job Description Upload                 | Placement team uploads/selects JD files from the `jd/` folder               |
| 🔍 Resume Parsing                         | Extracts raw text, normalizes sections, removes headers/footers             |
| 📝 JD Parsing                             | Extracts role title, must-have skills, good-to-have skills, qualifications  |
| ⚡ Hard Match                             | Keyword/skill/education matching (exact + fuzzy matches)                    |
| 🤖 Semantic Match                         | Embedding-based similarity + optional LLM reasoning                         |
| 📊 Hybrid Scoring                         | Combines hard + semantic match with weighted scoring formula                |
| 📈 Output Generation                      | Generates Relevance Score (0-100), Missing Skills, Verdict (High/Med/Low)   |
| 💡 Suggestions                           | Provides improvement tips for missing skills, certifications, projects      |
| 🗄️ Storage & Database                    | Stores results in **SQLite** for future access                              |
| 🔎 Dashboard Filtering                    | Placement team can filter/search by job role, score, location, verdict      |
| 🌐 Web Application                        | Streamlit dashboard for uploading JDs/resumes and viewing results           |
| 📥 Export Results                         | Download CSV reports for each JD separately                                 |

## 🚀 Getting Started

Follow these steps to set up and run the Automated Resume Relevance Check System on your local machine.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YourUsername/Automated-Resume-Relevance-Check.git
cd Automated-Resume-Relevance-Check
```
### 2️⃣ Create a Virtual Environment (Recommended)
```bash
python -m venv venv
```
Activate it:
#### Windows:
```bash
venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

