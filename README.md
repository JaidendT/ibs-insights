# IBS Insights — Personal Health Data Analytics & ML

A personal data science and machine learning project exploring how daily habits, symptoms, stress, sleep, diet, and activity relate to IBS flare-ups.  
The goal is to collect structured self-data, combine it with external research datasets, and build statistical + ML models that can detect patterns, quantify triggers, and generate personalised predictions.

This project is both a learning environment (SQL, Python, Bayesian modelling, ML) and a long-term health insight tool.

---

## 📌 Project Goals
- Collect clean, structured daily health data  
- Build a reproducible analytics pipeline  
- Explore correlations between symptoms, lifestyle factors, and flare-ups  
- Apply machine learning to predict flare-up risk  
- Use Bayesian statistics to quantify uncertainty and personalised effects  
- Deploy an interactive Streamlit dashboard for insights  

---

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn, PyMC, Matplotlib)  
- **Jupyter Notebooks** for exploration  
- **PostgreSQL / SQLite** as the database  
- **SQLAlchemy** for data access  
- **Streamlit** for a future dashboard  

---

## 📁 Project Structure
```text
ibs-insights/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│   ├── exploration/
│   └── modeling/
│
├── src/
│   ├── data_collection/
│   ├── preprocessing/
│   ├── analysis/
│   └── models/
│
├── app/
│
├── db/
│   └── schema.sql
│
├── config/
│   └── settings.yaml
│
├── .gitignore
├── requirements.txt
└── README.md
```
---

## 📊 Data Collected
(Will expand with time.)

- **Symptoms:** bloating, constipation, diarrhoea, abdominal pain, nausea, energy  
- **Lifestyle:** diet, hydration, caffeine, sleep quality  
- **Wearable data:** HR, HRV, stress score, steps, exercise time  
- **Mood & stress levels**  
- **Medication & supplements**  
- **Daily flare-up severity**  

---

## 🚀 Planned Features
- Daily data entry script (CLI → Streamlit form)  
- Automated data cleaning + summarisation  
- Correlation, time-series, and rolling window analysis  
- Trigger scoring system  
- Flare-up prediction models  
- Bayesian hierarchical models  
- Interactive Streamlit dashboard  

---

## 📈 Project Status
**Phase 1 — Setup & Data Design**

- Folder structure ✔  
- README ✔  
- Database schema ⏳  
- Data entry script ⏳  

---

## 📄 License
MIT License.