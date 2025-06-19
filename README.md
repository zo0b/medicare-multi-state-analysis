# Medicare Inpatient Utilization & Reimbursement Analysis (NY, CA, PA) – 2023

## 📊 Overview

This project analyzes Medicare inpatient hospital data from CMS for New York, California, and Pennsylvania. It focuses on identifying:

- The most common inpatient DRGs (diagnosis-related groups) by discharge volume
- Gaps between average submitted charges and Medicare reimbursement
- Financial insights across high-cost treatments like CAR-T therapy and tracheostomies

The goal is to surface actionable insights for healthcare analysts, hospital finance teams, and policymakers.

---

## 🗂️ Contents

- `/data/`: Filtered CSVs by state (NY, CA, PA)
- `/dashboards/`: Tableau visualizations (volume + reimbursement gap per state)
- `README.md`: Project overview
- `tableau_links.txt`: Optional shareable Tableau Public links

---

## 📍 State-Level Insights

### 🔹 New York (NY)

- **Top DRG**: Septicemia (DRG 871)
- **High Gap**: CAR-T therapy (DRG 018) and tracheostomy (DRG 003) had reimbursement gaps over $1M
- Chronic cardiopulmonary conditions and elective surgeries dominate inpatient discharges

### 🔹 California (CA)

- **Top DRGs**: Septicemia, joint replacements, heart failure
- **Reimbursement gaps** were especially large for CAR-T therapy, major surgery, and neonatal care
- Higher discharge volume for elective procedures than NY and PA

### 🔹 Pennsylvania (PA)

- **Top DRGs**: Septicemia, pneumonia, COPD, joint replacements
- **CAR-T therapy average charge** exceeded $6 million, indicating major outlier cases
- Reimbursement gaps were similar to NY/CA, with financial strain in critical care categories

---

## 🧰 Tools Used

- **Tableau Public** – Data visualization
- **Excel** – Data filtering & prep
- **GitHub** – Project hosting
- **CMS Medicare Provider Utilization & Payment Data (2023)** – Public dataset

---

## 💡 Use Cases

- Support financial audits and 340B compliance analysis
- Inform cost-saving strategies and payer negotiations
- Monitor high-cost treatment trends across states
- Provide scalable benchmarking tools for healthcare analysts

---

## 📎 Data Source

Centers for Medicare & Medicaid Services (CMS)  
[https://data.cms.gov/provider-summary-by-type-of-service/medicare-provider-utilization-and-payment/medicare-inpatient-hospitals](https://data.cms.gov/provider-summary-by-type-of-service/medicare-provider-utilization-and-payment/medicare-inpatient-hospitals)

---

## 👤 Author

Zubair Ali  
Healthcare Data Analyst | Applied Math & Data Science  
[LinkedIn](https://www.linkedin.com/in/zubairali00) | [GitHub](https://github.com/zo0b)

---

## 📌 License

This project uses **public CMS data** and is shared for educational and analytical purposes only.
