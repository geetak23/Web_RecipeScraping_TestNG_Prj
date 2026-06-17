# Recipe Scraping Automation

Automated web scraping and validation suite built with Selenium WebDriver 
and TestNG, using a live recipe web application.

## What this project covers

- **Recipe filter validation** — scrapes and verifies recipe data across 
  multiple dietary filters:
  - LCHF (Low Carb High Fat)
  - LFV (Low Fat Vegetarian)
  - Vegan / Vegetarian
  - Allergies (gluten, dairy, nuts)

- **Ingredients & comorbidities mapping** — validates the relationship 
  between recipe ingredients and associated health conditions
- Allure reports for detailed test results, step-level traceability, 
  and failure analysis
- Structured test suites with TestNG and auto-generated HTML reports

## Tech Stack
Java | Selenium WebDriver | TestNG | Maven | Allure

## Run tests
Execute `testng.xml` from your IDE or via Maven:
