# LINKEDAGENT - AI POWERED RESUME MAKER AND JOB APPLIER 


## 🚀 Project Overview

This project leverages **Large Language Models (LLMs)** and **agentic AI** to automate and optimize the job application pipeline. It supports users through two major components:

1. **ATS-Friendly Resume Generation**
2. **Automated LinkedIn Job Application Engine**

By intelligently integrating user data, LLMs, and real-time job scraping, this system aims to **minimize manual effort**, **enhance resume targeting**, and **maximize job match accuracy**—all while increasing the likelihood of securing interviews.

---

## ✨ Features

### 📄 ATS-Friendly Resume Generator (Module 1)
- Collects detailed user inputs:
  - Email and password (secured)
  - Preferred job type (remote/on-site/hybrid)
  - Location, company, and position preferences
  - Skills, experience, language proficiency
  - Areas of interest, notice period, salary expectations
- Uses `Qwen-32B Instruct` LLM to:
  - Generate a professional, keyword-optimized resume
  - Ensure ATS-compliant formatting (clean, minimal, structured)
  - Use role-relevant terminology and industry keywords
- Preview and download options available (PDF/Text)

### 🤖 LinkedIn Job Application Automation Engine (Module 2)
- Scrapes real-time job listings using custom filters (title, location, experience)
- Uses a **fine-tuned Mistral model** to:
  - Parse and analyze job descriptions
  - Compare them semantically with the generated resume
  - Compute a **match percentage**
- Auto-applies to jobs exceeding a match threshold:
  - Simulates user interactions using Selenium
  - Fills out forms and clicks buttons autonomously
- Logs:
  - Timestamped job applications
  - Applied job titles, companies, and match scores

---

## 🛠 Tech Stack

| Component        | Technology                 |
|------------------|----------------------------|
| Resume Generation | Qwen-32B Instruct (LLM)    |
| Job Matching     | Fine-tuned Mistral Model   |
| Scraping         | BeautifulSoup, Requests    |
| Automation       | Selenium                   |
| Backend          | Python (FastAPI/Flask)     |
| Frontend (Optional) | React / Streamlit       |
| Resume Export    | WeasyPrint / PDFKit        |

---

## 📦 Installation
```bash
# 1. Clone the repository
git clone git@github.com:VarnasriKumaran/Linkedagent.git

# 2. Create virtual environment
python -m venv venv

# 3. Install dependencies
pip install -r requirements.txt

# 4. Setup environment variables
cp .env.example .env
# Fill in your LinkedIn credentials, API keys, etc.

# 5. Run the app
python main.py


![image](https://github.com/user-attachments/assets/8cd4d9f2-f1b8-415a-a1b1-da03a1a6348e)
![image](https://github.com/user-attachments/assets/a1732060-2640-4b0f-a631-c2a19e33b9cc)
![image](https://github.com/user-attachments/assets/d5be5244-32b0-4c27-bcf7-f4ea1d26881d)
![image](https://github.com/user-attachments/assets/20e3297e-1b6d-4d7b-9698-a20e347c5d60)
![image](https://github.com/user-attachments/assets/a65aecbc-088c-4ddc-a448-77d2f9ba93f3)




