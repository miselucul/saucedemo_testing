# SauceDemo QA Testing Portfolio Project (Manual + Automation + API)

This repository contains an end-to-end QA Testing Portfolio project for the **SauceDemo e-commerce web application** and **Reqres.in REST API**.

The purpose of this project is to demonstrate real-world QA skills including **manual testing**, **test documentation**, **bug reporting**, **UI automation testing (Playwright & Selenium)**, and **API testing (Postman/Newman)** with optional CI/CD integration using GitHub Actions.

---

## 📌 Project Overview

**Website Under Test:** https://www.saucedemo.com/  
**API Under Test:** https://reqres.in/

This project covers key QA activities such as:
- Creating test plan and test documentation
- Designing and executing manual test cases
- Exploratory testing
- Reporting and verifying bugs
- Building UI automation frameworks (Playwright + Selenium)
- Performing API testing using Postman
- Running regression tests
- Generating test reports
- CI pipeline setup using GitHub Actions (optional)

---

## 🛠 Tools & Technologies Used

### Manual Testing
- Functional Testing
- Regression Testing
- UI/UX Testing
- Exploratory Testing

### Test Documentation & Reporting
- Markdown Documentation
- Excel / Google Sheets (optional)
- Qase.io format test cases (optional)

### Automation Testing
- **Playwright** (JavaScript / TypeScript)
- **Selenium WebDriver** (Python + Pytest)

### API Testing
- Postman
- Newman
- Swagger Documentation Validation

### Bug Tracking
- Jira-style Bug Report Format

### CI/CD (Optional)
- GitHub Actions

---

# 📂 Project Folder Structure

Struktur folder proyek **qa-saucedemo-e2e-testing**:


qa-saucedemo-e2e-testing/
│
├── 📄 README.md
│
├── 🗂 docs/ # Dokumen proyek
│ ├── Test_Plan.md
│ ├── Requirements_Breakdown.md
│ ├── Test_Strategy.md # Opsional
│ ├── Test_Summary_Report.md
│ └── Bug_Report.md
│
├── 📝 manual-testing/ # Manual test cases & suites
│ ├── Test_Cases.xlsx
│ ├── Test_Cases_GoogleSheet_Link.txt
│ ├── Smoke_Test_Suite.md
│ └── Regression_Test_Suite.md
│
├── 🐞 bug-reports/ # Bug report files
│ ├── Bug_001.md
│ ├── Bug_002.md
│ ├── Bug_003.md
│ └── screenshots/
│ ├── bug_001.png
│ └── bug_002.png
│
├── ⚡ api-testing/ # API testing files
│ ├── postman_collection.json
│ ├── postman_environment.json
│ └── newman-report.html
│
├── 🧪 playwright-ui-tests/ # Playwright UI tests
│ ├── tests/
│ ├── pages/
│ ├── playwright.config.ts
│ └── package.json
│
├── 💻 selenium-ui-tests/ # Selenium UI tests
│ ├── tests/
│ ├── pages/
│ └── requirements.txt
│
└── 🔧 .github/ # GitHub Actions workflows
└── workflows/
├── postman-ci.yml
└── playwright-ci.yml

## ✅ Test Coverage

### Web Application Testing (SauceDemo)
The following modules are covered:
- Login / Logout
- Product List Page
- Product Sorting
- Add to Cart / Remove from Cart
- Cart Page Validation
- Checkout Flow
- Order Confirmation
- UI/UX Validation
- Cross-browser Testing

### API Testing (Reqres.in)
Covered API testing areas:
- GET users list
- GET single user
- POST create user
- PUT update user
- PATCH update user
- DELETE user
- POST login/register
- Negative test scenarios (invalid payload, missing fields)
- Status code validation
- Response schema validation

---

## 🐞 Bug Reporting

All bugs are documented using a Jira-style bug report format including:
- Steps to reproduce
- Actual vs expected result
- Severity & priority
- Test environment
- Screenshot evidence (if available)

---

## 🚀 Future Enhancements (Planned)

This repository may include:
- Manual test cases in Excel/Google Sheets format
- Bug reports with screenshots
- Postman collection + Newman reports
- Playwright automation framework
- Selenium automation framework
- GitHub Actions workflow for CI regression testing

---

## 👤 Author

**Nusaibah Noor A.S**  
**LinkedIn:** [Nusaibah Noor A.S](https://www.linkedin.com/in/nusaibah-noor-as-sunnah)
**GitHub:** [AndrewLovesLasagna](https://github.com/miselucul)

---

## 📌 Notes

This project is created purely for learning and portfolio purposes using publicly available demo applications.
