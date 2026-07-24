# Oracle EBS R12 Financials Setup (GL & AP)

## Project Overview

This project demonstrates the complete functional configuration of Oracle E-Business Suite R12 Financials, focusing on the implementation of:

- General Ledger (GL)
- Accounts Payable (AP)

The project covers the end-to-end functional setup required to build a complete financial environment, including security configuration, Chart of Accounts, ledger setup, accounting calendar, reporting, budgeting, operating unit configuration, supplier management, invoice processing, and journal accounting.

> Company Name: Delta (Demo Environment)

---

# Project Modules

Current Modules

- General Ledger (GL)
- Accounts Payable (AP)

Future Modules

- Accounts Receivable (AR)
- Cash Management (CE)
- Fixed Assets (FA)
- Purchasing (PO)
- Inventory (INV)

---

# General Ledger (GL) Setup Flow

## 1. Security Setup

- Create User
- Create Responsibility
- Assign Responsibility to User

Screenshot

![](GL%20SETUP/user%20and%20responsibility%20assignment.jpg)

---

## 2. Currency Setup

### Functional & Reporting Currency

- Enable Functional Currency
- Enable Transaction Currency
- Configure Daily Rates
- Configure Reporting Currency
- Configure Translation Responsibility

Screenshots

![](GL%20SETUP/daily%20rate.jpg)

![](GL%20SETUP/reporting%20currency.jpg)

![](GL%20SETUP/translated%20ledger%20resbonsibility.jpg)

![](GL%20SETUP/enable%20currency.jpg)


---

## 3. Accounting Calendar

- Define Calendar Type
- Create Accounting Calendar
- Define Accounting Calendar
- Generate Calendar
- Define 13 Periods
  - 12 Normal Periods
  - 1 Adjustment Period

Screenshots

![](GL%20SETUP/calendar%20type.jpg)

![](GL%20SETUP/define%20acc%20calendar.jpg)

![](GL%20SETUP/requests.jpg)

---

## 4. Chart of Accounts (COA)

### Create Value Sets

Screenshots

![](GL%20SETUP/account%20value%20set.jpg)

![](GL%20SETUP/depart%20value%20set.jpg)

---

### Define Key Flexfield Structure

- Company
- Department
- Account
- Future Segments

Screenshot

![](GL%20SETUP/coa%20key%20flexfield.%20segment.jpg)

---

### Define Segment Values

- Company Values
- Sub Account Values
- Parent Values
- Child Values

Screenshots

![](GL%20SETUP/coa%20company%20vs.jpg)

![](GL%20SETUP/coa%20sub%20acc%20vs.jpg)

![](GL%20SETUP/coa%20segment%20values.jpg)

![](GL%20SETUP/coa%20depart%20values.jpg)

---

### Rollup Groups

Screenshot

![](GL%20SETUP/rollup%20group.jpg)

---

## 5. Ledger Setup

Configure:

- Functional Currency
- Accounting Calendar
- Chart of Accounts
- Accounting Method
- Ledger Options
- Reporting Currency
- Translation Options

Screenshots

![](GL%20SETUP/ledger%20definition.jpg)

![](GL%20SETUP/ledger%20option.jpg)

![](GL%20SETUP/ledger%20advanced%20option.jpg)

![](GL%20SETUP/ledger%20review.jpg)

![](GL%20SETUP/ledger%20translate.jpg)

---

## 6. Responsibility Assignment

Assign the Ledger to the GL Responsibility.

Screenshot

![](GL%20SETUP/copy%20gl%20responsibility.jpg)

---

## 7. Open Accounting Period

- Open Ledger Period
- Open USD Ledger Period

Screenshots

![](GL%20SETUP/open%20period.jpg)

![](GL%20SETUP/usd%20ledger%20open%20period.jpg)

---

## 8. Journal Processing

### Enter Journal

![](GL%20SETUP/enter%20journal.jpg)

### Journal Inquiry

![](GL%20SETUP/journals.jpg)

### Account Inquiry

![](GL%20SETUP/account%20inquiry.jpg)

### USD Journal

![](GL%20SETUP/usd%20journal.jpg)

---

## 9. Recurring Journals

Screenshots

![](GL%20SETUP/define%20recuring%20journal.jpg)

