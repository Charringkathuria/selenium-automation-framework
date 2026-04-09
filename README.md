# Selenium Automation Framework

![Java](https://img.shields.io/badge/Java-17-orange)
![Selenium](https://img.shields.io/badge/Selenium-4.18.1-green)
![TestNG](https://img.shields.io/badge/TestNG-7.9.0-red)
![Maven](https://img.shields.io/badge/Maven-3.9.14-blue)
![REST Assured](https://img.shields.io/badge/REST%20Assured-5.4.0-yellowgreen)

## 🚀 Framework Overview
Production grade Hybrid Automation Framework built with 
Selenium WebDriver, Java, TestNG and REST Assured.

## 🏗️ Framework Architecture
- **Type**: Hybrid Framework (POM + Data Driven)
- **Design Pattern**: Page Object Model (POM)
- **Language**: Java 17
- **Build Tool**: Maven
- **Test Framework**: TestNG
- **API Testing**: REST Assured
- **Reporting**: Extent Reports
- **Logging**: Log4j2
- **CI/CD**: Jenkins

## 📁 Project Structure
```
selenium-automation-framework/
├── src/main/java/com/charring/framework/
│   ├── base/          # BasePage, BaseTest
│   ├── config/        # ConfigReader
│   ├── constants/     # AppConstants
│   ├── driver/        # DriverManager
│   ├── enums/         # BrowserType, Environment
│   ├── listeners/     # TestListener, RetryAnalyzer
│   ├── pages/         # Page Object classes
│   ├── reports/       # ExtentReportManager
│   └── utils/         # Utility classes
└── src/test/
    ├── java/          # Test classes
    └── resources/     # Config, TestData, TestSuites
```

## 🌐 Applications Under Test
| Domain | Application |
|--------|-------------|
| E-Commerce | AutomationExercise |
| HRMS | OrangeHRM |

## ▶️ How to Run
```bash
# Run smoke suite
mvn test -Dsuite=smoke

# Run regression suite  
mvn test -Dsuite=regression

# Run with specific browser
mvn test -Dbrowser=firefox
```

## 📊 Test Coverage
- UI Test Cases: 45+
- API Test Cases: 20+
- E2E Test Cases: 10+
