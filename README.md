# Hey! I'm EJ | Data & Business Analytics

> **I investigate messy business data to make sure executives doesn't make expensive decisions on broken numbers.

I currently pursue **BS in Information Systems (Major in Business Analytics)** at West Visayas State University. I sit right between the database and the boardroom. I find calculation errors in raw ledgers, optimize budgets, and build dashboards that anyone on the team can immediately understand.

---

## 🛠️ Tools & Technologies

| Code & Scripting | Data & Math | Databases | Dashboards & BI |
| :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) | ![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black) |
| ![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=sqlite&logoColor=white) | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | ![ScikitLearn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) | ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) | ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white) |

---

## 🔍 What I Actually Do

* **Find the "Hidden Leaks" in Data:** A model is useless if the spreadsheet/excel beneath it is broken. I audit raw records, fix tracking errors, and make sure the data tells the truth before running any code.
* **Prescribe the Best Financial Move:** Instead of just summarizing past numbers, I use mathematical optimization (Linear Programming) to calculate the best way to allocate funds under strict risk limits.
* **Simplify Dashboards:** Interactive tools with clear visual takeaways so non-technical managers don't have to decipher raw numbers.

---

## 📊 Featured Case Studies & Projects

## 1. Integrated Management and Finance System for TTMPC with Parallel Risk Prediction, Debt Capacity Framework, and Loan Demand Forecasting using Time-Series Analysis
*Undergraduate Thesis, BS Information Systems, West Visayas State University (CICT)*

**Domain:** Credit risk analytics and financial decision support systems
**Team:** Ashley Nicole B. Bulotaolo, Romelyn I. Delos Reyes, Nash Ervine A. Siaton, Gero Antoni T. Tabiolo, Erden Jhed D. Teope

### The problem
A paper-based cooperative (Tubungan Teachers' Multi-Purpose Cooperative) treated borrowers whose old loans showed as "fully settled" as its safest members. Loan processing was slow and management had no timely view of credit risk or cash needs.

### What we found
After rebuilding the loan ledger (932 Consolidated and Emergency loans):
- About **70 of every 100** settled loans were cleared by taking a new loan.
- Among the **138 members** with three or more Consolidated loans, borrowing grew for **83 (60%)**.

### The solution
A web-based system with role-based portals for staff and a responsive module for members, plus three decision-support components:

| Component | What it does | Result |
|---|---|---|
| Parallel Risk Prediction Module | Gradient-boosted model scores each application on the day it is submitted (GREEN / AMBER / RED) | ROC-AUC 0.68; bands separated later-risky loans at about 8, 15 and 30 per 100 |
| Debt Capacity Framework | Flags amortization above 40% of net take-home pay or amounts above the share-capital debt ceiling | Decision stays with staff and the Board of Directors |
| Loan Demand Forecasting | 12-month forecasts from 1,407 loan releases | Forecast error reduced 16% to 47% vs. SARIMA |

It also automates Member in Good Standing (MIGS) classification. In pilot testing, 10 staff and 5 members rated it Highly Satisfactory (ISO 9241-11 grand means 4.89 and 4.76; Technology Acceptance Model 4.99 and 4.97).

### My role
- **Data Analyst:** cleaned and prepared the loan data for the classification and forecasting models.
- **Risk Model Developer:** built the risk prediction model.
- **System Analyst:** mapped the loan lifecycle across roles; wrote the business-rule glossary, process inventory and test plan.
- **Information Systems Auditor:** reviewed access controls (row-level security), data integrity and audit trails; documented findings with severity, evidence and recommendations.

### Tech stack
React (Vite) · FastAPI (Python) · Supabase (PostgreSQL, Auth, Row-Level Security) · scikit-learn-style gradient boosting · Rapid Application Development

*Status: defense stage.*

### **2. Strategic Loan Portfolio for Financial Cooperatives**
* **Domain:** Prescriptive Optimization & Portfolio Capital Management
* **The Problem:** The organization decide how to distribute a $5,000,000 lending budget across micro-business, farming, and personal loans without exceeding a 3.5% default cap.
* **The Finding:** Personal loans offered the highest interest rate (16%), but their 9% default risk ate up the entire safety buffer. 
* **The Solution:** Mathematically proved that allocating 66.7% to agriculture and 33.3% to small enterprises generates the highest safe return ($483,333/year) while keeping risk under the legal ceiling.

### **3. SDG 13: The Climate Change & Health Risk Paradox Dashboard**
* **Domain:** Econometric Modeling & Interactive BI Architecture
* **The Problem:** Explore how rising global temperatures affect health vulnerability across 150+ countries.
* **The Finding:** Wealthier nations produce higher emissions but suffer lower immediate health risks because of stronger infrastructure which leaves poorer, low-emitting nations to carry a poorer climate condition .
* **The Solution:** Built an interactive 4-step dashboard with dedicated urban policy recommendations for ASEAN countries.

### **4. Clinical Breast Cancer Diagnostic Support System**
* **Domain:** Supervised Machine Learning & Explainable AI (XAI)
**The Problem:** In medical screening, telling a sick patient they are healthy (a false negative) is a fatal mistake.
* **The Solution:** Built a classification model that prioritizes catch rate (Recall: 95.35%) over simple accuracy. Paired every result with an explanation chart that shows exactly which tumor measurements triggered the warning so doctors can verify the reasoning.

---

## 💡 How I Work

* **Prescriptive Decision Support:** Data must go beyond backward-looking reporting to prescribe optimal resource allocation under real-world constraints.
* **Relentless Data Auditing:** A model is only as sound as the data beneath it. I prioritize raw data verification, leakage elimination, and distribution diagnostic checks before executing machine learning pipelines.
* **Transparent Communication:** Bridge the gap between database architecture and executive stakeholders through honest, jargon-free data storytelling.

1. **Check the Foundation First:** Most data errors come from human typos, missing columns, or bad spreadsheet formulas. I fix the data integrity before I touch any machine learning model.
2. **Focus on Business Impact:** High accuracy means nothing if it doesn't solve a real operational problem.
3. **Simplification:** If an executive or loan officer can't understand why a recommendation was made, the analysis has failed.

---

<p align="center">
  <b>Let's Connect:</b> 
  <a href="www.linkedin.com/in/ejt8008">LinkedIn</a> • 
  <a href="ejhedteope@gmail.com">Email</a>
</p>
