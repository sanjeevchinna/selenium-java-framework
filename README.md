# selenium-java-framework
Selenium Java Framework is a lightweight yet powerful automation testing framework designed for UI and API testing.
It follows industry best practices, ensuring scalability, maintainability, and ease of integration with CI/CD pipelines.

✨ Key Features:

Built on Selenium WebDriver with Java.

Test execution management using TestNG.

Maven for dependency management and build lifecycle.

Page Object Model (POM) design pattern for better maintainability.

Config-driven execution (properties files for environment configs).

Supports parallel execution for faster test runs.

Logging & Reporting with Extent Reports / Allure Reports.

Easy to integrate with CI/CD tools like Jenkins, GitHub Actions, or GitLab CI.

Extensible structure for adding API tests (RestAssured) or DB validation.


Typical Folder Structure

selenium-java-framework/
│── src/main/java/com/framework/        # Core framework utilities
│── src/main/java/com/pages/            # Page Object Model classes
│── src/test/java/com/tests/            # Test classes
│── src/test/resources/                 # Test data, config files
│── reports/                            # Test execution reports
│── pom.xml                             # Maven dependencies
│── testng.xml                          # TestNG suite file
│── README.md                           # Documentation
│── .gitignore                          # Ignore unnecessary files
