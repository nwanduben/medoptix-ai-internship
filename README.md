# MedOptix AI – Personalized Treatment Optimization in European Healthcare

**Amdari Internship Accelerator – June 2025**
**Facilitator:** Muhammad Yekini

---

## 🔍 Overview

MedOptix is a UK-based digital health startup helping NHS and private orthopedic clinics improve patient outcomes. This full-stack data science project predicts therapy dropout, identifies adherence patterns, and powers personalized nudges for recovery.

---

## 🚀 Objectives

- Build an end-to-end pipeline: from CSV → PostgreSQL → Analysis → API
- Segment patients into personas based on recovery behavior
- Predict likelihood of dropout by Week 3
- Visualize trends in therapy adherence across clinics

---

## 📦 Project Structure

```
etl/          → Scripts to clean/load CSVs into PostgreSQL
eda/          → Jupyter notebooks for exploratory analysis
models/       → ML models: dropout prediction, adherence forecast
api/          → FastAPI endpoints for predictions
dashboards/   → Visual interfaces using Streamlit or Power BI
```

---

## 🧶 Tech Stack

- **Languages**: Python, SQL
- **Libraries**: Pandas, Seaborn, Plotly, scikit-learn, XGBoost, SHAP
- **Database**: PostgreSQL (Aiven Cloud)
- **Deployment**: Docker, Heroku/AWS EC2
- **API**: FastAPI, Swagger
- **CI/CD**: GitHub Actions
- **Visualization**: Streamlit, Power BI

---

## 📊 Current Progress

| Phase            | Status         | Notes                           |
| ---------------- | -------------- | ------------------------------- |
| Data Engineering | ✅ Completed   | Tables created, ETL ready       |
| EDA              | ⏳ In Progress | Pain trends & dropouts underway |
| Modeling         | ⏳ Pending     | Starts June 22                  |
| API + CI/CD      | ⏳ Pending     | After model training            |
| Dashboard        | ⏳ Pending     | Streamlit or Power BI           |

---

## 📚 Resources

- [Project Brief PDF](docs/medoptix-brief.pdf)
- [FastAPI Docs](https://fastapi.tiangolo.com)
- [Healthcare ML Fairness](https://fairlearn.org)
- [Streamlit Dashboards](https://streamlit.io)

---

## 🤝 Contributions
To contribute to the project:

1. **Fork** the repository on GitHub.
2. **Clone** your fork locally
3. **Create your branch**
4. **Commit your changes**
5. **Push to your branch**
6. **Open a Pull Request** on GitHub comparing:
- **base:** `main`
- **compare:** `eda-Benjamin`


This project is part of the **Amdari Internship Accelerator**
Mentor: Muhammad Yekini
Intern Cohort: Jan–Jul 2025
