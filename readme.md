# 🧪 QA Automation Portfolio: Robot Accountant & Closure State Validation

> About this repository: This project demonstrates unit testing and algorithm validation using Jest for a JavaScript application implementing state encapsulation and calculations using closures (Robot Accountant). It also highlights a modern "Shift-Left" QA approach through extensive static code analysis and Continuous Integration (CI/CD).

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Static Analysis](https://img.shields.io/badge/Static_Analysis-4B32C3?style=for-the-badge&logo=eslint&logoColor=black)

## 🎯 Project Overview

This application is a Vanilla JavaScript implementation focused on advanced closure patterns and state management, simulating a robot accountant that tracks and accumulates operations dynamically.

As a QA Automation / Software Testing Engineer, my focus in this repository is to validate core algorithmic logic, verify state encapsulation across multiple function invocations, and ensure calculation accuracy through comprehensive unit testing.

## 🛠️ QA Tech Stack & Tools

* **Unit Testing:** Jest (`src/makeRobotAccountant.test.js`)
* **CI/CD Pipeline:** GitHub Actions (Automated test execution on push/PR)
* **Static Code Analysis (Shift-Left QA):** ESLint, Prettier
* **Core Technologies:** Vanilla JS (ES6+)

## 📊 Test Strategy & Coverage

### 1. Unit Testing (Jest)
Located in `src/makeRobotAccountant.test.js`, the unit test suite verifies:
* Correct state persistence and data encapsulation using closures.
* Edge cases, sequential actions, and boundary conditions during calculations.
* Reliability and accuracy of the core robot accountant functions.

### 2. Continuous Integration (CI/CD)
The project utilizes GitHub Actions (`.github/workflows/test.yml`) to enforce quality gates. Every commit automatically triggers a pipeline that:
* Lints the code files to catch syntax and formatting issues early.
* Runs the Jest unit test suite in a headless environment.

## 🚀 How to Run the Tests Locally

To evaluate the test scripts and static analysis tools on your local machine, follow these steps:

### 1. Environment Setup
Clone the repository and install the Node.js dependencies:
```bash
npm install