![](GL%20SETUP/recuring%20journal%20line.jpg)

---

## 10. Budget Setup

Configure:

- Budget Definition
- Budget Organization
- Budgetary Control

Screenshots

![](GL%20SETUP/define%20budget.jpg)

![](GL%20SETUP/budget%20org.jpg)

![](GL%20SETUP/budgetry%20control.jpg)

---

## 11. Document Sequence

Screenshot

![](GL%20SETUP/define%20sequence.jpg)

---

## 12. Financial Statement Generator (FSG)

Configure:

- Column Set
- Row Set
- Account Assignment
- Financial Reports

Screenshots

![](GL%20SETUP/fsg%20column%20set.jpg)

![](GL%20SETUP/fsg%20row%20set.jpg)

![](GL%20SETUP/fsg%20acc%20assignment%20row%20set.jpg)

![](GL%20SETUP/fsg%20report.jpg)

---

## 13. Summary Accounts

Screenshots

![](GL%20SETUP/summary%20account.jpg)

![](GL%20SETUP/summary%20balances.jpg)

![](GL%20SETUP/account%20summary%20balance.jpg)

---

# Accounts Payable (AP) Setup Flow

Before configuring Accounts Payable, the Inventory Organization and Operating Unit were configured.

---

## 1. Inventory Organization

Screenshots

![](AP%20SETUP/inv%20org%20definition.jpg)

![](AP%20SETUP/inventory%20parameter.jpg)

![](AP%20SETUP/org%20parameter.jpg)

![](AP%20SETUP/org%20parameter%20accounts.jpg)

![](AP%20SETUP/org%20param%20cost%20info.jpg)

---

## 2. Operating Unit Assignment

Screenshot

![](AP%20SETUP/assign%20operating%20unit.jpg)

---

## 3. Assign Ledger to Operating Unit

Screenshot

![](AP%20SETUP/gl%20assign.jpg)

---

## 4. Financial Options

Configure:

- Ledger
- Accounting Information
- Business Defaults
- Intercompany Options

Screenshots

![](AP%20SETUP/financial%20option%20setup.jpg)

![](AP%20SETUP/financial%20options2.jpg)

---

## 5. Profile Options

Configure Profile Options to associate:

- Responsibility
- Ledger
- Operating Unit

---

## 6. Accounts Payable Configuration

Configure:

- Payables Options
- Invoice Options
- Matching Options
- Accounting Options

Screenshots

![](AP%20SETUP/payable%20options%201.jpg)

![](AP%20SETUP/payable%20option%202.jpg)

---

## 7. Open Payables Period

Screenshot

![](AP%20SETUP/open%20payable%20period.jpg)

---

## 8. Seed Data Request

Run Required Seed Data Request.

Screenshot

![](AP%20SETUP/rep%20seed%20data%20request.jpg)

---

## 9. Distribution Sets

Screenshot

![](AP%20SETUP/distribution%20set.jpg)

---

## 10. Supplier Setup

- Create Supplier
- Create Supplier Site

---

## 11. Invoice Processing

Create Accounts Payable Invoices.

Screenshot

![](AP%20SETUP/inv%20entry.jpg)

---

## 12. Journal Information

Review Accounting Entries generated from AP.

Screenshot

![](AP%20SETUP/ap%20journal%20info.jpg)

---

## 13. Error Handling

Release invoices from Error Status.

Screenshot

![](AP%20SETUP/release%20for%20error%20handle.jpg)

---

# Skills Demonstrated

- Oracle EBS R12 Financials
- General Ledger (GL)
- Accounts Payable (AP)
- Ledger Configuration
- Chart of Accounts (COA)
- Value Sets
- Key Flexfields
- Accounting Calendar
- Daily Rates
- Reporting Currency
- Ledger Translation
- Budget Setup
- Budgetary Control
- Financial Statement Generator (FSG)
- Summary Accounts
- Document Sequencing
- Operating Unit Configuration
- Inventory Organization
- Financial Options
- Payables Options
- Supplier Management
- Invoice Processing
- Journal Entries


---

# Author

Ahmed Ali

Faculty of Commerce (English) – Accounting Graduate

Oracle EBS Financial Consultant 
