# Banking Lockbox Reconciliation & CRM Integration System  
### Hybrid Business + Technical Project (Based on Real Wipro Experience)

This project simulates a real banking client's **SFTP lockbox payment process**, **reconciliation logic**, **CRM enrichment**, and **reporting**, inspired by my work experience as a **Business Systems Analyst at Wipro**.

The goal of this repo is to demonstrate my ability to work across:

- Business Requirements Gathering  
- CRM Functional Analysis  
- SQL/ETL Logic  
- Banking Payment Processes  
- Reporting (Power BI / OBIEE-like dashboards)  
- Exception Handling  
- UAT & End-to-End validation  

This project is a **fully functional demonstration** with:  
✔ SQL queries  
✔ Python automation  
✔ Mock CRM Integration  
✔ Reconciliation Engine  
✔ Power BI dashboard  
✔ Realistic documentation (BRD, FSD, UAT)  

---

## 🧩 Project Overview

The system processes **lockbox payment files** received from an SFTP server, validates them, reconciles them against customer/accounts data, and updates a mock CRM system.

It represents the typical workflow I handled at Wipro:

### 🔸 Step 1 — Validate Incoming Lockbox File  
Checks control totals, formats, duplicates, and missing fields.

### 🔸 Step 2 — Reconcile Payments  
Matches payments to customers using:  
1. Account number  
2. Invoice/reference  
3. Name + amount fallback  

### 🔸 Step 3 — Generate Exceptions  
Creates exception records for unmatched payments.

### 🔸 Step 4 — Push Successful Payments to CRM  
Simulates Siebel CRM update tables.

### 🔸 Step 5 — Dashboard  
A Power BI model visualizes reconciliation KPIs, exceptions, and payment trends.

---

## 📊 Dashboard Preview (Power BI)

This project includes:
- Lockbox Summary
- Reconciliation Rate
- Exception Trends
- CRM Update Metrics

Screenshots are included in  
`/05-dashboard/dashboard_screenshots/`

---

## 🧪 Testing (UAT)

The repo includes:
- SIT Test Cases  
- UAT Test Scenarios  
- Test Data  
- Expected Output Files  

---

## 🏗 Architecture

Included under `/06-architecture/`:
- System Context Diagram  
- End-to-End Data Flow  
- Reconciliation Workflow Diagram (Mermaid)  

---

## 💼 Why This Project Matters

This repo **proves** my hands-on experience in:

✔ Banking Domain (Lockbox, Reconciliation, Payments)  
✔ Siebel CRM Enhancements  
✔ OBIEE / PowerBI Reporting  
✔ SQL / ETL logic  
✔ BA Documentation & Functional Analysis  
✔ Agile delivery (SIT/UAT/Test cases)  

It acts as an **industry-level portfolio project** that recruiters can:
- Inspect  
- Run  
- Validate  
- Understand  

---

## 📥 How to Run This Project

### 🔹 Option 1: Run Python Scripts

Install dependencies:
