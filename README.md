# 📦 Logistics Automation Platform
### End-to-End Email → Excel → ETL → Master Dataset Automation

This automation system processes logistics booking emails, extracts and standardizes spreadsheet data, computes KPIs, updates a central master dataset, and maintains customer-specific order history — all without manual work.

### Workflow Screenshots
<p align="center">
  <img src="https://github.com/user-attachments/assets/ef57a43c-fdbc-4488-ba14-e3eca894af5f" width="49%" />
  <img src="https://github.com/user-attachments/assets/6cfa2b7a-7ce3-4975-8092-5678b4cc797b" width="49%" />
  <img src="https://github.com/user-attachments/assets/bd431aac-08c2-4366-8a9f-e330512e0aa1" width="49%" />
  <img src="https://github.com/user-attachments/assets/64a7662b-4314-4e9f-ae1f-9226b7b1c2b8" width="49%" />
</p>

*It is a complete **ETL + data warehouse + workflow automation engine** built using Power Automate, Excel Scripts, and SharePoint.*

---

## 🚀 What the Automation Does
- Detects and processes **all incoming booking emails**
- Validates file format, naming, and supported templates
- Runs a **700+ line Excel Script** to normalize multi‑format spreadsheets
- Cleans placeholders and inconsistent fields
- Extracts and standardizes dates (multiple formats supported)
- Automatically calculates:
  - DIFOT (HIT / MISS)
  - Expected & Actual Travel Days
  - Days Late
  - ISO Week & Year values
- Generates a unique `RecordKey` for deduplication
- Updates or inserts records into **Master_Current.xlsx**
- Creates & maintains **customer-specific order history files**
- Sends success/error notifications with full traceability

---

## 🧩 High-Level Workflow
```
Email → Validation → Excel Script Normalizer
      → KPI Engine (ISO, DIFOT, Travel Days)
      → Master Sheet Upsert (Update/Insert)
      → Customer Workbook Manager
      → Notifications
```

---

## 🛠️ Key Capabilities
- Multi-format Excel parser with dynamic column detection
- Automated data cleaning & normalization
- Complex KPI computation (ISO logic, travel days, DIFOT)
- Master data warehouse updating
- Customer folder & workbook auto-creation
- SharePoint automation for file storage
- Full error-handling & quality checks
- 40+ Power Automate actions integrated
- Equivalent to a **mini data warehouse pipeline** inside Microsoft 365

---

## 📈 Business Impact
- Saves **2–3 hours of manual work per day** (small operations)
- Up to **6,083 hours saved per year** at higher booking volumes
- Approx. **$152,000+/year labor savings**
- 80% fewer manual data-entry errors
- Faster order processing and higher DIFOT accuracy
- Improved customer visibility and operational consistency
- Automation **pays for itself within 1–3 months**

---

## 🧰 Tech Stack
- **Power Automate** (flow orchestration)
- **Excel Script** (700+ lines TypeScript)
- **SharePoint / OneDrive** (file and folder automation)
- **Outlook 365** (email ingestion)
- **Advanced ETL logic & KPI calculations** inside Power Automate

---

## 📁 Included Files
- `Automation.pdf` – Complete workflow logic & ROI analysis

---

This project demonstrates professional-level **automation engineering**, **ETL design**, and **process optimization** built for real logistics operations.
