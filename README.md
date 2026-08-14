# 📊 Fintech Risk Analysis Dashboard – Power BI

An interactive Power BI dashboard developed to analyze loan portfolio performance, customer risk, repayment behavior, and verification outcomes.

The project uses **Power Query for data preparation, data modelling for relationships, DAX for KPI calculations, and Power BI visualizations** to convert loan data into actionable business insights.

---

## 📸 Dashboard Preview

<img width="1427" height="801" alt="Fintech Risk Analysis Dashboard" src="https://github.com/user-attachments/assets/a769ffd0-9ca0-44af-8e8b-4939e9338f0f">

---

## 🎯 Business Objective

Financial institutions need to continuously monitor loan portfolios to understand repayment performance, identify risky customer segments, and track recovery.

This dashboard was created to answer key business questions such as:

- How much loan amount has been disbursed?
- How much has been recovered?
- What is the overall default rate?
- Which customer segments have higher risk?
- How does employment type affect loan performance?
- What are the major verification risk reasons?
- How does loan performance change over time?

---

## 🔄 Data Analysis Process

The project follows a typical Power BI data analysis workflow:

### 1. Data Preparation

Used **Power Query** to prepare the dataset for analysis.

Activities include:

- Reviewing the dataset
- Cleaning and transforming data
- Handling data types
- Preparing fields for analysis
- Creating a structured dataset for reporting

### 2. Data Modelling

Created relationships between relevant tables to build a connected data model.

The model supports analysis across:

- Applications
- Verification
- Loan performance
- Customer information

### 3. DAX Measures

Created DAX measures to calculate important business metrics such as:

- Total Loan Disbursed
- Total Recovery
- Default Rate
- High-Risk Accounts
- Average Ticket Size

### 4. Data Visualization

Created an interactive dashboard using Power BI visuals to present portfolio performance and risk information clearly.

---

## 📈 Key Performance Indicators

The dashboard includes the following KPIs:

| KPI | Purpose |
|---|---|
| 💰 Total Disbursed Loan | Measures the total loan amount |
| 💵 Total Recovery | Measures the amount recovered from customers |
| 📉 Default Rate | Measures the percentage of defaulted loans |
| ⚠️ High-Risk Accounts | Identifies accounts with higher risk |
| 💳 Average Ticket Size | Shows the average loan amount |

---

## 📊 Dashboard Features

### Portfolio Performance
- Total loan disbursement
- Recovery analysis
- Default rate
- Average loan amount
- Loan performance trends

### Customer Analysis
- Employment type analysis
- Loan distribution by customer segment
- Recovery performance by employment type

### Risk Analysis
- High-risk account analysis
- Verification status
- Risk flag reasons
- Default performance

### Interactive Filters
- Date slicer
- Employment type filter
- Interactive dashboard visuals

---

## 📌 Visualizations Used

The dashboard uses different Power BI visuals to present the analysis effectively:

- KPI Cards
- Line Chart
- Donut Chart
- Clustered Bar Chart
- Funnel Chart
- Area Chart
- Matrix
- Slicers

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **Microsoft Excel** – Source dataset
- **GitHub** – Project documentation and version control

---

## 💡 Key Insights

The dashboard highlights several important patterns in the loan portfolio:

- Salaried customers contribute a larger share of total loan disbursement.
- Employment type shows differences in loan recovery performance.
- Default rate provides an important measure of overall portfolio risk.
- Verification status helps identify the proportion of applications that successfully pass the verification process.
- Risk flag analysis helps identify common reasons for verification issues.
- Recovery analysis provides a clear view of the amount collected from the loan portfolio.

---

## 📂 Repository Structure

```text
PowerBI-Fintech-Risk-Analysis/
│
├── Dashboard/
│   └── Fintech Risk Analysis.pbix
│
├── Dataset/
│   └── fintech_risk_dataset.xlsx
│
├── Screenshots/
│   └── dashboard.png
│
├── README.md
├── .gitignore
└── LICENSE
