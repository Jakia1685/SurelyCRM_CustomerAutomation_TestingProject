# SurelyCRM Customer Automation
Web UI automation testing project for SurelyCRM using **Python, Selenium WebDriver, and PyTest**.

## Test Flow

Login → Customers → Add Customer → Enter Customer Information → Save → Verify Customer → Logout → PASSED

## Test Data

- First Name: Jakia
- Last Name: Sultana
- Phone: 01300000000
- Email: jakia1685@gmail.com

## Technologies

- Python
- Selenium WebDriver
- PyTest
- Page Object Model (POM)

## Run Project

python -m pytest -v -s --html=reports/crm_report.html --self-contained-html
