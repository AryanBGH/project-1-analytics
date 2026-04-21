# Data Cleaning Log

## Objective
Document all data cleaning checks and actions performed during Week 3.

### Step 1: Missing Value Scan
- Tool used: Excel Online (SharePoint)
- Columns checked: All
- Observations:
  - No blank cells detected in any column
  - No placeholder values such as NA, null, or N/A detected
  - Zero values appear to be valid domain values
- Action taken: None (no missing values found)

### Step 2: Categorical Consistency Check
- Tool used: Excel Online (SharePoint)
- Columns checked: Gender, Subscription Type, Contract Length, Churn
- Observations:
  - All categorical columns contain consistent and expected values
  - No spelling variations or formatting issues detected
- Action taken: None (no inconsistencies found)

### Step 3: Numerical Sanity Check
- Tool used: Excel Online (SharePoint)
- Columns checked: Tenure, Monthly Charges, Total Charges
- Observations:
  - No negative values detected
  - All numerical values fall within reasonable, business-expected ranges
  - No extreme or impossible values identified
- Action taken: None (no numerical issues found)

---

### Step 4: Duplicate Record Check
- Tool used: Excel Online (SharePoint)
- Columns checked: All
- Observations:
  - No duplicate rows detected based on full-row comparison
- Action taken: None (no duplicate records found)

---

### Step 5: Schema & Data Type Verification
- Tool used: Excel Online (SharePoint)
- Columns checked: All
- Observations:
  - Numerical columns contain only numeric values
  - Categorical columns contain only expected category labels
  - No schema inconsistencies detected
- Action taken: None (data types verified as correct)

---

### Step 6: Cleaned Dataset Generation
- Tool used: Excel Online (SharePoint)
- Observations:
  - No data transformations were required during cleaning
  - Cleaned dataset is identical to the raw dataset
- Action taken:
  - Exported analysis-ready dataset to `data/cleaned/customer_churn_cleaned.csv`

