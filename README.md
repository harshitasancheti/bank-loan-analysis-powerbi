# 📊 Bank Loan Analysis Using Power BI

> An end-to-end data analytics project analyzing bank loan portfolios using Microsoft Power BI — built during an internship at **BeWeSocial, Jodhpur**.

---

## 🔍 Project Overview

This project performs a comprehensive analysis of bank loan data to uncover insights about borrower behavior, loan performance, and portfolio risk. Using Power BI's interactive dashboards, the project translates raw loan data into actionable business intelligence.

**Internship Organization:** BeWeSocial Digital Marketing Agency, Jodhpur, Rajasthan  
**Industry Guide:** Mr. Nikhil Goklani (Founder, BeWeSocial)  
**Faculty Guide:** Dr. Manoj Tiwari  
**Student:** Harshita Sancheti | Reg No. 22MCAN123 | JECRC University

---

## 🎯 Objectives

- Analyze loan portfolio performance and borrower profiles
- Identify key risk indicators and default patterns
- Build interactive dashboards for real-time monitoring
- Support data-driven lending decisions through KPI tracking

---

## 🛠️ Technologies Used

| Tool/Technology | Purpose |
|---|---|
| **Power BI** | Data visualization & dashboard creation |
| **SQL** | Data querying and management |
| **Power Query (M)** | Data cleaning and transformation |
| **DAX** | Calculated measures and KPIs |
| **Excel / CSV** | Source data format |

---

## 📁 Repository Structure

```
bank-loan-analysis-powerbi/
│
├── 📊 Bank_Loan_Analysis_Dashboard.pbix      # Main Power BI dashboard file
├── 📄 Bank_Loan_Analysis_Synopsis_Report.pdf # Internship synopsis report
├── 📑 BANK_LOAN_ANALYSIS_USING_POWER_BI.pptx # Project presentation
├── 📑 Bank_Loan_Analysis_Major_Presentation.ppt # Detailed project presentation
└── 📝 README.md                              # This file
```

---

## 📈 Key Features & Dashboards

### 1. Summary Dashboard
- Total Loan Applications, Funded Amount, and Amount Received
- Month-over-Month (MoM) and Month-to-Date (MTD) KPI tracking
- Average Interest Rate and Debt-to-Income (DTI) Ratio

### 2. Good Loan vs Bad Loan Analysis
- Good Loans: Fully Paid + Current status
- Bad Loans: Charged Off status
- Visual breakdown by loan count, funded amount, and amount received

### 3. Loan Portfolio Breakdown
- By **State** (geographic distribution)
- By **Loan Term** (36 vs 60 months)
- By **Employment Length**
- By **Loan Purpose** (debt consolidation, education, home improvement, etc.)
- By **Home Ownership** (rent, own, mortgage)

---

## 📐 Key Performance Indicators (KPIs)

| KPI | Description |
|---|---|
| Total Loan Applications | Total number of applications received |
| Total Funded Amount | Total amount disbursed |
| Total Amount Received | Total repayments collected |
| Average Interest Rate | Mean interest rate across all loans |
| Average DTI | Mean debt-to-income ratio |
| Good Loan % | Share of performing loans |
| Bad Loan % | Share of defaulted/charged-off loans |

---

## 🔄 Data Processing Pipeline

1. **Data Collection** — Loan data from internal bank databases, credit bureaus, and APIs
2. **Data Cleaning** — Removed duplicates, handled missing values, treated outliers
3. **Data Integration** — Harmonized and standardized data from multiple sources
4. **Feature Engineering** — Created DTI ratio, credit utilization metrics, date hierarchies
5. **Data Modeling** — Built relationships between `bank_loan_data`, `Date Table`, and `Select Measure` tables in Power BI
6. **Visualization** — Designed interactive dashboards with slicers, drill-throughs, and cross-filtering

---

## 📊 Fields in the Dataset

| Field | Description |
|---|---|
| `loan_id` | Unique identifier for each loan |
| `address_state` | Borrower's state of residence |
| `annual_income` | Borrower's yearly income |
| `dti` | Debt-to-Income ratio |
| `emp_length` | Employment duration |
| `emp_title` | Job title |
| `grade` / `sub_grade` | Credit risk classification |
| `home_ownership` | Housing status |
| `loan_status` | Current/Fully Paid/Charged Off |
| `purpose` | Reason for loan |
| `term` | Loan duration (36/60 months) |
| `int_rate` | Interest rate |
| `loan_amount` | Principal borrowed |
| `installment` | Fixed monthly payment |

---

## 🚀 How to View the Dashboard

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `Bank_Loan_Analysis_Dashboard.pbix` in Power BI Desktop
4. Explore the interactive dashboards — use slicers to filter by state, term, grade, and purpose

---

## 📚 References

- Altman, E. I. (1968). Financial Ratios, Discriminant Analysis and the Prediction of Corporate Bankruptcy. *Journal of Finance*
- Basel Committee on Banking Supervision (2010). Basel III Framework
- Microsoft Power BI Documentation
- World Bank Open Data

---

## 📬 Contact

**Harshita Sancheti**  
JECRC University | MCA — Reg No. 22MCAN123  

---

> ⭐ If you found this project useful, consider starring the repository!
