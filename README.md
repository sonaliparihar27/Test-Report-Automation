# 🤖 Automated Test Report Validator (Python)One of the projects I worked on was an Automated Test Report Validator, where the goal was to automate the validation of test reports by comparing data from two different source systems against predefined specifications.

The main problem was that test report validation was being done manually. Data was coming from two systems, INCA and SEM, and the team had to compare parameter values manually, check whether they were within expected limits, and then fill the final test report in Excel. This process was time-consuming, repetitive, and prone to manual errors.

To solve this, I built a Python-based automation solution that automated the complete validation workflow.

First, I created a data processing pipeline to read raw files from both INCA and SEM systems. Since both systems had different formats and naming conventions, I standardized the data and normalized parameter names to make the datasets comparable.

Next, I built parameter mapping logic to align related parameters across both systems, because the same parameter often had different names in different sources. This step was important to ensure accurate comparison.

Once the data was aligned, I implemented rule-based validation logic. I applied checks such as threshold validation, min-max boundary checks, and tolerance comparisons to determine whether each parameter was within expected limits.

After validation, I automated the Excel reporting process using openpyxl. The script loaded a predefined Excel template and automatically populated expected values, actual values, validation results, and remarks. I also added conditional formatting so the final report was easy to interpret, where OK values were highlighted in green and NG values in red.

The final output was a fully completed and ready-to-use test report generated automatically, without manual comparison.

This project significantly reduced manual effort, improved accuracy, and made the validation process much faster and more reliable. It also created a scalable solution that could be reused for multiple test variants with minimal manual intervention

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
