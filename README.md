# Playwright Page Object Model (POM) Demo

This repository is part of my hands-on learning journey with **Playwright** and **TypeScript / JavaScript** for Automated Software Testing. 

It covers the implementation of the **Page Object Model (POM)** design pattern to create maintainable, reusable, and scalable automated test scripts, with test workflows initially recorded and generated using **Playwright Codegen**.

---

## Acknowledgments

Special thanks to **Raghav Pal** for his insightful Playwright Beginner Tutorials on YouTube, which served as the reference for building this project and repeating the implementation steps hands-on.

---

## Key Concepts & Tools Covered

* **Framework:** Playwright Test Runner
* **Design Pattern:** Page Object Model (POM)
* **Test Recording:** Playwright Codegen (`npx playwright codegen`)
* **Features:** End-to-End (E2E) UI Testing, Automated Workflows, Modular Test Architecture

---

## Getting Started

### Prerequisites
* Node.js (v14 or higher)
* Visual Studio Code

### Installation

1. Clone the repository:
git clone https://github.com/selinozerim/Playwright_PageObjectModel.git

2. Navigate to the project directory:
cd Playwright_PageObjectModel

3. Install dependencies:
npm install

4. Install Playwright browsers:
npx playwright install

### Running Tests & Codegen

* Execute all tests:
npx playwright test

* Record tests using Codegen:
npx playwright codegen

* View HTML test report:
npx playwright show-report
