# Consumer Finance Loan Risk Case Study

This repository contains an end-to-end **Loan Default Risk Analysis** case study using Python.  
It includes the complete analysis notebook and a business-ready presentation summarizing the key insights and recommendations.

---

## 📌 Problem Statement
Identify the key **driver variables** that strongly indicate **loan default risk** and derive actionable insights to support business decisions such as credit policy, risk-based pricing, and approval strategies.

---

## 📂 Repository Contents
- **`Gramener Consumer Finance Loan Risk Case Study - FINAL.ipynb`**  
  Complete analysis notebook with:
  - Data understanding & variable interpretation  
  - Data cleaning (missing values, outliers, formatting)
  - Univariate & bivariate analysis
  - Derived metrics (business/type/data-driven)
  - Visualizations and insights

- **`Loan_Risk_Analysis_Presentation.pdf`** *(or PPT/PDF you upload)*  
  Presentation summarizing the approach, key findings, and recommendations.

---

## 🧰 Tech Stack / Libraries
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Jupyter Notebook

---

## ✅ Analysis Workflow
1. **Data Understanding**
   - Checked dataset structure, datatypes, and variable meaning
   - Identified missing values, outliers, and inconsistencies

2. **Data Cleaning & Preparation**
   - Missing value treatment / imputation (where applicable)
   - Outlier handling (where required)
   - Feature formatting (dates, strings, categories)

3. **Exploratory Data Analysis (EDA)**
   - **Univariate analysis** (distribution and segmentation)
   - **Bivariate analysis** (relationships with default)
   - Created **derived metrics** (bins/bands) for business interpretation

4. **Key Driver Variables (Default Indicators)**
   Identified multiple variables that strongly influence default risk, such as:
   - Interest rate, Grade/Sub-grade
   - DTI, Annual income
   - Revolving utilization
   - Loan amount / installment
   - Delinquencies / public records / inquiries (where present)

---

## 📊 Key Visualizations Included
- Default distribution and class imbalance checks
- Risk separation across **Grade/Sub-grade**
- Default rate across **interest rate bands**
- Default rate vs **DTI / income / utilization**
- Correlation heatmap
- Combination analysis (e.g., Grade × Interest band)

---

## 💡 Business Insights (High Level)
- Higher risk segments show strong separation by **grade/sub-grade** and **interest rate**
- Customers with high **DTI** and high **revolving utilization** exhibit higher default likelihood
- Income and installment burden help explain affordability risk
- Certain combinations of drivers amplify risk and should be used in policy rules

---

## 🎯 Recommendations
- Apply **risk-based pricing** and stricter checks for high-risk segments
- Introduce rule-based screening for:
  - High DTI + high utilization
  - Low grade + high interest bands
- Use derived bins/segments for better policy design and communication

---

## ▶️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
