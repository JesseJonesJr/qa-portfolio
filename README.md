# QA Portfolio – Jesse Jones

## Overview

This portfolio showcases end-to-end QA work across **manual testing, API testing, UI automation, CI/CD pipeline engineering, and FinTech test plan design**.  
Projects demonstrate **hands-on skills** in test planning, structured documentation, bug reporting, end-to-end automation scripting, and regulated-systems thinking.

---

## Projects

### Mobile Money Platform – Test Plan (FinTech)

An 84-case test plan for a fictional mobile money platform covering KYC, authentication, money movement, agent network flows, cross-border FX, and compliance. Designed to demonstrate FinTech QA depth:

* Money math precision, idempotency on network retries, atomic concurrency
* AML, sanctions, and PEP screening compliance
* Hash-chained audit ledgers with tamper-evidence verification
* Transparent FX margin disclosure (Wise-style)
* Agent commission accounting with banker's rounding and idempotent end-of-day settlement
* Race-condition tests for daily limit aggregation and structuring patterns

The plan draws on patterns from Wise, Stripe, GhIPSS, and major mobile money operators in Africa and Asia. Applicable to mobile money platforms, African and global FinTech, neobanks, remittance providers, and any platform handling regulated money flows.

📂 [GitHub Repo – Mobile Money Test Plan](https://github.com/JesseJonesJr/mobile-money-test-plan)

---

### Client Project A – Auth UI Testing (Playwright + CI/CD + Docker)

[![Playwright Tests](https://github.com/JesseJonesJr/playwright-auth-testing/actions/workflows/playwright.yml/badge.svg)](https://github.com/JesseJonesJr/playwright-auth-testing/actions/workflows/playwright.yml)

* Wrote a 50-case test plan spanning 5 authentication flows, identifying 2 bugs during the planning phase before writing any code
* Automated 36 end-to-end tests in Playwright + TypeScript, achieving 72/72 pass rate across Chromium and Firefox
* Validated multi-step flows including OTP verification, password reset, and country auto-detection
* Configured GitHub Actions CI/CD that runs the Playwright suite inside Microsoft's official Playwright Docker container, with the private application repo cloned, built, and started on every PR and push to main; uploads HTML reports and raw failure artifacts (screenshots, videos, traces)
* CI exposed a real "works on my machine" drift on its first run, demonstrating the value of testing against actual deployable code
* Measured caching optimizations in CI and made data-driven decisions: kept npm caching, removed Docker image caching after measuring it provided no benefit for pre-built images from a CDN

📂 [GitHub Repo – Playwright Auth Testing](https://github.com/JesseJonesJr/playwright-auth-testing)

---

### ClientX – Manual QA (Mobile App)

- Tested 5 core modules (Auth, Missions, Rewards, etc.)
- Wrote and executed 67 test cases
- Logged and tracked 13+ verified bugs
- Created QA Summary Reports, Bug Tracker, and Retest Logs  

📂 [ClientX QA Folder (Google Drive)](https://drive.google.com/drive/folders/1qdKL7kS79GJMTSaMlBhZtVdd6hHPJNbe?usp=sharing)

---

### Reqres API – API Testing (Postman)

- Built a Postman collection with 5 API test cases
- Covered GET, POST, PUT, and login token handling
- Wrote JavaScript assertions for status codes, data validation, and performance
- Documented test cases and exported Postman collection  

📂 [GitHub Repo – Reqres API Testing](https://github.com/JesseJonesJr/reqres-api-testing)

---

## Early Automation Practice

### SauceDemo – UI Automation (Cypress)

* Automated login, negative login, logout, and checkout flows
* Implemented end-to-end scenarios using Cypress (JavaScript)
* Demonstrated foundational UI regression coverage on a public demo site

📂 [GitHub Repo – Cypress Web Automation](https://github.com/JesseJonesJr/cypress-web-automation)

---

## Current Focus

* Test automation and CI/CD: building and owning Playwright suites in Dockerized pipelines
* FinTech and regulated-systems QA: payment validation, transaction accuracy, currency handling, compliance

---

## Tools & Technologies

| Area | Tools |
| --- | --- |
| Manual Testing | Google Docs, Sheets, Android Emulator |
| API Testing | Postman, REST APIs, JSON |
| Automation | Playwright, Cypress, Selenium |
| CI/CD | GitHub Actions, Docker |
| Programming | JavaScript, TypeScript, Python |
| Version Control | Git, GitHub |
| Collaboration | Slack, Shortcut |

---

## Contact

- GitHub: [@JesseJonesJr](https://github.com/JesseJonesJr)
- LinkedIn: [@JesseJones](www.linkedin.com/in/jesse-jones-6b2841279)

---

## About

Built and maintained by Jesse Jones, a frontend developer and QA engineer.
