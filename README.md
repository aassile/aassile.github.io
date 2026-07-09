# Andrew Assile — Data Science Portfolio

Data scientist with an MS in Data Science (Eastern University, 2024) and a BS in Mathematics (Ramapo College of New Jersey, 2021). Focused on predictive modeling, explainable machine learning, and production analytics in Python and SQL.

Portfolio site: [aassile.github.io](https://aassile.github.io)

---

## Projects

### Dental Claim Cost Pricing with Explainable XGBoost

End-to-end regression pipeline predicting expected claim cost per member using engineered behavioral, demographic, and geographic features.

**Stack:** Python, XGBoost, SHAP, Optuna, Streamlit, pandas, NumPy

**Key results:**
- Holdout RMSE of 187 and R² of 0.89
- SHAP global and local interpretability for pricing transparency
- Live interactive Streamlit app for scenario testing

[View repo](https://github.com/aassile/Dental-Insurance-Pricing)

---

### GLM Pricing — French Motor Third-Party Liability

Actuarial-style ratemaking pipeline using frequency and severity models on the freMTPL2 dataset (678K policies, 26K claims).

**Stack:** Python, statsmodels, Poisson GLM, Gamma GLM, pandas

**Key results:**
- Poisson GLM for claim frequency; Gamma GLM for claim severity
- Combined into pure premium estimates
- Structured into reusable `src/` modules with reproducible notebooks

[View repo](https://github.com/aassile/GLM-Pricing-French-MTPL)

---

### Sonar Mine Detection — Mines vs. Rocks Classification

End-to-end binary classification pipeline on the UCI Sonar dataset, distinguishing underwater mines from rocks using 60 acoustic frequency-band energy readings.

**Stack:** Python, scikit-learn, Extra Trees, Plotly, pytest

**Key results:**
- Compared Random Forest, Extra Trees, Gradient Boosting, and a neural net
- Tuned Extra Trees best: 92.9% test accuracy, 0.982 ROC-AUC
- Permutation-importance interpretability, K-Means clustering, and synthetic stress-testing
- Packaged into importable `src/` modules with a reproducible notebook, pytest suite, and CI
- Live interactive Streamlit app for signal classification and per-band explanations

[Live app](https://sonar-mine-detection-andrew-assile.streamlit.app/) · [View repo](https://github.com/aassile/Sonar_Mine_Detection)

---

## Technical Skills

| Category | Tools |
|---|---|
| Languages | Python, SQL, R |
| Modeling / ML | XGBoost, GLMs, scikit-learn, statsmodels, SHAP, Optuna |
| Data Wrangling | pandas, NumPy |
| BI / Reporting | Power BI, Tableau, Qlik Sense |
| Infrastructure | Git, AWS S3/EC2, Streamlit |

---

## Background

**MS Data Science** — Eastern University, 2024 (GPA 3.83)
**BS Mathematics** — Ramapo College of New Jersey, 2021 (GPA 3.54, Pi Mu Epsilon)

Currently: Senior Financial Consultant, Dental Network Analytics at MetLife, building Python and SQL workflows for claims data pipelines, pricing inputs, and Power BI dashboards.

---

## Contact

- Email: [aassile.data@gmail.com](mailto:aassile.data@gmail.com)
- LinkedIn: [linkedin.com/in/andrew-assile](https://www.linkedin.com/in/andrew-assile/)
- GitHub: [github.com/aassile](https://github.com/aassile)
