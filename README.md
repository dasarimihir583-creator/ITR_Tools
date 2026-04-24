# TDS_Tools: Smart Calculation & Section Determination

A specialized logic engine designed to assist finance professionals in correctly identifying TDS sections and calculating deductions per Income Tax Act regulations.

## 🛠️ Features
* **Smart Questionnaire:** A conversational, step-by-step UI that guides the user through payment nature, payee type (Individual/HUF vs. Company/Firm), and PAN status.
* **Automated Section Mapping:** Automatically maps inputs to specific TDS sections (e.g., 194C, 194J, 194I, 194A, 194Q).
* **Threshold & Limit Logic:** Handles complex tax scenarios including:
    * Single vs. Annual aggregate limits.
    * Higher deduction rates for non-PAN cases.
    * Excess-amount calculation logic (e.g., for Section 194Q).
* **Instant Calculation:** Real-time computation of TDS amount and net payable, with an integrated "Accountant's Guide" for compliance reminders.

## 📋 Supported Sections
This tool includes logic for, but is not limited to:
* **194C:** Payments to Contractors
* **194J:** Fees for Professional/Technical Services
* **194I:** Rent for Land, Building, or Machinery
* **194A:** Interest on Loans
* **194Q:** Purchase of Goods

## 💻 Tech Stack
* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript.
* **Architecture:** Static, client-side logic engine for maximum privacy and data security.

---
*Disclaimer: These tools are provided for educational and audit assistance purposes. Always validate calculations against official statutory provisions and your professional judgment.*
