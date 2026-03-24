# Enterprise Risk Management (ERM) Platform

A high-fidelity, interactive front-end replica of a B2B Enterprise Risk Management dashboard. This project simulates a secure portal used by consulting firms and enterprises to conduct scalable internal security audits and map compliance to international frameworks.

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20Vanilla%20JS-blue)

## 📌 Project Overview
This Single Page Application (SPA) prototype allows employees ("Staff Respondents") to log in and securely complete multi-step risk assessments. It was built with strict software quality assurance principles in mind, ensuring reliable state management, rigorous form validation, and a seamless user experience without requiring page reloads.

### Key Features
* **Authentication UI:** A role-based login screen (Compliance Manager, Risk Owner, Staff Respondent) mimicking enterprise access controls.
* **Dynamic SPA Routing:** Vanilla JavaScript handles seamless transitions between the Login, Dashboard, Questionnaire, and History views.
* **Interactive Assessment Engine:** * Tracks user progress dynamically with a visual progress bar.
  * Supports multiple question types (Standard radio buttons and complex Rating scales).
  * Validates inputs to ensure users cannot skip mandatory questions.
* **Automated Summary & History:** Generates a real-time summary of the user's inputs upon completion and dynamically updates the assessment history table.
* **Modern UI/UX:** A responsive, dark-mode-first interface using CSS variables, CSS Grid/Flexbox, and the Inter typeface for optimal readability.

## 💼 Business Value
This platform structure solves several critical bottlenecks for risk management and IT consulting firms:
1. **Scalable Auditing:** Replaces manual consultant interviews with a distributable digital questionnaire, saving hundreds of billable hours.
2. **Framework Alignment:** Questions are structured to collect data mapped directly to **ISO 27001**, **ISO 22301**, and **NDPR** compliance standards.
3. **Data Standardization:** Captures structured data ready for automated AI analysis and executive vulnerability reporting.

## 🛠️ Tech Stack
* **HTML5:** Semantic structuring and accessibility.
* **CSS3:** Custom variables, Flexbox/Grid layouts, and keyframe animations.
* **JavaScript (ES6+):** DOM manipulation, state tracking, and event handling.

## 🚀 Getting Started
To view this project locally:
1. Clone the repository:
   ```bash
   git clone [https://github.com/kellyemmy/ERM.git](https://github.com/kellyemmy/ERM.git)
