# Selenium Java Framework

A robust, scalable, and maintainable Selenium automation framework built using **Java**, **TestNG**, and **Maven**.

## Features
- Selenium WebDriver (Java)
- TestNG with parallel execution
- Page Object Model (POM)
- Config-driven (per-environment)
- Explicit waits utilities
- Headless support (CI-ready)
- Logging with SLF4J + Logback
- GitHub Actions workflow included

## Quick Start
```bash
# Run tests (defaults: env=dev, browser=chrome, headless=true)
mvn -B clean test -Denv=dev -Dbrowser=chrome -Dheadless=true
```
