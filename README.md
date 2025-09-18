# 👋 Hi, I’m Simon — MBBS | MSc Computer Science with Artificial Intelligence

<!-- ### Core Tech -->
![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend%20API-green)
![Uvicorn](https://img.shields.io/badge/Uvicorn-ASGI%20Server-lightgrey)
![Pydantic](https://img.shields.io/badge/Pydantic-Data%20Validation-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)

<!-- ### Testing & Deployment -->
![Pytest](https://img.shields.io/badge/Pytest-Testing-yellow)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)
![Render](https://img.shields.io/badge/Deployment-Render-purple)

<!-- ### Data & AI -->
![AI/ML](https://img.shields.io/badge/AI%2FML-TCN%2C%20LightGBM-orange)
![Data Viz](https://img.shields.io/badge/Data%20Viz-Matplotlib%20%26%20Seaborn-blueviolet)
![Data Storage](https://img.shields.io/badge/Data-CSV%20%26%20TimeSeries-teal)

<!-- ### Clinical & Digital Health -->
![MBBS](https://img.shields.io/badge/MBBS-Clinical%20Expert-yellowgreen)
![Clinical Scoring](https://img.shields.io/badge/NEWS2-Early%20Warning%20System-red)
![Digital Health](https://img.shields.io/badge/Digital%20Health-Data%20Driven-green)
![EHR & FHIR](https://img.shields.io/badge/EHR%20%26%20FHIR-Standards%20Compliant-lightblue)
![GDPR](https://img.shields.io/badge/GDPR-Privacy%20Compliant-yellow)

<!-- ### Version Control & Tools-->
![Git](https://img.shields.io/badge/Git-Version%20Control-informational)
![CLI Tools](https://img.shields.io/badge/CLI-Command%20Line%20Interfaces-ff69b4)
![Portfolio](https://img.shields.io/badge/Portfolio-Clinician%20Technologist-brightgreen)

***Clinically-informed, technically rigorous, and designed to deliver digital health solutions that only a clinician could envision*** 

[LinkedIn](https://www.linkedin.com/in/simonyip22/) | [GitHub](https://github.com/SimonYip22)

---

## 👤 About Me

***Bridging medicine & AI to deliver clinically-informed digital health solutions***

I am a **clinically trained medical professional (MBBS)** transitioning into healthcare technology through an **MSc in Computer Science with AI**. I specialise in **clinically-informed software development**, combining Python, AI/ML, NLP, and data analytics to build tools that are **technically robust and medically interpretable**.

My goal is to develop, validate, and deploy intelligent healthcare solutions that **improve patient outcomes, streamline clinical workflows, and integrate predictive decision support** into real-world clinical settings. 

My focus areas include **data science, digital health product management, AI/ML in medicine, and health informatics**.

---

## 💡⚙️ Technical Skills

- 💾 **Programming & Software Engineering:** Python, OOP, SQL/NoSQL, Git/GitHub, Testing, Modular Design, CI/CD  
- 🤖 **Artificial Intelligence & Machine Learning:** Rule-based AI, Bayesian inference, NLP, TensorFlow, PyTorch, Scikit-learn  
- 📊 **Data Handling & Visualisation:** Pandas, Matplotlib, Seaborn, ASCII charts, Healthcare analytics  
- 🏥 **Clinical Systems & Standards:** EHRs (ICE, SystmOne, MediViewer), FHIR, HL7, GDPR compliance  
- 🖥 **UX & HCI:** CLI design, user-centered interfaces, portfolio-ready visualisation  
- ☁️ **Cloud & DevOps:** AWS/Azure basics, distributed systems  

---

## 🚀 Featured Projects

### 🧠🤖 Rule-Based AI Symptom Checker (CLI & FastAPI)
[GitHub Repo](https://github.com/SimonYip22/AI-Symptom-Checker) | [Live API](https://ai-symptom-checker-5rfb.onrender.com)

A **Python-based AI symptom checker** combining **rule-based inference** with **clinically-informed logic** to interpret patient-reported symptoms and rank likely conditions.  

Unlike generic AI tools, this project encodes **doctor-level clinical reasoning**, using weighted symptom–condition mappings and input normalisation to reflect real-world prioritisation.  

**Highlights:**
- 🏥 Clinically-informed input handling for lay-language symptoms  
- ⚖️ Rule-based inference with **formula-weighted scoring** ensuring interpretable, relevant outputs  
- 💻 **Dual interface**: **Command-line tool** + **FastAPI JSON API (live on Render)**  
- 🔄 **Continuous Integration (GitHub Actions)** validates API endpoints weekly and on push  
- 🧩 Modular architecture, future-ready for **ML/NLP integration and frontend expansion**  

**Workflow Overview:**  

![Symptom Checker Flowchart](symptom-checker-flowchart.png)  
*Figure 1: Rule-based AI symptom checker workflow showing symptom input, weighted scoring, and top condition output with advice.*

---

### 🫀📉 NEWS2 Vitals Tracker with Alerts, Moitoring & visualisation (CLI & FastAPI)
[GitHub Repo](https://github.com/SimonYip22/Vitals-Tracker-CLI) | [Live API](https://vitals-tracker-cli.onrender.com/docs)

A **Python-based CLI & FastAPI tool** for **multi-patient vitals monitoring**, **real-time NEWS2 scoring**, tiered clinical alerts, and trend visualisation (ASCII & Matplotlib). Designed with **clinically-informed logic**, GDPR-compliant patient management, and longitudinal tracking.  

Supports clinicians in real-time monitoring, reduces risk of missed deterioration, and can integrate into hospital EHRs.

**Highlights:**
- 🏥 Clinically-informed input handling for patient vitals with validation  
- 📊 **Full vitals capture**: BP, HR, RR, Temp, O₂ sats, Level of Consciousness  
- 🚨 Tiered NEWS2 scoring and alerts aligned with **clinical decision thresholds** (Normal → Mild → Moderate → Severe)
- 💻 **Dual interface**: **Command-line tool** + **FastAPI JSON API (live on Render)** 
- ❓ Patient ID anonymisation for GDPR-compliant longitudinal multi-patient tracking
- 🔄 **Continuous Integration (GitHub Actions)** validates API endpoints weekly and on push
- 📈 Portfolio-ready trend visualisation with ASCII charts and **Matplotlib plots**  
- 🧩 Modular architecture supporting **future AI/ML predictive extensions**  

**Workflow Overview:**  

![Vitals Tracker Flowchart](vitals-tracker-flowchart.png)
*Figure 2: CLI & API patient vitals tracking workflow with NEWS2 scoring, alert logic, and trend visualisation.*

**Example Matplotlib Plot:**  

![Vitals Tracker Matplotlib Plot](vitals-tracker-matplotlib.png)
*Figure 3: Dual-axis Matplotlib plot of patient vitals over time with NEWS2 scores. Clinically-informed alerts are highlighted, demonstrating portfolio-ready visualisation and interpretation.*

---

### 📈📊 Time-Series ML Early Warning System (EWS) for ICU Patient Deterioration

**In Progress**

---

### 🔮🚀 Future Projects
- **Intelligent Clinical Decision Support Tool (CDST):** AI/ML-powered predictive risk stratification  
- **EWS Expansion:** Full Early Warning Score system with predictive analytics  
- **NLP Clinical Findings Extraction:** Automating insights from unstructured clinical notes  

---

## 📬🤝 Connect with Me

[LinkedIn](https://www.linkedin.com/in/simonyip22/) | [GitHub](https://github.com/SimonYip22) | Portfolio coming soon 🌐

---

*Clinically-informed, technically rigorous, and designed to make me an **irreplacable clinician-technologist in healthcare AI**.*
