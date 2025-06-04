#PMarsOnBoardingTask2 Automation Framework

This framework provides automated functional testing for web applications with the following features:


Reqnroll: Implements Cucumber's Gherkin syntax for readable tests
Selenium WebDriver: Handles browser interactions
NUnit: Manages test execution and assertions
ExtentReports: Generates HTML test reports
Page Object Model (POM): Separates test logic from page interactions

Prerequisites
.NET SDK: Version 8.0 or higher (install from dotnet.microsoft.com)

IDE: Visual Studio Code or Visual Studio (recommended)

Chrome Browser: Required for Selenium WebDriver (ChromeDriver version must match your browser version via
WebDriverManager)

## 🚀 Technologies Used

| Technology       | Purpose                                       |
|------------------|-----------------------------------------------|
| ReqnRoll         | BDD framework (Gherkin syntax, step binding)  |
| Selenium WebDriver | Browser automation                          |
| NUnit            | Test framework and assertions                 |
| ExtentReports    | Test report generation (HTML)                 |
| Page Object Model (POM) | Separation of test logic and UI logic |

## 📁 Project Structure
PMarsOnBoardingTask2/
│
├── Features/ # .feature files (Gherkin syntax)
│ └── Login.feature
│
├── StepDefinitions/ # C# methods that bind to Gherkin steps
│ └── LoginSteps.cs
│
├── Pages/ # Page Object Model classes
│ └── LoginPage.cs
│
├── PMarsOnBoardingTask2.csproj # Project file with NuGet packages
└── README.md

## ✅ Current Progress

- [x] ReqnRoll package installed
- [x] Selenium and NUnit integrated
- [x] Project structure created
- [x] Sample `.feature` file added
- [ ] Step Definitions implemented
- [ ] Page Object class created
- [ ] Test reports configured
- [ ] CI integration (optional)
