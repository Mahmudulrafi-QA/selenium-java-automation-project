# Selenium Automation with Java

## Project Overview
This is a Selenium WebDriver automation project using Java and TestNG framework.  
It automates the testing of web applications by simulating user interactions on browsers.

## Features
- Browser compatibility: Chrome, Firefox (configurable)
- Uses Maven for dependency management
- TestNG framework for test execution and reporting
- Page Object Model (POM) design pattern implemented
- Sample test cases for login, navigation, and form submission
- Includes explicit waits and proper exception handling

## Prerequisites
- Java JDK 8 or higher installed
- Maven installed
- IDE (IntelliJ IDEA, Eclipse, or VS Code)
- ChromeDriver or GeckoDriver setup and added to system PATH

## Project Structure
/src/main/java - Page classes and utilities
/src/test/java - Test classes
/pom.xml - Maven dependencies and plugins

## How to Run
1. Clone or download the repository  
2. Open the project in your favorite IDE  
3. Make sure Maven dependencies are downloaded (`mvn clean install`)  
4. Update browser driver path if needed in the config  
5. Run tests using TestNG:  
   - From IDE: Run the TestNG XML suite file or test classes  
   - From command line:  
   ```bash
   mvn test
