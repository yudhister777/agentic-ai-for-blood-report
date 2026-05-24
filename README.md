# Health Analysis AI App

## Overview

This project is an AI-powered health analysis application built using:

* Python
* Streamlit
* LangChain
* Google Gemini

The application analyzes blood reports and health-related text files using Large Language Models (LLMs) to generate insights and summaries.

---

# Features

* Upload blood report text files
* AI-powered health report analysis
* Streamlit-based interactive UI
* Environment variable support using `.env`
* Gemini API integration
* LangChain LLM orchestration

---

# Project Structure

```bash
health_analysis/
│
├── streamlit_app/
│   ├── app.py
│
├── blood_report.txt
├── blood_work.txt
├── Untitled.ipynb
├── Untitled1.ipynb
│
├── .env
├── pyproject.toml
├── README.md
└── .venv/
```

---

# Installation

## 1. Clone the Repository

```bash
git clone <your_repo_url>
cd health_analysis
```

---

## 2. Create Virtual Environment

Using uv:

```bash
uv venv
```

Activate virtual environment:

### Windows PowerShell

```powershell
.\.venv\Scripts\Activate.ps1
```

---

## 3. Install Dependencies

```bash
uv pip install streamlit langchain langchain-google-genai python-dotenv pandas numpy
```

---

# Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_google_gemini_api_key
```

---

# Run the Application

Navigate to Streamlit app folder:

```bash
cd streamlit_app
```

Run app:

```bash
python -m streamlit run app.py
```

---

# Technologies Used

* Streamlit
* LangChain
* Google Gemini
* python-dotenv
* Pandas

---

# Future Improvements

* PDF blood report upload
* Visualization dashboards
* Historical health tracking
* AI-generated recommendations
* Database integration
* Authentication system

---

# Author

Yudhister Singh
