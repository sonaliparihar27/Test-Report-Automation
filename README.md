# 🤖 Automated Test Report Validator (Python)

## 📌 Overview
This project automates the validation of automotive test reports by comparing data from INCA and SEM systems against predefined specifications.

The solution eliminates manual comparison and generates instant OK/NG results.

> ⚠️ Note: This repository uses sample data due to confidentiality restrictions.

---

## 🎯 Objective
- Automate comparison of test datasets
- Validate values against expected limits
- Generate OK/NG decisions
- Auto-fill Excel test reports

---

## 🛠 Tools & Technologies
- Python (pandas)
- openpyxl
- Excel automation

---

## ⚙️ Methodology

### 1️⃣ Data Processing Pipeline
- Read INCA and SEM files
- Normalize parameter names across systems
- Align datasets for comparison

---

### 2️⃣ Parameter Mapping
- Handled different naming conventions
- Mapped parameters between systems
- Ensured consistent comparison

---

### 3️⃣ Validation Logic
Applied rule-based validation:
- Threshold checks
- Min/Max boundaries
- Tolerance comparison

Example logic:
