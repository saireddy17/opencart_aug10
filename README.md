# Hybrid Driven Framework for Open Cart App

## Overview

This repository contains a Hybrid Driven Framework for automated testing of the Open Cart application. The framework is implemented using Java, Selenium, TestNG, and Maven, following the Page Object Model for enhanced reusability.

## Project Structure

The project follows a structured layout with Maven for dependency management. The key components include:

- **src/main:** Java source code
  - **pageObjects:** BasePage, HomePage, RegistrationPage,LoginPage,MyAccountPage,SearchPage,ShoppingCartPage,CheckoutPage
  - **testBase:** BaseClass
- **src/test:** Test-related resources
  - **java/testCases:** AccountRegistrationTest, LoginTest, LoginDataDrivenTest,Search Product,Add Product to Cart,End-To-End Test
  - **resources:** log4j2.xml, config.properties
  - **utilities:** ExtentReportUtility, ExcelUtility, DataProviders
- **testData:** TestData.xlsx
- **testng.xml:** TestNG configuration
- **grouping.xml:** TestNG configuration for test groups
- **pom.xml:** Maven configuration
- **run.bat:** Batch file for running tests
- **.gitignore:** Git ignore file

## BasePage

### 1. BasePage

- BasePage under pageObjects includes a constructor for reusability.

## Page Object Classes

### 2. Page Object Classes

- HomePage and RegistrationPage extend BasePage for code reusability.

## Account Registration Test

### 3. Account Registration Test

- AccountRegistrationTest under testCases validates account registration.

## Logging with log4j2

### 4. Adding logs to the test case (log4j2)

- log4j2.xml configures logging.
- BaseClass and AccountRegistrationTest have log statements.

## Cross Browser and Parallel Execution

### 5. Run Tests on Desired Browser/Cross Browser/Parallel

- testng.xml configures browser and parallel execution settings.

## Configurations from config.properties

### 6. Read Common values from config.properties file.

- config.properties stores common values like URLs and credentials.

## Extent Reports Integration

### 7. Add Extent Reports to Project

- ExtentReportUtility and captureScreen() method in BaseClass for detailed reporting.
- ExtentReportUtility added as a listener in testng.xml.

##  Test Case

### 8. Test Case

- TC_001_AccountRegistrationTest
- LoginTest validates user login.
- TC_002_LoginTest
- TC_003_LoginDDT
- Page object classes updated for login functionality.
- TC_004_Search
- TC_004_SearchProductTest
- TC_005_AddToCartPageTest
- TC_006_EndToEndTest
- TC005_AdvSearch
## Data Driven Login Test

### 9. Data Driven Login Test

- ExcelUtility manages test data.
- MyAccountPage updated for logout link.
- DataProviders class for data-driven tests.
- LoginDataDrivenTest reads data from Excel.

## Grouping Tests

### 10. Grouping Tests

- Tests grouped into Sanity, Regression, and Master.
- BaseClass setup() and teardown() added to all groups.
- grouping.xml for executing specific test groups.

## Run Failed Tests

### 11. Run Failed Tests

- testng-failed.xml generated for rerunning failed tests.

## Running Tests Using Maven, Command Prompt & run.bat

### 12. Run Tests using Maven pom.xml, Command Prompt & run.bat file.

- Maven configured to run tests.
- run.bat for easy command line execution.

## Code Repository and Version Control

### 13. Push the Code to Git & GitHub Repository

- Code stored in a Git repository on GitHub.

## Integration with Jenkins

### 14. Run Tests using Jenkins

- Jenkins configured for continuous integration.

## Conclusion

This documentation serves as a comprehensive guide for understanding, configuring, and expanding the Hybrid Driven Framework for the Open Cart application. The structure and features provided facilitate efficient test automation and reporting.

## Clone the repository:

git clone https://github.com/saireddy17/opencart_aug10

# Screenshot:

![Screenshot (171)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/01.png)

![Screenshot (172)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/02.png)

![Screenshot (173)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/03.png)

![Screenshot (174)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/04.png)

![Screenshot (175)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/05.png)

![Screenshot (176)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/06.png)

![Screenshot (184)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/07.png)

![Screenshot (185)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/08.png)

![Screenshot (186)](https://github.com/saireddy17/opencart_aug10/blob/main/IMAGES/09.png)

