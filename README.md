# SynapseCV
# 🚀 AI Resume Analyzer & ATS Optimizer (Groq Powered)

An AI-powered Resume Analyzer that evaluates resumes against job descriptions and provides:

* 📊 ATS Score
* 🔍 Keyword Match Analysis
* 💡 Improvement Suggestions
* 📄 Downloadable ATS Report (PDF)
* ✉️ AI-generated Cover Letter

Built using **Streamlit + Groq LLM API**

---

## 🧠 Features

### ✅ Resume Upload

* Upload resume in PDF format
* Automatic text extraction

### ✅ Job Description Input

* Paste any job description
* AI compares resume with JD

### ✅ Detailed ATS Analysis

* ATS Score (0–100)
* Missing Keywords
* Strength Areas
* Weak Areas
* Suggestions for Improvement

### ✅ Cover Letter Generator

* Generates tailored cover letter using LLM

### ✅ Download ATS Report

* Generates downloadable PDF report

---

## 🏗️ Tech Stack

* Python
* Streamlit
* Groq API
* PyPDF2
* ReportLab

---

## ⚙️ Installation

### 1️⃣ Clone Repository

git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer

### 2️⃣ Install Dependencies

pip install streamlit groq PyPDF2 reportlab python-dotenv

---

## 🔑 Setup Groq API Key

### Option 1 – Using .env (Recommended)

Create a `.env` file:

GROQ_API_KEY=your_actual_groq_api_key_here

### Option 2 – Directly in Code

api_key = "your_actual_groq_api_key_here"

---

## ▶️ Run the App

streamlit run app.py

Open browser:
http://localhost:8501

---

## 📁 Project Structure

app.py
README.md
requirements.txt
.env

---

## 🛠️ Common Errors & Fixes

### ❌ missing ScriptRunContext

Run using:
streamlit run app.py

Do NOT run inside Jupyter Notebook.

---

### ❌ GroqError: api_key must be set

* Ensure API key is correct
* Ensure .env file exists
* Ensure load_dotenv() is used

---

## 📈 Future Improvements

*
