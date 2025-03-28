# Selenium Automation Framework

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![TestNG](https://img.shields.io/badge/testng-7.8.0-red)]()
[![Selenium](https://img.shields.io/badge/selenium-4.10.0-orange)]()

A robust test automation framework using Selenium WebDriver, TestNG, and Maven with Page Object Model (POM) design pattern.

## 📌 Framework Features

- **Page Object Model** implementation for maintainable code
- **Multi-browser support** (Chrome, Firefox, Edge)
- **Extent Reports** with screenshots for detailed reporting
- **Data-driven testing** using TestNG DataProviders
- **Configuration management** via properties files
- **Parallel test execution** capability

## 🛠️ Technical Stack

| Component       | Technology |
|----------------|------------|
| Test Runner    | TestNG     |
| Browser Automation | Selenium WebDriver |
| Build Tool     | Maven      |
| Reporting      | ExtentReports |
| Language       | Java 11    |

## 🛠️ Prerequisites

- Java JDK 8 or later
- Maven 3.6.0+
- Chrome/Firefox browsers installed
- IDE (IntelliJ/Eclipse recommended)

## 🚀 Quick Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-framework.git
2. **Install dependencies**:
   ```bash
   mvn clean install
3. **Run tests**:
    ```bash
   mvn test

## Project Structure 

Experion_selenium_Poject/ 
├── src/ 
│ ├── main/ 
│ │ ├── java/ 
│ │ │ └── com/ 
│ │ │ ├── com.experion.pages/ # Page classes 
│ │ │ ├── com.experion.utils/ # Utility classes 
│ │ │ ├── com.experion.managers/ # Driver/Report managers 
│ │ │ └── com.experion.config/ # Configuration classes 
│ │ └── resources/ # Property files, test data 
│ │     └── config.properties # Configuration file 
│ └── test/ 
│ ├── java/
│ │     └── com.experion.testData  # Test Data
│ │     └── com.experion.tests # Test classes
│ └── resources/ 
│       └── testng.xml # TestNG XMLs 
├── test-output/ # Reports and screenshots 
├── pom.xml # Maven configuration 
└── README.md # This file


## 📊 Reports 

-- **Extent Reports: test-output/Test-Report-{time stamp}.html
-- **TestNG Reports: test-output/index.html
-- **Screenshots: test-output/screenshots/

🧩 Key Components

1. **Page Objects: src/main/java/com/experion/pages/
   Example: LoginPage.java, ProductsPage.java
2. **Test Data: src/test/java/com/yourcompany/testdata/
   Example: LoginTestData.java
3. **Utilities:
   DriverManager.java - Handles WebDriver instances
   ExtentReportManager.java - Manages reporting
   ScreenshotUtils.java - Captures screenshots

📧 Contact
**Your Name - Nandhakumar KR
**Your enail - krnandhakumar.qa@gmail.com
**Project Link: https://github.com/Nandhakumar-qa/Experion-automation-framework/
