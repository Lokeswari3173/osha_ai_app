# osha_ai_app
ML-based system to predict workplace incident outcomes using OSHA data, combining TF-IDF and LightGBM with a deployable Streamlit interface.
# 🛡️ SafeGuard AI

## AI-Powered Workplace Safety Risk Prediction & OSHA Safety Assistant

SafeGuard AI is an end-to-end AI platform that predicts workplace incident outcomes using OSHA data, provides AI-powered safety explanations, generates downloadable reports, and assists users with OSHA-related queries through an intelligent chatbot.

---

# 📌 Problem Statement

Workplace accidents remain a major challenge across industries due to delayed risk assessment, inconsistent reporting, and limited access to actionable safety insights. Traditional methods often rely on manual investigation after an incident has already occurred.

SafeGuard AI addresses these challenges by combining Machine Learning and Generative AI to predict workplace incident outcomes, explain risks, recommend preventive measures, and support OSHA compliance.

---

# 🎯 Objectives

- Predict workplace incident outcomes using OSHA data.
- Provide AI-powered explanations for predicted risks.
- Generate detailed safety reports.
- Offer an OSHA Safety Assistant chatbot.
- Support multilingual safety assistance.
- Help organizations improve workplace safety.

---

# 🧠 System Overview

The platform combines:

- LightGBM Machine Learning Model
- TF-IDF Text Processing
- Google Gemini AI
- Streamlit Web Application

Users enter workplace, job, and incident details. The system predicts the likely incident outcome, generates AI explanations, recommends preventive actions, and allows downloading reports.

---

# 🔁 High-Level Workflow

Login → Enter Company Information → Enter Job Details → Enter Incident Details → Data Preprocessing → TF-IDF Encoding → LightGBM Prediction → AI Explanation (Gemini) → Download Report → OSHA Safety Assistant

---

# 🏗️ System Architecture

```text
User Input
    │
    ▼
Data Cleaning & Feature Engineering
    │
    ▼
TF-IDF + Feature Encoding
    │
    ▼
LightGBM Model
    │
    ▼
Prediction
    │
    ▼
Google Gemini AI
    │
    ▼
Safety Explanation & Report
    │
    ▼
Streamlit Dashboard
```

---

# ⚙️ Tech Stack

| Layer | Technology |
|--------|------------|
| Programming Language | Python |
| Machine Learning | LightGBM |
| NLP | TF-IDF |
| Generative AI | Google Gemini |
| Frontend | Streamlit |
| Data Processing | Pandas, NumPy |
| Model Storage | Pickle |
| Version Control | Git & GitHub |

---

# ✨ Key Features

- Workplace Risk Prediction
- OSHA Incident Outcome Prediction
- AI Safety Explanation
- Root Cause Analysis
- Risk Factors Identification
- Prevention Recommendations
- Worker Treatment Suggestions
- Long-term Safety Measures
- AI Safety Assistant Chatbot
- Multilingual Support
- PDF & Report Download
- Secure Login System

---

# 📊 Prediction Output

The application provides:

- Predicted Incident Outcome
- Confidence Score
- AI Safety Explanation
- Root Cause
- Risk Factors
- Recurrence Analysis
- Prevention & Solutions
- Worker Treatment
- Long-term Safety Measures
- Downloadable Report

---

# 🚀 Getting Started

## Prerequisites

- Python 3.10+
- pip

## Installation

```bash
git clone https://github.com/Lokeswari3173/osha_ai_app.git
cd osha_ai_app
pip install -r requirements.txt
```

## Run

```bash
streamlit run app.py
```

Open:

http://localhost:8501

---

# 📁 Project Structure

```text
osha_ai_app/
│
├── app.py
├── train.py
├── preprocessing.py
├── data_cleaning.py
├── feature_engineering.py
├── encoding.py
├── geo_features.py
├── text_processing.py
├── genai_helper.py
├── final_model.pkl
├── users.json
├── models/
├── requirements.txt
├── README.md
└── screenshots/
```

---

# 📈 Results & Impact

- Predicts workplace incident outcomes using OSHA data.
- Generates AI-powered workplace safety insights.
- Improves workplace risk awareness.
- Supports proactive accident prevention.
- Assists organizations with OSHA compliance.
- Reduces manual safety assessment effort.

---

# 🔮 Future Scope

- Real-time IoT integration
- CCTV-based safety monitoring
- Voice-enabled AI assistant
- Mobile application
- Cloud deployment
- Dashboard analytics
- Enterprise integration
- Advanced multilingual support

---

# 🏭 Use Cases

- Construction
- Manufacturing
- Healthcare
- Logistics
- Energy
- Government Organizations

---

# 👩‍💻 Author

**Mangasamudram Lokeswari**

Data Science | Machine Learning | Generative AI

GitHub: https://github.com/Lokeswari3173

---

# ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork it
- 📢 Share it

---

# 📜 License

This project is licensed under the MIT License.

---

# 📸 Application Screenshots


- login.png
- home.png
- risk_predictor.png
- job_information.png
- incident_details.png
- prediction_result.png
- ai_explanation.png
- safety_report.png
- ai_chatbot.png
- download_report.png

Then use:

```markdown
## Login
(<img width="1600" height="768" alt="image" src="https://github.com/user-attachments/assets/f34fd3c2-30ff-42c7-9d72-623a10befec0" />
)

## Home Dashboard
![Home](screenshots/home.png)

## Risk Predictor
![Risk Predictor](screenshots/risk_predictor.png)

## Job Information
![Job Information](screenshots/job_information.png)

## Incident Details
![Incident Details](screenshots/incident_details.png)

## Prediction Result
![Prediction Result](screenshots/prediction_result.png)

## AI Safety Explanation
![AI Explanation](screenshots/ai_explanation.png)

## Safety Report
![Safety Report](screenshots/safety_report.png)

## AI Safety Assistant
![AI Chatbot](screenshots/ai_chatbot.png)

## Download Report
![Download Report](screenshots/download_report.png)
```
