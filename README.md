# Nonprofit Financial Management & Automation Toolkit

## 📌 Project Overview
A comprehensive financial management and automated transaction tracking system built for **NON-PROFIT o.z.** Designed to streamline non-profit accounting, multi-account balance tracking (cards, cash, debts), category tagging, and automated income/expense analysis.

* **Language / Platform:** Google Sheets (Advanced Formulas & Dynamic Arrays)
* **Domain:** Non-Profit Financial Operations & Process Automation

---

## 🛠 Core Architecture & Technical Stack
The system relies on modern Google Sheets features, avoiding manual data manipulation through the use of dynamic array formulas and functional programming constructs:
* **Dynamic Sequences & ID Generation:** Automatic row numbering and tracking using `SEQUENCE`, `COUNT`, and `FILTER`.
* **Running Balances & State Tracking:** Advanced utilization of `MAP`, `SCAN`, and array wrappers (`ARRAYFORMULA`, `TOROW`, `UNIQUE`) to calculate real-time cash flows across multiple financial accounts.
* **Categorization & Tagging System:** Automated aggregation of transactions by tags (`reklama`, `banking`, `earnings`, `tickets`, etc.) and flows (`Income` vs `Expenses`).
* **Summary Dashboards:** High-level overview cards tracking total debt, cash reserves, card balances, and net position using robust lookup formulas (`LOOKUP`, `SUMIF`).

---

## 📸 System Preview & Layout

### 1. Main Transaction Ledger & Running Balances
*Tracks dates, comments, payment types, category tags, cash flow direction, amounts, and real-time multi-account balances using `SCAN` / `MAP` logic.*

### 2. Category Mapping & Dynamic Tagging
*Organizes transaction streams into structured categories and custom tags using advanced array transformations (`TOROW(UNIQUE(...))`).*

---

## 💡 Key Value & Operational Impact
* **Error Reduction:** Eliminated manual calculation mistakes in monthly reporting through automated formula-driven workflows.
* **Multi-Account Visibility:** Instant visibility into cash versus card liquidity, liabilities, and project-specific funds.
* **Scalability:** Built as a reusable template framework that can be easily adapted by other civil associations and student organizations.

---
*Developed for civil association financial operations.*
