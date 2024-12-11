# EasyPay Mobile Application Features and Test Cases

This repository contains the feature requirements, acceptance criteria, test cases, and bug reports for the EasyPay Mobile Application. EasyPay is an MFS (Mobile Financial Service) app that allows users to perform various financial transactions, including merchant and utility bill payments, balance loans, and more.

## Features Overview

### Feature 1: Merchant and Utility Bill Payments
- **Merchant Payments**: A 1% service charge applies, with a minimum fee of 5 TK. Cashback is available for large transactions:
  - **10% Cashback**: Transactions above 5000 TK.
  - **20% Cashback**: Transactions above 10,000 TK, up to a maximum cashback of 3000 TK.
- **Utility Payments**: No cashback is applicable.

### Feature 2: Balance Loan Facility
- Customers with a balance below 100 TK can apply for a loan of up to 20,000 TK.
- **Interest-Free Period**: Loans repaid within 30 days have no interest.
- **Interest on Overdue Payments**: Daily compound interest of 1.8% applies after 30 days.
- **Eligibility for Multiple Loans**: After repaying 50% of an outstanding loan, customers can apply for another loan.

---

## Repository Contents

- **Acceptance Criteria**: Defined for each feature using a rule-based standard.
- **Test Cases**: Positive and negative test cases for features, provided in a structured format.
- **Bug Reports**: Identified bugs and improvements with priority and severity levels.
- **Feature Prioritization**: Documented rationale for prioritizing features using the attached priority table.

---

## File Structure

