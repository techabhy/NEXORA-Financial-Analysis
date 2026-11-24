# NEXORA – Financial Performance & Budget Analysis Dashboard

An interactive Power BI dashboard designed to analyze financial performance, invoice management, payment trends, tax distribution, departmental budgets, and employee expenses.

## 📊 Project Overview

NEXORA is a fictional company created for this financial analytics project. The objective is to transform financial data into meaningful business insights using Power BI, Power Query, and DAX.

The dashboard consists of two interactive pages:

- **Financial Performance:** Analyzes invoices, payments, invoice status, customer performance, and tax distribution.
- **Budget & Expense Management:** Analyzes budget allocation, departmental spending, budget utilization, and employee expenses.

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Cleaning & Transformation
- Data Visualization

## 📁 Dataset Information

The project uses five datasets containing a total of 650 records.

| Dataset | Records |
|---|---:|
| Invoices | 200 |
| Payments | 150 |
| Employee Expenses | 120 |
| Tax Entries | 100 |
| Budgets | 80 |
| **Total** | **650** |

## 📌 Dashboard Pages

### 1. Financial Performance

This page provides an overview of the company's invoice and payment performance.

**Key Performance Indicators (KPIs):**
- Total Invoice Amount: 639.99K
- Total Invoices: 200
- Total Payments: 520.99K
- Overdue Invoices: 18

**Key Business Insights:**

1. **Invoice Status Analysis:** 136 invoices (68%) are pending, 46 (23%) are paid, and 18 (9%) are overdue.
2. **Monthly Invoice Trend:** June recorded the highest invoice amount at approximately 98K, while April recorded the lowest.
3. **Payment Method Analysis:** Credit Card is the leading payment method, followed by Bank Transfer and Cash.
4. **Customer Analysis:** Julia Wilson, Paula Hughes, Jack Cruz, Hugo Kim, and Jack Bennett are the top five customers by invoice amount.
5. **Tax Analysis:** Sales Tax contributes the highest amount, followed by Income Tax and Property Tax.

### 2. Budget & Expense Management

This page focuses on departmental budget allocation, spending patterns, and employee expenses.

**Key Performance Indicators (KPIs):**
- Total Allocated Budget: 1.13M
- Total Spent Budget: 1.42M
- Total Employee Expenses: 115.21K
- Budget Utilization: 126.07%

**Key Business Insights:**

1. **Budget Utilization:** Overall spending reached 126.07% of the allocated budget, indicating approximately 26.07% overspending.
2. **Budget Status:** 46 out of 80 budget records are over budget, while 34 are within budget.
3. **Department Analysis:** The Development department shows notable overspending, with spending of approximately 80K against an allocated budget of approximately 53K.
4. **Monthly Employee Expenses:** December recorded the highest employee expenses at approximately 18K, while August recorded the lowest.
5. **Employee Analysis:** Elif Reyes, Grace Singh, Mila Kowalski, Alice Castro, and Fatima Carter are the top five employees by expenses.

## 📈 Dashboard Features

- Interactive KPI cards
- Monthly financial trend analysis
- Invoice status distribution
- Payment method analysis
- Top 5 customer analysis
- Tax type analysis
- Department-wise budget comparison
- Budget status distribution
- Monthly employee expense trends
- Top 5 employee expense analysis
- Interactive date and category slicers

## 🔄 Data Preparation & Modeling

The project involved the following steps:

1. Imported five datasets into Power BI.
2. Cleaned and transformed data using Power Query.
3. Removed unnecessary columns and verified data types.
4. Checked missing values and key relationships.
5. Created relationships between Invoices, Payments, and Tax Entries.
6. Created a custom Budget Status column to classify budget records.
7. Developed DAX measures for financial KPIs.
8. Designed interactive dashboards with charts, cards, and slicers.

## 💡 Business Recommendations

Based on the dashboard findings:

- Review pending invoices and strengthen payment follow-up processes.
- Investigate the gap between invoice amounts and recorded payments.
- Monitor departments with spending above their allocated budgets.
- Review the Development department's budget performance.
- Analyze the December increase in employee expenses.

## ⚠️ Data Considerations

- NEXORA is a fictional company, and the datasets are used for analytical practice.
- Payment records may not directly reconcile with invoice amounts.
- Budget utilization is calculated using total spent budget divided by total allocated budget.
- Budget status counts represent budget records, not unique departments.
- Findings are based on the available dataset and dashboard filters.

## 🎯 Project Objective

The main objective of this project is to demonstrate practical skills in data cleaning, data modeling, DAX calculations, interactive dashboard development, and business insight generation using Power BI.

---

**Created by:** DATA ABHAY  
**Project:** NEXORA – Financial Performance & Budget Analysis  
**Technology:** Microsoft Power BI
