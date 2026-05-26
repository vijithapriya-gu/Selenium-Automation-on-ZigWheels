# Selenium-Automation-on-ZigWheels
🚗 ZigWheels Automation Testing Framework
https://img.shields.io/badge/Language-Java-blue
https://img.shields.io/badge/Automation-Selenium-green
https://img.shields.io/badge/Build-Maven-orange
https://img.shields.io/badge/TestNG-red
https://img.shields.io/badge/License-MIT-lightgrey

📌 Project Overview
ZigWheelsAutomation is a Selenium-based automation testing framework built to validate and automate key functionalities of the ZigWheels web application.
The framework is developed using Java and follows a modular, scalable, and maintainable design, ensuring ease of test execution, reusability, and extensibility.

🛠 Tech Stack

Programming Language: Java
Automation Tool: Selenium WebDriver
Build Tool: Maven
Test Framework: TestNG
Reporting / Data Handling: Apache POI
Version Control: Git & GitHub


📁 Project Structure
ZigWheelsAutomation
│
├── .idea/
├── .mvn/
├── src/
│   ├── main/java/
│   │   ├── base/
│   │   │   └── BaseTest.java
│   │   ├── pages/
│   │   │   ├── HomePage.java
│   │   │   ├── LoginPage.java
│   │   │   ├── UpcomingBikesPage.java
│   │   │   └── UsedCarsPage.java
│   │   └── utils/
│   │       ├── BrowserFactory.java
│   │       ├── ScreenshotUtils.java
│   │       └── WaitUtils.java
│   │
│   └── test/java/tests/
│       ├── UpcomingBikesTest.java
│       ├── UsedCarsTest.java
│       └── LoginTest.java
│
├── testng.xml
├── pom.xml
└── README.md


✨ Key Features

✅ Selenium WebDriver-based UI automation
✅ Page Object Model (POM) design pattern
✅ Maven for dependency and build management
✅ Centralized browser initialization
✅ Explicit wait utilities
✅ Screenshot capture for debugging
✅ CI/CD integration readiness


✅ Test Scenarios Covered

🔍 Identify upcoming Honda bikes with price < ₹4 Lakhs and capture details
🚗 Validate used popular car models available in Chennai
🔐 Perform negative login validation using Google Sign-In


🧪 Testing Types Performed

Functional Testing
UI Testing
Regression Testing
Data Validation Testing
Negative Testing
Smoke Testing
Automation Testing
Manual Testing


▶️ How to Run the Tests
✅ Prerequisites
Make sure the following are installed:

Java JDK 8 or above
Maven
Chrome / Firefox browser
IDE (IntelliJ IDEA / Eclipse recommended)
