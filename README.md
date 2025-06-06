# 📝 ATS Resume Checker

![License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/built%20with-Streamlit-orange)
![Gemini API](https://img.shields.io/badge/Google-Gemini%20API-blue)

## 🚀 About the Project

**ATS Resume Checker** is an AI-powered web application that helps job seekers optimize their resumes to pass through **Applicant Tracking Systems (ATS)**.

It uses **Google Gemini AI** to analyze your resume and job description, then provides:

- ✅ A match **score**
- 🔍 **Missing keywords/skills**
- 💡 Actionable **improvement suggestions**
- 📄 Support for **PDF** and **TXT** resume formats

> Built with Python, Streamlit, and Google Gemini API.

---

## 📸 Demo

![ATS Resume Checker UI](demo.gif) <br>
live app: https://rishabh9559-resume-ats-checker-main-0u8tsv.streamlit.app/

---

## 🧠 Features

- Upload your resume as **PDF** or **TXT**
- Paste any **job description**
- One-click AI analysis with a clean Google-style UI
- Get insights on:
  - Match Score (0–100)
  - Missing tools, skills, and keywords
  - Role alignment analysis
  - Clear and personalized suggestions to improve your resume

---

## 🛠️ Technologies Used

- [Python 3.8+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Google Gemini API (generative AI)](https://ai.google.dev/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [dotenv](https://pypi.org/project/python-dotenv/)

---

## ⚙️ Setup Instructions

### 🔐 Prerequisites
- Python 3.8+
- Google Gemini API key ([get it here](https://makersuite.google.com/app))
- UV Environment

### Add your API key
- Create a .env file in the root folder:
   <br> GEMINI_API_KEY=your_google_gemini_api_key
- Run the app
    <br> streamlit run app.py
## 📂 Project Structure
ats-resume-checker<br>
├── app.py                 # Main Streamlit app <br>
├── .env                   # Environment variables (Gemini API Key) <br>
├── requirements.txt       # Python dependencies <br>
└── README.md              # GitHub ReadMe file <br>


## 🧑‍💻 Developer: Rishabh Kushwaha
