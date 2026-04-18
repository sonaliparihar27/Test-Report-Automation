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

---

### 4️⃣ Excel Automation
- Loaded predefined report template
- Auto-filled:
  - Expected values
  - Actual values
  - Results (OK/NG)
  - Remarks
- Applied conditional formatting

---

### 5️⃣ Output Generation
- Generated fully completed test report
- Color-coded results:
  - 🟩 OK
  - 🟥 NG

---

## 📊 Sample Output
- Completed Excel test report
- Automated validation results
- Ready-to-use engineering document

---

## 🚧 Challenges Faced
- Handling different data formats (INCA vs SEM)
- Parameter mapping complexity
- Defining accurate validation rules
- Ensuring reliability of automation

---

## 📈 Impact
- Eliminated manual validation effort
- Improved accuracy of test results
- Reduced processing time significantly
- Scalable solution for multiple variants

---

## 🚀 Future Improvements
- Add GUI for user interaction
- Support more file formats
- Integrate with real-time systems
