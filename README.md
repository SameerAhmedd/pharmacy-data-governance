# Pharmacy Data Governance Portfolio

A self-initiated data governance project applied to a fictional online pharmacy dataset. Built to demonstrate practical skills in data cataloging, GDPR classification, data quality management, and governance policy design.

---

## Project Overview

This project simulates the work of a junior Data Governance Analyst at an online pharmacy. Starting from a raw, uncleaned order dataset, the workbook documents every field, classifies it by sensitivity and GDPR legal basis, identifies data quality issues, and defines governance rules and policies - end to end.

The dataset is entirely fictional and was designed to reflect realistic data governance challenges in a regulated healthcare e-commerce context.

---

## Workbook Contents

| Sheet | Description |
|---|---|
| **Raw Data** | 50-row simulated pharmacy order dataset with intentional quality issues flagged for review |
| **Data Catalog** | Field-level documentation: data type, source system, data owner, and governance remarks for all 20 fields |
| **Data Classification** | Sensitivity level, GDPR legal basis, retention period, and access control per field |
| **Quality & Issues** | 12 logged data quality problems with severity rating, root cause analysis, and recommended resolution |
| **Governance Rules** | Handling policies, masking rules, validation logic, and automation opportunities per field |
| **Changelog** | Full version history of the document |

---

## Skills Demonstrated

- Data catalog enrichment and field-level documentation
- Data classification by sensitivity (Public / Internal / Confidential / Restricted)
- GDPR compliance mapping (Art. 6 and Art. 9 legal bases, retention periods)
- Data quality issue identification, severity rating, and escalation
- Governance policy and data handling rule design
- Automation opportunity identification for governance processes

---

## Dataset Structure

20 fields across 5 categories:

- **Customer** — PII including name, date of birth, email, address
- **Order** — order ID, date, status, delivery method  
- **Product** — product ID, name, prescription requirement
- **Health** — ICD-10 diagnosis code, prescribing doctor (GDPR Art. 9 special category data)
- **Payment** — payment method, status, order value

---

## Context

This project was built as a portfolio exercise to apply data governance concepts to a realistic domain. All data is fictional. No real patient, customer, or transaction data was used.

GDPR framework references: EU Regulation 2016/679.
