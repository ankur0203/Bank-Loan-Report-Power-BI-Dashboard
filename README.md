# Bank Loan Report | Power BI Dashboard

A Power BI dashboard analysing bank loan applications, funding, and repayments.

## Overview

This project analyses 38.6K loan applications to understand loan performance, good vs bad loans, and repayment trends by month, state, purpose, term, and home ownership.

## Key KPIs

- **Total Loan Applications:** 38.6K
- **Total Funded Amount:** $435.8M
- **Total Amount Received:** $473.1M
- **Avg Interest Rate:** 12.0%
- **Avg DTI:** 13.3%

## Pages

### 1. Summary
Good vs Bad loan split and Loan Status breakdown.
- Good Loans: 86.2% — 33.2K applications, $370.2M funded, $435.8M received
- Bad Loans: 13.8% — 5.3K applications, $65.5M funded, $37.3M received
- Fully Paid loans are the biggest group — 32,145 applications, with the lowest avg interest rate at 11.64%
- Charged Off loans lost money: $65.5M funded but only $37.3M received

### 2. Overview
Trends and breakdowns.
- Amount received more than doubled during the year, from $28M in Jan to $58M in Dec
- Debt consolidation is the biggest purpose at $0.25bn, more than 3x the next purpose, credit card at $0.07bn
- 36-month loans bring in most of the amount received — $294.71M (62.3%) vs $178.36M for 60 months
- Borrowers with 10+ years employment bring in the most — $126M

### 3. Details
Row-level loan details with filters for State, Grade, and Good vs Bad Loans.
Columns include Purpose, Home Ownership, Grade, Sub Grade, Issue Date, Funded Amount, Interest Rate, Installment, and Total Amount Received.

## Key Insights

- 86.2% of loans are good loans, bringing in $435.8M of the $473.1M received.
- Debt consolidation dominates lending purpose.
- Shorter 36-month terms generate more repayment than 60-month terms.
- Repayment grew steadily month-on-month through the year.

## Tools Used

- Power BI Desktop
- DAX Measures — Total Loan Applications, Total Funded Amount, Total Amount Received, Avg Interest Rate, Avg DTI, MTD and MoM
- Data Model — bank_loan_data, Date Table

## Dataset

Bank loan dataset with loan ID, purpose, home ownership, grade, issue date, funded amount, interest rate, installment, loan status, and amount received.

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Use the Summary, Overview, and Details pages and the slicers for State, Grade, Purpose, and Good vs Bad Loans.

## Screenshots

### Summary

